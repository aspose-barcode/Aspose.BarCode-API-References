---
title: ThreadsManager
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.common.threads/threadsmanager/
---
**Inheritance:**
java.lang.Object
```
public class ThreadsManager
```

Class implements multithreading tool which allows run paralled kernels(like shader or OpenCL kernels) and tasks. Both, task and kernel running returns Exception list which were invoked in the kernel or tasks functions

Kernel is a simple functions which is run in X instances, where every instance accepts KernelInstanceData(lock object for the whole current job, current instance index, ammount of instances in the job) To use kernel you should call RunKernelAndWait which returs Exception list from kernel

Task is independent function, which list can be run in parallel. To run tasks you should put the tasks list to RunTasksAndWait which returs Exception list from tasks

IThreadsOptionsRequest is required to get maximal cores for single job, which show maximal ammount threads which can run in single call of RunKernelAndWait or RunTasksAndWait, and maximal allowed additional threads for the whole framework.
## Constructors

| Constructor | Description |
| --- | --- |
| [ThreadsManager(IThreadsOptionsRequest aThreadsOptions, IThreadsExceptionHandler aExceptionHandler)](#ThreadsManager-com.aspose.barcode.barcoderecognition.common.threads.IThreadsOptionsRequest-com.aspose.barcode.barcoderecognition.common.threads.IThreadsExceptionHandler-) | Init multithreaded framework instance |
## Fields

| Field | Description |
| --- | --- |
| [Manager](#Manager) | Global instance of Thread Manager. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [runKernelAndWait(IKernelAction kernel)](#runKernelAndWait-com.aspose.barcode.barcoderecognition.common.threads.IKernelAction-) | Runs Kernel instances in parallel, which depends on allowed cores for the job |
| [runKernelAndWait(int MaxRequiredCores, IKernelAction kernel)](#runKernelAndWait-int-com.aspose.barcode.barcoderecognition.common.threads.IKernelAction-) | Runs Kernel instances in parallel, which depends on minimal from allowed cores for the job and required cores for the kernel |
| [runTasksAndWait(ITaskAction[] tasks)](#runTasksAndWait-com.aspose.barcode.barcoderecognition.common.threads.ITaskAction...-) | Runs Task list in parallel which depends on allowed cores for the job |
| [runTasksAndWait(int MaxRequiredCores, ITaskAction[] tasks)](#runTasksAndWait-int-com.aspose.barcode.barcoderecognition.common.threads.ITaskAction...-) | Runs Task list in parallel which depends on minimal from allowed cores for the job and required cores for the kernel |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ThreadsManager(IThreadsOptionsRequest aThreadsOptions, IThreadsExceptionHandler aExceptionHandler) {#ThreadsManager-com.aspose.barcode.barcoderecognition.common.threads.IThreadsOptionsRequest-com.aspose.barcode.barcoderecognition.common.threads.IThreadsExceptionHandler-}
```
public ThreadsManager(IThreadsOptionsRequest aThreadsOptions, IThreadsExceptionHandler aExceptionHandler)
```


Init multithreaded framework instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aThreadsOptions | com.aspose.barcode.barcoderecognition.common.threads.IThreadsOptionsRequest | Getter of processor cores and allowed adittional tasks |
| aExceptionHandler | com.aspose.barcode.barcoderecognition.common.threads.IThreadsExceptionHandler | Exception list processor |

### Manager {#Manager}
```
public static ThreadsManager Manager
```


Global instance of Thread Manager. If you need not to use own pool, you should use this

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### runKernelAndWait(IKernelAction kernel) {#runKernelAndWait-com.aspose.barcode.barcoderecognition.common.threads.IKernelAction-}
```
public System.Collections.Generic.List<Exception> runKernelAndWait(IKernelAction kernel)
```


Runs Kernel instances in parallel, which depends on allowed cores for the job

--------------------

> ```
> [Java]
>  
>  ThreadsManager.Manager.runKernelAndWait(kernelInstance);
>  public void kernelAction(KernelInstanceData data)
>  {
>       for (int i = data.ThreadIndex; i <= dimension; i += data.ThreadCount)
>       {
>           iterateData();
>       }
>       synchronized(data.KernelLock)
>       {
>           storeData();
>       }
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kernel | [IKernelAction](../../com.aspose.barcode.barcoderecognition.common.threads/ikernelaction) | current threaded kernel function |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - Exceptions in the kernel instances list
### runKernelAndWait(int MaxRequiredCores, IKernelAction kernel) {#runKernelAndWait-int-com.aspose.barcode.barcoderecognition.common.threads.IKernelAction-}
```
public System.Collections.Generic.List<Exception> runKernelAndWait(int MaxRequiredCores, IKernelAction kernel)
```


Runs Kernel instances in parallel, which depends on minimal from allowed cores for the job and required cores for the kernel

ThreadsManager.Manager.runKernelAndWait(maxRequiredCores, kernelInstance); public void kernelAction(KernelInstanceData data) \{ for (int i = data.ThreadIndex; i <= dimension; i += data.ThreadCount) \{ iterateData(); \} synchronized(data.KernelLock) \{ storeData(); \} \}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| MaxRequiredCores | int | Max cores required for the kernel |
| kernel | [IKernelAction](../../com.aspose.barcode.barcoderecognition.common.threads/ikernelaction) | current threaded kernel function |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - Exceptions in the kernel instances list
### runTasksAndWait(ITaskAction[] tasks) {#runTasksAndWait-com.aspose.barcode.barcoderecognition.common.threads.ITaskAction...-}
```
public System.Collections.Generic.List<Exception> runTasksAndWait(ITaskAction[] tasks)
```


Runs Task list in parallel which depends on allowed cores for the job

--------------------

> ```
> [Java]
>   
>  ThreadsManager.Manager.runTasksAndWait(taskClass, taskClass, taskClass);
>  protected void taskAction(ThreadsJobData data)
>  {
>       doInternal();
>       synchronized(data.JobLock)
>       {
>           storeData();
>       }
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tasks | [ITaskAction\[\]](../../com.aspose.barcode.barcoderecognition.common.threads/itaskaction) | List of tasks to run |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - Exceptions in the tasks list
### runTasksAndWait(int MaxRequiredCores, ITaskAction[] tasks) {#runTasksAndWait-int-com.aspose.barcode.barcoderecognition.common.threads.ITaskAction...-}
```
public System.Collections.Generic.List<Exception> runTasksAndWait(int MaxRequiredCores, ITaskAction[] tasks)
```


Runs Task list in parallel which depends on minimal from allowed cores for the job and required cores for the kernel

--------------------

> ```
> [Java]
>  
>  ThreadsManager.Manager.runTasksAndWait(processorCount, taskClass, taskClass, taskClass);
>  public static void taskAction(ThreadsJobData data)
>  {
>       doInternal();
>       synchronized(data.JobLock)
>       {
>           storeData();
>       }
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| MaxRequiredCores | int | Max cores required for the tasks list |
| tasks | [ITaskAction\[\]](../../com.aspose.barcode.barcoderecognition.common.threads/itaskaction) | List of tasks to run |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - Exceptions in the tasks list
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

