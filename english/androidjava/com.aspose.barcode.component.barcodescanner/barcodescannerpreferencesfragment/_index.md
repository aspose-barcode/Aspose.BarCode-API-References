---
title: BarcodeScannerPreferencesFragment
second_title: Aspose.BarCode for Android via Java API Reference
description: PreferencesFragment can be used for customizing the barcode recognition process using custom GUI.
type: docs
weight: 17
url: /androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferencesfragment/
---
**Inheritance:**
java.lang.Object, androidx.fragment.app.Fragment, androidx.preference.PreferenceFragmentCompat
```
public abstract class BarcodeScannerPreferencesFragment extends PreferenceFragmentCompat
```

PreferencesFragment can be used for customizing the barcode recognition process using custom GUI. PreferencesFragment can be implemented as custom class and can be attached to BarcodeScannerFragment using BarcodeRecognitionSettings.setPreferencesFragment() method.
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeScannerPreferencesFragment()](#BarcodeScannerPreferencesFragment--) |  |
## Fields

| Field | Description |
| --- | --- |
| [ARG_PREFERENCE_ROOT](#ARG-PREFERENCE-ROOT) |  |
## Methods

| Method | Description |
| --- | --- |
| [<I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultCallback<O> arg1)](#-I-O-registerForActivityResult-androidx.activity.result.contract.ActivityResultContract-I-O--androidx.activity.result.ActivityResultCallback-O--) |  |
| [<I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultRegistry arg1, ActivityResultCallback<O> arg2)](#-I-O-registerForActivityResult-androidx.activity.result.contract.ActivityResultContract-I-O--androidx.activity.result.ActivityResultRegistry-androidx.activity.result.ActivityResultCallback-O--) |  |
| [<T>findPreference(CharSequence arg0)](#-T-findPreference-java.lang.CharSequence-) |  |
| [addPreferencesFromResource(int arg0)](#addPreferencesFromResource-int-) |  |
| [dump(String arg0, FileDescriptor arg1, PrintWriter arg2, String[] arg3)](#dump-java.lang.String-java.io.FileDescriptor-java.io.PrintWriter-java.lang.String---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActivity()](#getActivity--) |  |
| [getAllowEnterTransitionOverlap()](#getAllowEnterTransitionOverlap--) |  |
| [getAllowReturnTransitionOverlap()](#getAllowReturnTransitionOverlap--) |  |
| [getArguments()](#getArguments--) |  |
| [getCallbackFragment()](#getCallbackFragment--) |  |
| [getChildFragmentManager()](#getChildFragmentManager--) |  |
| [getClass()](#getClass--) |  |
| [getContext()](#getContext--) |  |
| [getDefaultViewModelProviderFactory()](#getDefaultViewModelProviderFactory--) |  |
| [getEnterTransition()](#getEnterTransition--) |  |
| [getExitTransition()](#getExitTransition--) |  |
| [getFragmentManager()](#getFragmentManager--) |  |
| [getHost()](#getHost--) |  |
| [getId()](#getId--) |  |
| [getLayoutInflater()](#getLayoutInflater--) |  |
| [getLayoutInflater(Bundle arg0)](#getLayoutInflater-android.os.Bundle-) |  |
| [getLifecycle()](#getLifecycle--) |  |
| [getListView()](#getListView--) |  |
| [getLoaderManager()](#getLoaderManager--) |  |
| [getParentFragment()](#getParentFragment--) |  |
| [getParentFragmentManager()](#getParentFragmentManager--) |  |
| [getPreferenceManager()](#getPreferenceManager--) |  |
| [getPreferenceScreen()](#getPreferenceScreen--) |  |
| [getReenterTransition()](#getReenterTransition--) |  |
| [getResources()](#getResources--) |  |
| [getRetainInstance()](#getRetainInstance--) |  |
| [getReturnTransition()](#getReturnTransition--) |  |
| [getSavedStateRegistry()](#getSavedStateRegistry--) |  |
| [getSharedElementEnterTransition()](#getSharedElementEnterTransition--) |  |
| [getSharedElementReturnTransition()](#getSharedElementReturnTransition--) |  |
| [getString(int arg0)](#getString-int-) |  |
| [getString(int arg0, Object[] arg1)](#getString-int-java.lang.Object...-) |  |
| [getTag()](#getTag--) |  |
| [getTargetFragment()](#getTargetFragment--) |  |
| [getTargetRequestCode()](#getTargetRequestCode--) |  |
| [getText(int arg0)](#getText-int-) |  |
| [getUserVisibleHint()](#getUserVisibleHint--) |  |
| [getView()](#getView--) |  |
| [getViewLifecycleOwner()](#getViewLifecycleOwner--) |  |
| [getViewLifecycleOwnerLiveData()](#getViewLifecycleOwnerLiveData--) |  |
| [getViewModelStore()](#getViewModelStore--) |  |
| [hasOptionsMenu()](#hasOptionsMenu--) |  |
| [hashCode()](#hashCode--) |  |
| [instantiate(Context arg0, String arg1)](#instantiate-android.content.Context-java.lang.String-) |  |
| [instantiate(Context arg0, String arg1, Bundle arg2)](#instantiate-android.content.Context-java.lang.String-android.os.Bundle-) |  |
| [isAdded()](#isAdded--) |  |
| [isDetached()](#isDetached--) |  |
| [isHidden()](#isHidden--) |  |
| [isInLayout()](#isInLayout--) |  |
| [isMenuVisible()](#isMenuVisible--) |  |
| [isRemoving()](#isRemoving--) |  |
| [isResumed()](#isResumed--) |  |
| [isStateSaved()](#isStateSaved--) |  |
| [isVisible()](#isVisible--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onActivityCreated(Bundle arg0)](#onActivityCreated-android.os.Bundle-) |  |
| [onActivityResult(int arg0, int arg1, Intent arg2)](#onActivityResult-int-int-android.content.Intent-) |  |
| [onAttach(Activity arg0)](#onAttach-android.app.Activity-) |  |
| [onAttach(Context arg0)](#onAttach-android.content.Context-) |  |
| [onAttachFragment(Fragment arg0)](#onAttachFragment-androidx.fragment.app.Fragment-) |  |
| [onConfigurationChanged(Configuration arg0)](#onConfigurationChanged-android.content.res.Configuration-) |  |
| [onContextItemSelected(MenuItem arg0)](#onContextItemSelected-android.view.MenuItem-) |  |
| [onCreate(Bundle savedInstanceState)](#onCreate-android.os.Bundle-) |  |
| [onCreateAnimation(int arg0, boolean arg1, int arg2)](#onCreateAnimation-int-boolean-int-) |  |
| [onCreateAnimator(int arg0, boolean arg1, int arg2)](#onCreateAnimator-int-boolean-int-) |  |
| [onCreateContextMenu(ContextMenu arg0, View arg1, ContextMenu.ContextMenuInfo arg2)](#onCreateContextMenu-android.view.ContextMenu-android.view.View-android.view.ContextMenu.ContextMenuInfo-) |  |
| [onCreateLayoutManager()](#onCreateLayoutManager--) |  |
| [onCreateOptionsMenu(Menu arg0, MenuInflater arg1)](#onCreateOptionsMenu-android.view.Menu-android.view.MenuInflater-) |  |
| [onCreatePreferences(Bundle arg0, String arg1)](#onCreatePreferences-android.os.Bundle-java.lang.String-) |  |
| [onCreateRecyclerView(LayoutInflater arg0, ViewGroup arg1, Bundle arg2)](#onCreateRecyclerView-android.view.LayoutInflater-android.view.ViewGroup-android.os.Bundle-) |  |
| [onCreateView(LayoutInflater arg0, ViewGroup arg1, Bundle arg2)](#onCreateView-android.view.LayoutInflater-android.view.ViewGroup-android.os.Bundle-) |  |
| [onDestroy()](#onDestroy--) |  |
| [onDestroyOptionsMenu()](#onDestroyOptionsMenu--) |  |
| [onDestroyView()](#onDestroyView--) |  |
| [onDetach()](#onDetach--) |  |
| [onDisplayPreferenceDialog(Preference arg0)](#onDisplayPreferenceDialog-androidx.preference.Preference-) |  |
| [onGetLayoutInflater(Bundle arg0)](#onGetLayoutInflater-android.os.Bundle-) |  |
| [onHiddenChanged(boolean arg0)](#onHiddenChanged-boolean-) |  |
| [onInflate(Activity arg0, AttributeSet arg1, Bundle arg2)](#onInflate-android.app.Activity-android.util.AttributeSet-android.os.Bundle-) |  |
| [onInflate(Context arg0, AttributeSet arg1, Bundle arg2)](#onInflate-android.content.Context-android.util.AttributeSet-android.os.Bundle-) |  |
| [onLowMemory()](#onLowMemory--) |  |
| [onMultiWindowModeChanged(boolean arg0)](#onMultiWindowModeChanged-boolean-) |  |
| [onNavigateToScreen(PreferenceScreen arg0)](#onNavigateToScreen-androidx.preference.PreferenceScreen-) |  |
| [onOptionsItemSelected(MenuItem arg0)](#onOptionsItemSelected-android.view.MenuItem-) |  |
| [onOptionsMenuClosed(Menu arg0)](#onOptionsMenuClosed-android.view.Menu-) |  |
| [onPause()](#onPause--) |  |
| [onPictureInPictureModeChanged(boolean arg0)](#onPictureInPictureModeChanged-boolean-) |  |
| [onPreferenceTreeClick(Preference arg0)](#onPreferenceTreeClick-androidx.preference.Preference-) |  |
| [onPrepareOptionsMenu(Menu arg0)](#onPrepareOptionsMenu-android.view.Menu-) |  |
| [onPrimaryNavigationFragmentChanged(boolean arg0)](#onPrimaryNavigationFragmentChanged-boolean-) |  |
| [onRequestPermissionsResult(int arg0, String[] arg1, int[] arg2)](#onRequestPermissionsResult-int-java.lang.String---int---) |  |
| [onResume()](#onResume--) |  |
| [onSaveInstanceState(Bundle arg0)](#onSaveInstanceState-android.os.Bundle-) |  |
| [onStart()](#onStart--) |  |
| [onStop()](#onStop--) |  |
| [onViewCreated(View arg0, Bundle arg1)](#onViewCreated-android.view.View-android.os.Bundle-) |  |
| [onViewStateRestored(Bundle arg0)](#onViewStateRestored-android.os.Bundle-) |  |
| [postponeEnterTransition()](#postponeEnterTransition--) |  |
| [postponeEnterTransition(long arg0, TimeUnit arg1)](#postponeEnterTransition-long-java.util.concurrent.TimeUnit-) |  |
| [registerForContextMenu(View arg0)](#registerForContextMenu-android.view.View-) |  |
| [requestPermissions(String[] arg0, int arg1)](#requestPermissions-java.lang.String---int-) |  |
| [requireActivity()](#requireActivity--) |  |
| [requireArguments()](#requireArguments--) |  |
| [requireContext()](#requireContext--) |  |
| [requireFragmentManager()](#requireFragmentManager--) |  |
| [requireHost()](#requireHost--) |  |
| [requireParentFragment()](#requireParentFragment--) |  |
| [requireView()](#requireView--) |  |
| [scrollToPreference(Preference arg0)](#scrollToPreference-androidx.preference.Preference-) |  |
| [scrollToPreference(String arg0)](#scrollToPreference-java.lang.String-) |  |
| [setAllowEnterTransitionOverlap(boolean arg0)](#setAllowEnterTransitionOverlap-boolean-) |  |
| [setAllowReturnTransitionOverlap(boolean arg0)](#setAllowReturnTransitionOverlap-boolean-) |  |
| [setArguments(Bundle arg0)](#setArguments-android.os.Bundle-) |  |
| [setDivider(Drawable arg0)](#setDivider-android.graphics.drawable.Drawable-) |  |
| [setDividerHeight(int arg0)](#setDividerHeight-int-) |  |
| [setEnterSharedElementCallback(SharedElementCallback arg0)](#setEnterSharedElementCallback-androidx.core.app.SharedElementCallback-) |  |
| [setEnterTransition(Object arg0)](#setEnterTransition-java.lang.Object-) |  |
| [setExitSharedElementCallback(SharedElementCallback arg0)](#setExitSharedElementCallback-androidx.core.app.SharedElementCallback-) |  |
| [setExitTransition(Object arg0)](#setExitTransition-java.lang.Object-) |  |
| [setHasOptionsMenu(boolean arg0)](#setHasOptionsMenu-boolean-) |  |
| [setInitialSavedState(Fragment.SavedState arg0)](#setInitialSavedState-androidx.fragment.app.Fragment.SavedState-) |  |
| [setMenuVisibility(boolean arg0)](#setMenuVisibility-boolean-) |  |
| [setPreferenceScreen(PreferenceScreen arg0)](#setPreferenceScreen-androidx.preference.PreferenceScreen-) |  |
| [setPreferencesFromResource(int arg0, String arg1)](#setPreferencesFromResource-int-java.lang.String-) |  |
| [setReenterTransition(Object arg0)](#setReenterTransition-java.lang.Object-) |  |
| [setRetainInstance(boolean arg0)](#setRetainInstance-boolean-) |  |
| [setReturnTransition(Object arg0)](#setReturnTransition-java.lang.Object-) |  |
| [setSharedElementEnterTransition(Object arg0)](#setSharedElementEnterTransition-java.lang.Object-) |  |
| [setSharedElementReturnTransition(Object arg0)](#setSharedElementReturnTransition-java.lang.Object-) |  |
| [setTargetFragment(Fragment arg0, int arg1)](#setTargetFragment-androidx.fragment.app.Fragment-int-) |  |
| [setUserVisibleHint(boolean arg0)](#setUserVisibleHint-boolean-) |  |
| [shouldShowRequestPermissionRationale(String arg0)](#shouldShowRequestPermissionRationale-java.lang.String-) |  |
| [startActivity(Intent arg0)](#startActivity-android.content.Intent-) |  |
| [startActivity(Intent arg0, Bundle arg1)](#startActivity-android.content.Intent-android.os.Bundle-) |  |
| [startActivityForResult(Intent arg0, int arg1)](#startActivityForResult-android.content.Intent-int-) |  |
| [startActivityForResult(Intent arg0, int arg1, Bundle arg2)](#startActivityForResult-android.content.Intent-int-android.os.Bundle-) |  |
| [startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5, Bundle arg6)](#startIntentSenderForResult-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-) |  |
| [startPostponedEnterTransition()](#startPostponedEnterTransition--) |  |
| [toString()](#toString--) |  |
| [unregisterForContextMenu(View arg0)](#unregisterForContextMenu-android.view.View-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeScannerPreferencesFragment() {#BarcodeScannerPreferencesFragment--}
```
public BarcodeScannerPreferencesFragment()
```


### ARG_PREFERENCE_ROOT {#ARG-PREFERENCE-ROOT}
```
public static final String ARG_PREFERENCE_ROOT
```


### <I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultCallback<O> arg1) {#-I-O-registerForActivityResult-androidx.activity.result.contract.ActivityResultContract-I-O--androidx.activity.result.ActivityResultCallback-O--}
```
public final ActivityResultLauncher<I> <I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultCallback<O> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.activity.result.contract.ActivityResultContract<I,O> |  |
| arg1 | androidx.activity.result.ActivityResultCallback<O> |  |

**Returns:**
androidx.activity.result.ActivityResultLauncher<I>
### <I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultRegistry arg1, ActivityResultCallback<O> arg2) {#-I-O-registerForActivityResult-androidx.activity.result.contract.ActivityResultContract-I-O--androidx.activity.result.ActivityResultRegistry-androidx.activity.result.ActivityResultCallback-O--}
```
public final ActivityResultLauncher<I> <I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultRegistry arg1, ActivityResultCallback<O> arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.activity.result.contract.ActivityResultContract<I,O> |  |
| arg1 | androidx.activity.result.ActivityResultRegistry |  |
| arg2 | androidx.activity.result.ActivityResultCallback<O> |  |

**Returns:**
androidx.activity.result.ActivityResultLauncher<I>
### <T>findPreference(CharSequence arg0) {#-T-findPreference-java.lang.CharSequence-}
```
public T <T>findPreference(CharSequence arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.CharSequence |  |

**Returns:**
T
### addPreferencesFromResource(int arg0) {#addPreferencesFromResource-int-}
```
public void addPreferencesFromResource(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### dump(String arg0, FileDescriptor arg1, PrintWriter arg2, String[] arg3) {#dump-java.lang.String-java.io.FileDescriptor-java.io.PrintWriter-java.lang.String---}
```
public void dump(String arg0, FileDescriptor arg1, PrintWriter arg2, String[] arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | java.io.FileDescriptor |  |
| arg2 | java.io.PrintWriter |  |
| arg3 | java.lang.String[] |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getActivity() {#getActivity--}
```
public final FragmentActivity getActivity()
```




**Returns:**
androidx.fragment.app.FragmentActivity
### getAllowEnterTransitionOverlap() {#getAllowEnterTransitionOverlap--}
```
public boolean getAllowEnterTransitionOverlap()
```




**Returns:**
boolean
### getAllowReturnTransitionOverlap() {#getAllowReturnTransitionOverlap--}
```
public boolean getAllowReturnTransitionOverlap()
```




**Returns:**
boolean
### getArguments() {#getArguments--}
```
public final Bundle getArguments()
```




**Returns:**
android.os.Bundle
### getCallbackFragment() {#getCallbackFragment--}
```
public Fragment getCallbackFragment()
```




**Returns:**
androidx.fragment.app.Fragment
### getChildFragmentManager() {#getChildFragmentManager--}
```
public final FragmentManager getChildFragmentManager()
```




**Returns:**
androidx.fragment.app.FragmentManager
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContext() {#getContext--}
```
public Context getContext()
```




**Returns:**
android.content.Context
### getDefaultViewModelProviderFactory() {#getDefaultViewModelProviderFactory--}
```
public ViewModelProvider.Factory getDefaultViewModelProviderFactory()
```




**Returns:**
androidx.lifecycle.ViewModelProvider.Factory
### getEnterTransition() {#getEnterTransition--}
```
public Object getEnterTransition()
```




**Returns:**
java.lang.Object
### getExitTransition() {#getExitTransition--}
```
public Object getExitTransition()
```




**Returns:**
java.lang.Object
### getFragmentManager() {#getFragmentManager--}
```
public final FragmentManager getFragmentManager()
```




**Returns:**
androidx.fragment.app.FragmentManager
### getHost() {#getHost--}
```
public final Object getHost()
```




**Returns:**
java.lang.Object
### getId() {#getId--}
```
public final int getId()
```




**Returns:**
int
### getLayoutInflater() {#getLayoutInflater--}
```
public final LayoutInflater getLayoutInflater()
```




**Returns:**
android.view.LayoutInflater
### getLayoutInflater(Bundle arg0) {#getLayoutInflater-android.os.Bundle-}
```
public LayoutInflater getLayoutInflater(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

**Returns:**
android.view.LayoutInflater
### getLifecycle() {#getLifecycle--}
```
public Lifecycle getLifecycle()
```




**Returns:**
androidx.lifecycle.Lifecycle
### getListView() {#getListView--}
```
public final RecyclerView getListView()
```




**Returns:**
androidx.recyclerview.widget.RecyclerView
### getLoaderManager() {#getLoaderManager--}
```
public LoaderManager getLoaderManager()
```




**Returns:**
androidx.loader.app.LoaderManager
### getParentFragment() {#getParentFragment--}
```
public final Fragment getParentFragment()
```




**Returns:**
androidx.fragment.app.Fragment
### getParentFragmentManager() {#getParentFragmentManager--}
```
public final FragmentManager getParentFragmentManager()
```




**Returns:**
androidx.fragment.app.FragmentManager
### getPreferenceManager() {#getPreferenceManager--}
```
public PreferenceManager getPreferenceManager()
```




**Returns:**
androidx.preference.PreferenceManager
### getPreferenceScreen() {#getPreferenceScreen--}
```
public PreferenceScreen getPreferenceScreen()
```




**Returns:**
androidx.preference.PreferenceScreen
### getReenterTransition() {#getReenterTransition--}
```
public Object getReenterTransition()
```




**Returns:**
java.lang.Object
### getResources() {#getResources--}
```
public final Resources getResources()
```




**Returns:**
android.content.res.Resources
### getRetainInstance() {#getRetainInstance--}
```
public final boolean getRetainInstance()
```




**Returns:**
boolean
### getReturnTransition() {#getReturnTransition--}
```
public Object getReturnTransition()
```




**Returns:**
java.lang.Object
### getSavedStateRegistry() {#getSavedStateRegistry--}
```
public final SavedStateRegistry getSavedStateRegistry()
```




**Returns:**
androidx.savedstate.SavedStateRegistry
### getSharedElementEnterTransition() {#getSharedElementEnterTransition--}
```
public Object getSharedElementEnterTransition()
```




**Returns:**
java.lang.Object
### getSharedElementReturnTransition() {#getSharedElementReturnTransition--}
```
public Object getSharedElementReturnTransition()
```




**Returns:**
java.lang.Object
### getString(int arg0) {#getString-int-}
```
public final String getString(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.lang.String
### getString(int arg0, Object[] arg1) {#getString-int-java.lang.Object...-}
```
public final String getString(int arg0, Object[] arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.lang.Object[] |  |

**Returns:**
java.lang.String
### getTag() {#getTag--}
```
public final String getTag()
```




**Returns:**
java.lang.String
### getTargetFragment() {#getTargetFragment--}
```
public final Fragment getTargetFragment()
```




**Returns:**
androidx.fragment.app.Fragment
### getTargetRequestCode() {#getTargetRequestCode--}
```
public final int getTargetRequestCode()
```




**Returns:**
int
### getText(int arg0) {#getText-int-}
```
public final CharSequence getText(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.lang.CharSequence
### getUserVisibleHint() {#getUserVisibleHint--}
```
public boolean getUserVisibleHint()
```




**Returns:**
boolean
### getView() {#getView--}
```
public View getView()
```




**Returns:**
android.view.View
### getViewLifecycleOwner() {#getViewLifecycleOwner--}
```
public LifecycleOwner getViewLifecycleOwner()
```




**Returns:**
androidx.lifecycle.LifecycleOwner
### getViewLifecycleOwnerLiveData() {#getViewLifecycleOwnerLiveData--}
```
public LiveData<LifecycleOwner> getViewLifecycleOwnerLiveData()
```




**Returns:**
androidx.lifecycle.LiveData<androidx.lifecycle.LifecycleOwner>
### getViewModelStore() {#getViewModelStore--}
```
public ViewModelStore getViewModelStore()
```




**Returns:**
androidx.lifecycle.ViewModelStore
### hasOptionsMenu() {#hasOptionsMenu--}
```
public final boolean hasOptionsMenu()
```




**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### instantiate(Context arg0, String arg1) {#instantiate-android.content.Context-java.lang.String-}
```
public static Fragment instantiate(Context arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | java.lang.String |  |

**Returns:**
androidx.fragment.app.Fragment
### instantiate(Context arg0, String arg1, Bundle arg2) {#instantiate-android.content.Context-java.lang.String-android.os.Bundle-}
```
public static Fragment instantiate(Context arg0, String arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | java.lang.String |  |
| arg2 | android.os.Bundle |  |

**Returns:**
androidx.fragment.app.Fragment
### isAdded() {#isAdded--}
```
public final boolean isAdded()
```




**Returns:**
boolean
### isDetached() {#isDetached--}
```
public final boolean isDetached()
```




**Returns:**
boolean
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```




**Returns:**
boolean
### isInLayout() {#isInLayout--}
```
public final boolean isInLayout()
```




**Returns:**
boolean
### isMenuVisible() {#isMenuVisible--}
```
public final boolean isMenuVisible()
```




**Returns:**
boolean
### isRemoving() {#isRemoving--}
```
public final boolean isRemoving()
```




**Returns:**
boolean
### isResumed() {#isResumed--}
```
public final boolean isResumed()
```




**Returns:**
boolean
### isStateSaved() {#isStateSaved--}
```
public final boolean isStateSaved()
```




**Returns:**
boolean
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```




**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onActivityCreated(Bundle arg0) {#onActivityCreated-android.os.Bundle-}
```
public void onActivityCreated(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

### onActivityResult(int arg0, int arg1, Intent arg2) {#onActivityResult-int-int-android.content.Intent-}
```
public void onActivityResult(int arg0, int arg1, Intent arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | android.content.Intent |  |

### onAttach(Activity arg0) {#onAttach-android.app.Activity-}
```
public void onAttach(Activity arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |

### onAttach(Context arg0) {#onAttach-android.content.Context-}
```
public void onAttach(Context arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Context |  |

### onAttachFragment(Fragment arg0) {#onAttachFragment-androidx.fragment.app.Fragment-}
```
public void onAttachFragment(Fragment arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment |  |

### onConfigurationChanged(Configuration arg0) {#onConfigurationChanged-android.content.res.Configuration-}
```
public void onConfigurationChanged(Configuration arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.res.Configuration |  |

### onContextItemSelected(MenuItem arg0) {#onContextItemSelected-android.view.MenuItem-}
```
public boolean onContextItemSelected(MenuItem arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MenuItem |  |

**Returns:**
boolean
### onCreate(Bundle savedInstanceState) {#onCreate-android.os.Bundle-}
```
public final void onCreate(Bundle savedInstanceState)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| savedInstanceState | android.os.Bundle |  |

### onCreateAnimation(int arg0, boolean arg1, int arg2) {#onCreateAnimation-int-boolean-int-}
```
public Animation onCreateAnimation(int arg0, boolean arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | boolean |  |
| arg2 | int |  |

**Returns:**
android.view.animation.Animation
### onCreateAnimator(int arg0, boolean arg1, int arg2) {#onCreateAnimator-int-boolean-int-}
```
public Animator onCreateAnimator(int arg0, boolean arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | boolean |  |
| arg2 | int |  |

**Returns:**
android.animation.Animator
### onCreateContextMenu(ContextMenu arg0, View arg1, ContextMenu.ContextMenuInfo arg2) {#onCreateContextMenu-android.view.ContextMenu-android.view.View-android.view.ContextMenu.ContextMenuInfo-}
```
public void onCreateContextMenu(ContextMenu arg0, View arg1, ContextMenu.ContextMenuInfo arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ContextMenu |  |
| arg1 | android.view.View |  |
| arg2 | android.view.ContextMenu.ContextMenuInfo |  |

### onCreateLayoutManager() {#onCreateLayoutManager--}
```
public RecyclerView.LayoutManager onCreateLayoutManager()
```




**Returns:**
androidx.recyclerview.widget.RecyclerView.LayoutManager
### onCreateOptionsMenu(Menu arg0, MenuInflater arg1) {#onCreateOptionsMenu-android.view.Menu-android.view.MenuInflater-}
```
public void onCreateOptionsMenu(Menu arg0, MenuInflater arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Menu |  |
| arg1 | android.view.MenuInflater |  |

### onCreatePreferences(Bundle arg0, String arg1) {#onCreatePreferences-android.os.Bundle-java.lang.String-}
```
public abstract void onCreatePreferences(Bundle arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |
| arg1 | java.lang.String |  |

### onCreateRecyclerView(LayoutInflater arg0, ViewGroup arg1, Bundle arg2) {#onCreateRecyclerView-android.view.LayoutInflater-android.view.ViewGroup-android.os.Bundle-}
```
public RecyclerView onCreateRecyclerView(LayoutInflater arg0, ViewGroup arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.LayoutInflater |  |
| arg1 | android.view.ViewGroup |  |
| arg2 | android.os.Bundle |  |

**Returns:**
androidx.recyclerview.widget.RecyclerView
### onCreateView(LayoutInflater arg0, ViewGroup arg1, Bundle arg2) {#onCreateView-android.view.LayoutInflater-android.view.ViewGroup-android.os.Bundle-}
```
public View onCreateView(LayoutInflater arg0, ViewGroup arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.LayoutInflater |  |
| arg1 | android.view.ViewGroup |  |
| arg2 | android.os.Bundle |  |

**Returns:**
android.view.View
### onDestroy() {#onDestroy--}
```
public void onDestroy()
```




### onDestroyOptionsMenu() {#onDestroyOptionsMenu--}
```
public void onDestroyOptionsMenu()
```




### onDestroyView() {#onDestroyView--}
```
public void onDestroyView()
```




### onDetach() {#onDetach--}
```
public void onDetach()
```




### onDisplayPreferenceDialog(Preference arg0) {#onDisplayPreferenceDialog-androidx.preference.Preference-}
```
public void onDisplayPreferenceDialog(Preference arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.preference.Preference |  |

### onGetLayoutInflater(Bundle arg0) {#onGetLayoutInflater-android.os.Bundle-}
```
public LayoutInflater onGetLayoutInflater(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

**Returns:**
android.view.LayoutInflater
### onHiddenChanged(boolean arg0) {#onHiddenChanged-boolean-}
```
public void onHiddenChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onInflate(Activity arg0, AttributeSet arg1, Bundle arg2) {#onInflate-android.app.Activity-android.util.AttributeSet-android.os.Bundle-}
```
public void onInflate(Activity arg0, AttributeSet arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | android.util.AttributeSet |  |
| arg2 | android.os.Bundle |  |

### onInflate(Context arg0, AttributeSet arg1, Bundle arg2) {#onInflate-android.content.Context-android.util.AttributeSet-android.os.Bundle-}
```
public void onInflate(Context arg0, AttributeSet arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | android.util.AttributeSet |  |
| arg2 | android.os.Bundle |  |

### onLowMemory() {#onLowMemory--}
```
public void onLowMemory()
```




### onMultiWindowModeChanged(boolean arg0) {#onMultiWindowModeChanged-boolean-}
```
public void onMultiWindowModeChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onNavigateToScreen(PreferenceScreen arg0) {#onNavigateToScreen-androidx.preference.PreferenceScreen-}
```
public void onNavigateToScreen(PreferenceScreen arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.preference.PreferenceScreen |  |

### onOptionsItemSelected(MenuItem arg0) {#onOptionsItemSelected-android.view.MenuItem-}
```
public boolean onOptionsItemSelected(MenuItem arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MenuItem |  |

**Returns:**
boolean
### onOptionsMenuClosed(Menu arg0) {#onOptionsMenuClosed-android.view.Menu-}
```
public void onOptionsMenuClosed(Menu arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Menu |  |

### onPause() {#onPause--}
```
public void onPause()
```




### onPictureInPictureModeChanged(boolean arg0) {#onPictureInPictureModeChanged-boolean-}
```
public void onPictureInPictureModeChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onPreferenceTreeClick(Preference arg0) {#onPreferenceTreeClick-androidx.preference.Preference-}
```
public boolean onPreferenceTreeClick(Preference arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.preference.Preference |  |

**Returns:**
boolean
### onPrepareOptionsMenu(Menu arg0) {#onPrepareOptionsMenu-android.view.Menu-}
```
public void onPrepareOptionsMenu(Menu arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Menu |  |

### onPrimaryNavigationFragmentChanged(boolean arg0) {#onPrimaryNavigationFragmentChanged-boolean-}
```
public void onPrimaryNavigationFragmentChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onRequestPermissionsResult(int arg0, String[] arg1, int[] arg2) {#onRequestPermissionsResult-int-java.lang.String---int---}
```
public void onRequestPermissionsResult(int arg0, String[] arg1, int[] arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.lang.String[] |  |
| arg2 | int[] |  |

### onResume() {#onResume--}
```
public void onResume()
```




### onSaveInstanceState(Bundle arg0) {#onSaveInstanceState-android.os.Bundle-}
```
public void onSaveInstanceState(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

### onStart() {#onStart--}
```
public void onStart()
```




### onStop() {#onStop--}
```
public void onStop()
```




### onViewCreated(View arg0, Bundle arg1) {#onViewCreated-android.view.View-android.os.Bundle-}
```
public void onViewCreated(View arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |
| arg1 | android.os.Bundle |  |

### onViewStateRestored(Bundle arg0) {#onViewStateRestored-android.os.Bundle-}
```
public void onViewStateRestored(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

### postponeEnterTransition() {#postponeEnterTransition--}
```
public void postponeEnterTransition()
```




### postponeEnterTransition(long arg0, TimeUnit arg1) {#postponeEnterTransition-long-java.util.concurrent.TimeUnit-}
```
public final void postponeEnterTransition(long arg0, TimeUnit arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | java.util.concurrent.TimeUnit |  |

### registerForContextMenu(View arg0) {#registerForContextMenu-android.view.View-}
```
public void registerForContextMenu(View arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |

### requestPermissions(String[] arg0, int arg1) {#requestPermissions-java.lang.String---int-}
```
public final void requestPermissions(String[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String[] |  |
| arg1 | int |  |

### requireActivity() {#requireActivity--}
```
public final FragmentActivity requireActivity()
```




**Returns:**
androidx.fragment.app.FragmentActivity
### requireArguments() {#requireArguments--}
```
public final Bundle requireArguments()
```




**Returns:**
android.os.Bundle
### requireContext() {#requireContext--}
```
public final Context requireContext()
```




**Returns:**
android.content.Context
### requireFragmentManager() {#requireFragmentManager--}
```
public final FragmentManager requireFragmentManager()
```




**Returns:**
androidx.fragment.app.FragmentManager
### requireHost() {#requireHost--}
```
public final Object requireHost()
```




**Returns:**
java.lang.Object
### requireParentFragment() {#requireParentFragment--}
```
public final Fragment requireParentFragment()
```




**Returns:**
androidx.fragment.app.Fragment
### requireView() {#requireView--}
```
public final View requireView()
```




**Returns:**
android.view.View
### scrollToPreference(Preference arg0) {#scrollToPreference-androidx.preference.Preference-}
```
public void scrollToPreference(Preference arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.preference.Preference |  |

### scrollToPreference(String arg0) {#scrollToPreference-java.lang.String-}
```
public void scrollToPreference(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### setAllowEnterTransitionOverlap(boolean arg0) {#setAllowEnterTransitionOverlap-boolean-}
```
public void setAllowEnterTransitionOverlap(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setAllowReturnTransitionOverlap(boolean arg0) {#setAllowReturnTransitionOverlap-boolean-}
```
public void setAllowReturnTransitionOverlap(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setArguments(Bundle arg0) {#setArguments-android.os.Bundle-}
```
public void setArguments(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

### setDivider(Drawable arg0) {#setDivider-android.graphics.drawable.Drawable-}
```
public void setDivider(Drawable arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.graphics.drawable.Drawable |  |

### setDividerHeight(int arg0) {#setDividerHeight-int-}
```
public void setDividerHeight(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setEnterSharedElementCallback(SharedElementCallback arg0) {#setEnterSharedElementCallback-androidx.core.app.SharedElementCallback-}
```
public void setEnterSharedElementCallback(SharedElementCallback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.SharedElementCallback |  |

### setEnterTransition(Object arg0) {#setEnterTransition-java.lang.Object-}
```
public void setEnterTransition(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

### setExitSharedElementCallback(SharedElementCallback arg0) {#setExitSharedElementCallback-androidx.core.app.SharedElementCallback-}
```
public void setExitSharedElementCallback(SharedElementCallback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.SharedElementCallback |  |

### setExitTransition(Object arg0) {#setExitTransition-java.lang.Object-}
```
public void setExitTransition(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

### setHasOptionsMenu(boolean arg0) {#setHasOptionsMenu-boolean-}
```
public void setHasOptionsMenu(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setInitialSavedState(Fragment.SavedState arg0) {#setInitialSavedState-androidx.fragment.app.Fragment.SavedState-}
```
public void setInitialSavedState(Fragment.SavedState arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment.SavedState |  |

### setMenuVisibility(boolean arg0) {#setMenuVisibility-boolean-}
```
public void setMenuVisibility(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setPreferenceScreen(PreferenceScreen arg0) {#setPreferenceScreen-androidx.preference.PreferenceScreen-}
```
public void setPreferenceScreen(PreferenceScreen arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.preference.PreferenceScreen |  |

### setPreferencesFromResource(int arg0, String arg1) {#setPreferencesFromResource-int-java.lang.String-}
```
public void setPreferencesFromResource(int arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | java.lang.String |  |

### setReenterTransition(Object arg0) {#setReenterTransition-java.lang.Object-}
```
public void setReenterTransition(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

### setRetainInstance(boolean arg0) {#setRetainInstance-boolean-}
```
public void setRetainInstance(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setReturnTransition(Object arg0) {#setReturnTransition-java.lang.Object-}
```
public void setReturnTransition(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

### setSharedElementEnterTransition(Object arg0) {#setSharedElementEnterTransition-java.lang.Object-}
```
public void setSharedElementEnterTransition(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

### setSharedElementReturnTransition(Object arg0) {#setSharedElementReturnTransition-java.lang.Object-}
```
public void setSharedElementReturnTransition(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

### setTargetFragment(Fragment arg0, int arg1) {#setTargetFragment-androidx.fragment.app.Fragment-int-}
```
public void setTargetFragment(Fragment arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment |  |
| arg1 | int |  |

### setUserVisibleHint(boolean arg0) {#setUserVisibleHint-boolean-}
```
public void setUserVisibleHint(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### shouldShowRequestPermissionRationale(String arg0) {#shouldShowRequestPermissionRationale-java.lang.String-}
```
public boolean shouldShowRequestPermissionRationale(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
boolean
### startActivity(Intent arg0) {#startActivity-android.content.Intent-}
```
public void startActivity(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

### startActivity(Intent arg0, Bundle arg1) {#startActivity-android.content.Intent-android.os.Bundle-}
```
public void startActivity(Intent arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.Bundle |  |

### startActivityForResult(Intent arg0, int arg1) {#startActivityForResult-android.content.Intent-int-}
```
public void startActivityForResult(Intent arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |

### startActivityForResult(Intent arg0, int arg1, Bundle arg2) {#startActivityForResult-android.content.Intent-int-android.os.Bundle-}
```
public void startActivityForResult(Intent arg0, int arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |
| arg2 | android.os.Bundle |  |

### startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5, Bundle arg6) {#startIntentSenderForResult-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-}
```
public void startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5, Bundle arg6)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.IntentSender |  |
| arg1 | int |  |
| arg2 | android.content.Intent |  |
| arg3 | int |  |
| arg4 | int |  |
| arg5 | int |  |
| arg6 | android.os.Bundle |  |

### startPostponedEnterTransition() {#startPostponedEnterTransition--}
```
public void startPostponedEnterTransition()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterForContextMenu(View arg0) {#unregisterForContextMenu-android.view.View-}
```
public void unregisterForContextMenu(View arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

