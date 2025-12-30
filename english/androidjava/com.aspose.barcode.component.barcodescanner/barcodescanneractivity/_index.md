---
title: BarcodeScannerActivity
second_title: Aspose.BarCode for Android via Java API Reference
description: Activity that contains BarcodeScannerFragment It is internal class and client should not call this class but client should register BarcodeScannerActivity in AndroidManifest.xml
type: docs
weight: 13
url: /androidjava/com.aspose.barcode.component.barcodescanner/barcodescanneractivity/
---
**Inheritance:**
java.lang.Object, android.content.Context, android.content.ContextWrapper, android.view.ContextThemeWrapper, android.app.Activity, androidx.core.app.ComponentActivity, androidx.activity.ComponentActivity, androidx.fragment.app.FragmentActivity, androidx.appcompat.app.AppCompatActivity
```
public class BarcodeScannerActivity extends AppCompatActivity
```

Activity that contains BarcodeScannerFragment It is internal class and client should not call this class, but client should register BarcodeScannerActivity in AndroidManifest.xml
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeScannerActivity()](#BarcodeScannerActivity--) |  |
## Fields

| Field | Description |
| --- | --- |
| [ACCESSIBILITY_SERVICE](#ACCESSIBILITY-SERVICE) |  |
| [ACCOUNT_SERVICE](#ACCOUNT-SERVICE) |  |
| [ACTIVITY_SERVICE](#ACTIVITY-SERVICE) |  |
| [ALARM_SERVICE](#ALARM-SERVICE) |  |
| [APPWIDGET_SERVICE](#APPWIDGET-SERVICE) |  |
| [APP_OPS_SERVICE](#APP-OPS-SERVICE) |  |
| [APP_SEARCH_SERVICE](#APP-SEARCH-SERVICE) |  |
| [AUDIO_SERVICE](#AUDIO-SERVICE) |  |
| [BATTERY_SERVICE](#BATTERY-SERVICE) |  |
| [BIND_ABOVE_CLIENT](#BIND-ABOVE-CLIENT) |  |
| [BIND_ADJUST_WITH_ACTIVITY](#BIND-ADJUST-WITH-ACTIVITY) |  |
| [BIND_ALLOW_OOM_MANAGEMENT](#BIND-ALLOW-OOM-MANAGEMENT) |  |
| [BIND_AUTO_CREATE](#BIND-AUTO-CREATE) |  |
| [BIND_DEBUG_UNBIND](#BIND-DEBUG-UNBIND) |  |
| [BIND_EXTERNAL_SERVICE](#BIND-EXTERNAL-SERVICE) |  |
| [BIND_IMPORTANT](#BIND-IMPORTANT) |  |
| [BIND_INCLUDE_CAPABILITIES](#BIND-INCLUDE-CAPABILITIES) |  |
| [BIND_NOT_FOREGROUND](#BIND-NOT-FOREGROUND) |  |
| [BIND_NOT_PERCEPTIBLE](#BIND-NOT-PERCEPTIBLE) |  |
| [BIND_WAIVE_PRIORITY](#BIND-WAIVE-PRIORITY) |  |
| [BIOMETRIC_SERVICE](#BIOMETRIC-SERVICE) |  |
| [BLOB_STORE_SERVICE](#BLOB-STORE-SERVICE) |  |
| [BLUETOOTH_SERVICE](#BLUETOOTH-SERVICE) |  |
| [BUGREPORT_SERVICE](#BUGREPORT-SERVICE) |  |
| [CAMERA_SERVICE](#CAMERA-SERVICE) |  |
| [CAPTIONING_SERVICE](#CAPTIONING-SERVICE) |  |
| [CARRIER_CONFIG_SERVICE](#CARRIER-CONFIG-SERVICE) |  |
| [CLIPBOARD_SERVICE](#CLIPBOARD-SERVICE) |  |
| [COMPANION_DEVICE_SERVICE](#COMPANION-DEVICE-SERVICE) |  |
| [CONNECTIVITY_DIAGNOSTICS_SERVICE](#CONNECTIVITY-DIAGNOSTICS-SERVICE) |  |
| [CONNECTIVITY_SERVICE](#CONNECTIVITY-SERVICE) |  |
| [CONSUMER_IR_SERVICE](#CONSUMER-IR-SERVICE) |  |
| [CONTEXT_IGNORE_SECURITY](#CONTEXT-IGNORE-SECURITY) |  |
| [CONTEXT_INCLUDE_CODE](#CONTEXT-INCLUDE-CODE) |  |
| [CONTEXT_RESTRICTED](#CONTEXT-RESTRICTED) |  |
| [CROSS_PROFILE_APPS_SERVICE](#CROSS-PROFILE-APPS-SERVICE) |  |
| [DEFAULT_KEYS_DIALER](#DEFAULT-KEYS-DIALER) |  |
| [DEFAULT_KEYS_DISABLE](#DEFAULT-KEYS-DISABLE) |  |
| [DEFAULT_KEYS_SEARCH_GLOBAL](#DEFAULT-KEYS-SEARCH-GLOBAL) |  |
| [DEFAULT_KEYS_SEARCH_LOCAL](#DEFAULT-KEYS-SEARCH-LOCAL) |  |
| [DEFAULT_KEYS_SHORTCUT](#DEFAULT-KEYS-SHORTCUT) |  |
| [DEVICE_POLICY_SERVICE](#DEVICE-POLICY-SERVICE) |  |
| [DISPLAY_HASH_SERVICE](#DISPLAY-HASH-SERVICE) |  |
| [DISPLAY_SERVICE](#DISPLAY-SERVICE) |  |
| [DOMAIN_VERIFICATION_SERVICE](#DOMAIN-VERIFICATION-SERVICE) |  |
| [DOWNLOAD_SERVICE](#DOWNLOAD-SERVICE) |  |
| [DROPBOX_SERVICE](#DROPBOX-SERVICE) |  |
| [EUICC_SERVICE](#EUICC-SERVICE) |  |
| [FILE_INTEGRITY_SERVICE](#FILE-INTEGRITY-SERVICE) |  |
| [FINGERPRINT_SERVICE](#FINGERPRINT-SERVICE) |  |
| [GAME_SERVICE](#GAME-SERVICE) |  |
| [HARDWARE_PROPERTIES_SERVICE](#HARDWARE-PROPERTIES-SERVICE) |  |
| [INPUT_METHOD_SERVICE](#INPUT-METHOD-SERVICE) |  |
| [INPUT_SERVICE](#INPUT-SERVICE) |  |
| [IPSEC_SERVICE](#IPSEC-SERVICE) |  |
| [JOB_SCHEDULER_SERVICE](#JOB-SCHEDULER-SERVICE) |  |
| [KEYGUARD_SERVICE](#KEYGUARD-SERVICE) |  |
| [LAUNCHER_APPS_SERVICE](#LAUNCHER-APPS-SERVICE) |  |
| [LAYOUT_INFLATER_SERVICE](#LAYOUT-INFLATER-SERVICE) |  |
| [LOCALE_SERVICE](#LOCALE-SERVICE) |  |
| [LOCATION_SERVICE](#LOCATION-SERVICE) |  |
| [MEDIA_COMMUNICATION_SERVICE](#MEDIA-COMMUNICATION-SERVICE) |  |
| [MEDIA_METRICS_SERVICE](#MEDIA-METRICS-SERVICE) |  |
| [MEDIA_PROJECTION_SERVICE](#MEDIA-PROJECTION-SERVICE) |  |
| [MEDIA_ROUTER_SERVICE](#MEDIA-ROUTER-SERVICE) |  |
| [MEDIA_SESSION_SERVICE](#MEDIA-SESSION-SERVICE) |  |
| [MIDI_SERVICE](#MIDI-SERVICE) |  |
| [MODE_APPEND](#MODE-APPEND) |  |
| [MODE_ENABLE_WRITE_AHEAD_LOGGING](#MODE-ENABLE-WRITE-AHEAD-LOGGING) |  |
| [MODE_MULTI_PROCESS](#MODE-MULTI-PROCESS) |  |
| [MODE_NO_LOCALIZED_COLLATORS](#MODE-NO-LOCALIZED-COLLATORS) |  |
| [MODE_PRIVATE](#MODE-PRIVATE) |  |
| [MODE_WORLD_READABLE](#MODE-WORLD-READABLE) |  |
| [MODE_WORLD_WRITEABLE](#MODE-WORLD-WRITEABLE) |  |
| [NETWORK_STATS_SERVICE](#NETWORK-STATS-SERVICE) |  |
| [NFC_SERVICE](#NFC-SERVICE) |  |
| [NOTIFICATION_SERVICE](#NOTIFICATION-SERVICE) |  |
| [NSD_SERVICE](#NSD-SERVICE) |  |
| [PEOPLE_SERVICE](#PEOPLE-SERVICE) |  |
| [PERFORMANCE_HINT_SERVICE](#PERFORMANCE-HINT-SERVICE) |  |
| [POWER_SERVICE](#POWER-SERVICE) |  |
| [PRINT_SERVICE](#PRINT-SERVICE) |  |
| [RECEIVER_EXPORTED](#RECEIVER-EXPORTED) |  |
| [RECEIVER_NOT_EXPORTED](#RECEIVER-NOT-EXPORTED) |  |
| [RECEIVER_VISIBLE_TO_INSTANT_APPS](#RECEIVER-VISIBLE-TO-INSTANT-APPS) |  |
| [RESTRICTIONS_SERVICE](#RESTRICTIONS-SERVICE) |  |
| [RESULT_CANCELED](#RESULT-CANCELED) |  |
| [RESULT_FIRST_USER](#RESULT-FIRST-USER) |  |
| [RESULT_OK](#RESULT-OK) |  |
| [ROLE_SERVICE](#ROLE-SERVICE) |  |
| [SEARCH_SERVICE](#SEARCH-SERVICE) |  |
| [SENSOR_SERVICE](#SENSOR-SERVICE) |  |
| [SHORTCUT_SERVICE](#SHORTCUT-SERVICE) |  |
| [STATUS_BAR_SERVICE](#STATUS-BAR-SERVICE) |  |
| [STORAGE_SERVICE](#STORAGE-SERVICE) |  |
| [STORAGE_STATS_SERVICE](#STORAGE-STATS-SERVICE) |  |
| [SYSTEM_HEALTH_SERVICE](#SYSTEM-HEALTH-SERVICE) |  |
| [TELECOM_SERVICE](#TELECOM-SERVICE) |  |
| [TELEPHONY_IMS_SERVICE](#TELEPHONY-IMS-SERVICE) |  |
| [TELEPHONY_SERVICE](#TELEPHONY-SERVICE) |  |
| [TELEPHONY_SUBSCRIPTION_SERVICE](#TELEPHONY-SUBSCRIPTION-SERVICE) |  |
| [TEXT_CLASSIFICATION_SERVICE](#TEXT-CLASSIFICATION-SERVICE) |  |
| [TEXT_SERVICES_MANAGER_SERVICE](#TEXT-SERVICES-MANAGER-SERVICE) |  |
| [TV_INPUT_SERVICE](#TV-INPUT-SERVICE) |  |
| [TV_INTERACTIVE_APP_SERVICE](#TV-INTERACTIVE-APP-SERVICE) |  |
| [UI_MODE_SERVICE](#UI-MODE-SERVICE) |  |
| [USAGE_STATS_SERVICE](#USAGE-STATS-SERVICE) |  |
| [USB_SERVICE](#USB-SERVICE) |  |
| [USER_SERVICE](#USER-SERVICE) |  |
| [VIBRATOR_MANAGER_SERVICE](#VIBRATOR-MANAGER-SERVICE) |  |
| [VIBRATOR_SERVICE](#VIBRATOR-SERVICE) |  |
| [VPN_MANAGEMENT_SERVICE](#VPN-MANAGEMENT-SERVICE) |  |
| [WALLPAPER_SERVICE](#WALLPAPER-SERVICE) |  |
| [WIFI_AWARE_SERVICE](#WIFI-AWARE-SERVICE) |  |
| [WIFI_P2P_SERVICE](#WIFI-P2P-SERVICE) |  |
| [WIFI_RTT_RANGING_SERVICE](#WIFI-RTT-RANGING-SERVICE) |  |
| [WIFI_SERVICE](#WIFI-SERVICE) |  |
| [WINDOW_SERVICE](#WINDOW-SERVICE) |  |
## Methods

| Method | Description |
| --- | --- |
| [<I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultCallback<O> arg1)](#-I-O-registerForActivityResult-androidx.activity.result.contract.ActivityResultContract-I-O--androidx.activity.result.ActivityResultCallback-O--) |  |
| [<I,O>registerForActivityResult(ActivityResultContract<I,O> arg0, ActivityResultRegistry arg1, ActivityResultCallback<O> arg2)](#-I-O-registerForActivityResult-androidx.activity.result.contract.ActivityResultContract-I-O--androidx.activity.result.ActivityResultRegistry-androidx.activity.result.ActivityResultCallback-O--) |  |
| [<T>findViewById(int arg0)](#-T-findViewById-int-) |  |
| [<T>getExtraData(Class<T> arg0)](#-T-getExtraData-java.lang.Class-T--) |  |
| [<T>getSystemService(Class<T> arg0)](#-T-getSystemService-java.lang.Class-T--) |  |
| [<T>requireViewById(int arg0)](#-T-requireViewById-int-) |  |
| [addContentView(View arg0, ViewGroup.LayoutParams arg1)](#addContentView-android.view.View-android.view.ViewGroup.LayoutParams-) |  |
| [addMenuProvider(MenuProvider arg0)](#addMenuProvider-androidx.core.view.MenuProvider-) |  |
| [addMenuProvider(MenuProvider arg0, LifecycleOwner arg1)](#addMenuProvider-androidx.core.view.MenuProvider-androidx.lifecycle.LifecycleOwner-) |  |
| [addMenuProvider(MenuProvider arg0, LifecycleOwner arg1, Lifecycle.State arg2)](#addMenuProvider-androidx.core.view.MenuProvider-androidx.lifecycle.LifecycleOwner-androidx.lifecycle.Lifecycle.State-) |  |
| [addOnConfigurationChangedListener(Consumer<Configuration> arg0)](#addOnConfigurationChangedListener-androidx.core.util.Consumer-android.content.res.Configuration--) |  |
| [addOnContextAvailableListener(OnContextAvailableListener arg0)](#addOnContextAvailableListener-androidx.activity.contextaware.OnContextAvailableListener-) |  |
| [addOnMultiWindowModeChangedListener(Consumer<MultiWindowModeChangedInfo> arg0)](#addOnMultiWindowModeChangedListener-androidx.core.util.Consumer-androidx.core.app.MultiWindowModeChangedInfo--) |  |
| [addOnNewIntentListener(Consumer<Intent> arg0)](#addOnNewIntentListener-androidx.core.util.Consumer-android.content.Intent--) |  |
| [addOnPictureInPictureModeChangedListener(Consumer<PictureInPictureModeChangedInfo> arg0)](#addOnPictureInPictureModeChangedListener-androidx.core.util.Consumer-androidx.core.app.PictureInPictureModeChangedInfo--) |  |
| [addOnTrimMemoryListener(Consumer<Integer> arg0)](#addOnTrimMemoryListener-androidx.core.util.Consumer-java.lang.Integer--) |  |
| [applyOverrideConfiguration(Configuration arg0)](#applyOverrideConfiguration-android.content.res.Configuration-) |  |
| [bindIsolatedService(Intent arg0, int arg1, String arg2, Executor arg3, ServiceConnection arg4)](#bindIsolatedService-android.content.Intent-int-java.lang.String-java.util.concurrent.Executor-android.content.ServiceConnection-) |  |
| [bindService(Intent arg0, ServiceConnection arg1, int arg2)](#bindService-android.content.Intent-android.content.ServiceConnection-int-) |  |
| [bindService(Intent arg0, int arg1, Executor arg2, ServiceConnection arg3)](#bindService-android.content.Intent-int-java.util.concurrent.Executor-android.content.ServiceConnection-) |  |
| [bindServiceAsUser(Intent arg0, ServiceConnection arg1, int arg2, UserHandle arg3)](#bindServiceAsUser-android.content.Intent-android.content.ServiceConnection-int-android.os.UserHandle-) |  |
| [checkCallingOrSelfPermission(String arg0)](#checkCallingOrSelfPermission-java.lang.String-) |  |
| [checkCallingOrSelfUriPermission(Uri arg0, int arg1)](#checkCallingOrSelfUriPermission-android.net.Uri-int-) |  |
| [checkCallingOrSelfUriPermissions(List<Uri> arg0, int arg1)](#checkCallingOrSelfUriPermissions-java.util.List-android.net.Uri--int-) |  |
| [checkCallingPermission(String arg0)](#checkCallingPermission-java.lang.String-) |  |
| [checkCallingUriPermission(Uri arg0, int arg1)](#checkCallingUriPermission-android.net.Uri-int-) |  |
| [checkCallingUriPermissions(List<Uri> arg0, int arg1)](#checkCallingUriPermissions-java.util.List-android.net.Uri--int-) |  |
| [checkPermission(String arg0, int arg1, int arg2)](#checkPermission-java.lang.String-int-int-) |  |
| [checkSelfPermission(String arg0)](#checkSelfPermission-java.lang.String-) |  |
| [checkUriPermission(Uri arg0, int arg1, int arg2, int arg3)](#checkUriPermission-android.net.Uri-int-int-int-) |  |
| [checkUriPermission(Uri arg0, String arg1, String arg2, int arg3, int arg4, int arg5)](#checkUriPermission-android.net.Uri-java.lang.String-java.lang.String-int-int-int-) |  |
| [checkUriPermissions(List<Uri> arg0, int arg1, int arg2, int arg3)](#checkUriPermissions-java.util.List-android.net.Uri--int-int-int-) |  |
| [clearWallpaper()](#clearWallpaper--) |  |
| [closeContextMenu()](#closeContextMenu--) |  |
| [closeOptionsMenu()](#closeOptionsMenu--) |  |
| [createAttributionContext(String arg0)](#createAttributionContext-java.lang.String-) |  |
| [createConfigurationContext(Configuration arg0)](#createConfigurationContext-android.content.res.Configuration-) |  |
| [createContext(ContextParams arg0)](#createContext-android.content.ContextParams-) |  |
| [createContextForSplit(String arg0)](#createContextForSplit-java.lang.String-) |  |
| [createDeviceProtectedStorageContext()](#createDeviceProtectedStorageContext--) |  |
| [createDisplayContext(Display arg0)](#createDisplayContext-android.view.Display-) |  |
| [createPackageContext(String arg0, int arg1)](#createPackageContext-java.lang.String-int-) |  |
| [createPendingResult(int arg0, Intent arg1, int arg2)](#createPendingResult-int-android.content.Intent-int-) |  |
| [createWindowContext(Display arg0, int arg1, Bundle arg2)](#createWindowContext-android.view.Display-int-android.os.Bundle-) |  |
| [createWindowContext(int arg0, Bundle arg1)](#createWindowContext-int-android.os.Bundle-) |  |
| [databaseList()](#databaseList--) |  |
| [deleteDatabase(String arg0)](#deleteDatabase-java.lang.String-) |  |
| [deleteFile(String arg0)](#deleteFile-java.lang.String-) |  |
| [deleteSharedPreferences(String arg0)](#deleteSharedPreferences-java.lang.String-) |  |
| [dismissDialog(int arg0)](#dismissDialog-int-) |  |
| [dismissKeyboardShortcutsHelper()](#dismissKeyboardShortcutsHelper--) |  |
| [dispatchGenericMotionEvent(MotionEvent arg0)](#dispatchGenericMotionEvent-android.view.MotionEvent-) |  |
| [dispatchKeyEvent(KeyEvent arg0)](#dispatchKeyEvent-android.view.KeyEvent-) |  |
| [dispatchKeyShortcutEvent(KeyEvent arg0)](#dispatchKeyShortcutEvent-android.view.KeyEvent-) |  |
| [dispatchPopulateAccessibilityEvent(AccessibilityEvent arg0)](#dispatchPopulateAccessibilityEvent-android.view.accessibility.AccessibilityEvent-) |  |
| [dispatchTouchEvent(MotionEvent arg0)](#dispatchTouchEvent-android.view.MotionEvent-) |  |
| [dispatchTrackballEvent(MotionEvent arg0)](#dispatchTrackballEvent-android.view.MotionEvent-) |  |
| [dump(String arg0, FileDescriptor arg1, PrintWriter arg2, String[] arg3)](#dump-java.lang.String-java.io.FileDescriptor-java.io.PrintWriter-java.lang.String---) |  |
| [enforceCallingOrSelfPermission(String arg0, String arg1)](#enforceCallingOrSelfPermission-java.lang.String-java.lang.String-) |  |
| [enforceCallingOrSelfUriPermission(Uri arg0, int arg1, String arg2)](#enforceCallingOrSelfUriPermission-android.net.Uri-int-java.lang.String-) |  |
| [enforceCallingPermission(String arg0, String arg1)](#enforceCallingPermission-java.lang.String-java.lang.String-) |  |
| [enforceCallingUriPermission(Uri arg0, int arg1, String arg2)](#enforceCallingUriPermission-android.net.Uri-int-java.lang.String-) |  |
| [enforcePermission(String arg0, int arg1, int arg2, String arg3)](#enforcePermission-java.lang.String-int-int-java.lang.String-) |  |
| [enforceUriPermission(Uri arg0, int arg1, int arg2, int arg3, String arg4)](#enforceUriPermission-android.net.Uri-int-int-int-java.lang.String-) |  |
| [enforceUriPermission(Uri arg0, String arg1, String arg2, int arg3, int arg4, int arg5, String arg6)](#enforceUriPermission-android.net.Uri-java.lang.String-java.lang.String-int-int-int-java.lang.String-) |  |
| [enterPictureInPictureMode()](#enterPictureInPictureMode--) |  |
| [enterPictureInPictureMode(PictureInPictureParams arg0)](#enterPictureInPictureMode-android.app.PictureInPictureParams-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fileList()](#fileList--) |  |
| [finish()](#finish--) |  |
| [finishActivity(int arg0)](#finishActivity-int-) |  |
| [finishActivityFromChild(Activity arg0, int arg1)](#finishActivityFromChild-android.app.Activity-int-) |  |
| [finishAffinity()](#finishAffinity--) |  |
| [finishAfterTransition()](#finishAfterTransition--) |  |
| [finishAndRemoveTask()](#finishAndRemoveTask--) |  |
| [finishFromChild(Activity arg0)](#finishFromChild-android.app.Activity-) |  |
| [getActionBar()](#getActionBar--) |  |
| [getActivityResultRegistry()](#getActivityResultRegistry--) |  |
| [getApplication()](#getApplication--) |  |
| [getApplicationContext()](#getApplicationContext--) |  |
| [getApplicationInfo()](#getApplicationInfo--) |  |
| [getAssets()](#getAssets--) |  |
| [getAttributionSource()](#getAttributionSource--) |  |
| [getAttributionTag()](#getAttributionTag--) |  |
| [getBaseContext()](#getBaseContext--) |  |
| [getCacheDir()](#getCacheDir--) |  |
| [getCallingActivity()](#getCallingActivity--) |  |
| [getCallingPackage()](#getCallingPackage--) |  |
| [getChangingConfigurations()](#getChangingConfigurations--) |  |
| [getClass()](#getClass--) |  |
| [getClassLoader()](#getClassLoader--) |  |
| [getCodeCacheDir()](#getCodeCacheDir--) |  |
| [getColor(int arg0)](#getColor-int-) |  |
| [getColorStateList(int arg0)](#getColorStateList-int-) |  |
| [getComponentName()](#getComponentName--) |  |
| [getContentResolver()](#getContentResolver--) |  |
| [getContentScene()](#getContentScene--) |  |
| [getContentTransitionManager()](#getContentTransitionManager--) |  |
| [getCurrentFocus()](#getCurrentFocus--) |  |
| [getDataDir()](#getDataDir--) |  |
| [getDatabasePath(String arg0)](#getDatabasePath-java.lang.String-) |  |
| [getDefaultViewModelCreationExtras()](#getDefaultViewModelCreationExtras--) |  |
| [getDefaultViewModelProviderFactory()](#getDefaultViewModelProviderFactory--) |  |
| [getDelegate()](#getDelegate--) |  |
| [getDir(String arg0, int arg1)](#getDir-java.lang.String-int-) |  |
| [getDisplay()](#getDisplay--) |  |
| [getDrawable(int arg0)](#getDrawable-int-) |  |
| [getDrawerToggleDelegate()](#getDrawerToggleDelegate--) |  |
| [getExternalCacheDir()](#getExternalCacheDir--) |  |
| [getExternalCacheDirs()](#getExternalCacheDirs--) |  |
| [getExternalFilesDir(String arg0)](#getExternalFilesDir-java.lang.String-) |  |
| [getExternalFilesDirs(String arg0)](#getExternalFilesDirs-java.lang.String-) |  |
| [getExternalMediaDirs()](#getExternalMediaDirs--) |  |
| [getFileStreamPath(String arg0)](#getFileStreamPath-java.lang.String-) |  |
| [getFilesDir()](#getFilesDir--) |  |
| [getFragmentManager()](#getFragmentManager--) |  |
| [getIntent()](#getIntent--) |  |
| [getLastCustomNonConfigurationInstance()](#getLastCustomNonConfigurationInstance--) |  |
| [getLastNonConfigurationInstance()](#getLastNonConfigurationInstance--) |  |
| [getLayoutInflater()](#getLayoutInflater--) |  |
| [getLifecycle()](#getLifecycle--) |  |
| [getLoaderManager()](#getLoaderManager--) |  |
| [getLocalClassName()](#getLocalClassName--) |  |
| [getMainExecutor()](#getMainExecutor--) |  |
| [getMainLooper()](#getMainLooper--) |  |
| [getMaxNumPictureInPictureActions()](#getMaxNumPictureInPictureActions--) |  |
| [getMediaController()](#getMediaController--) |  |
| [getMenuInflater()](#getMenuInflater--) |  |
| [getNoBackupFilesDir()](#getNoBackupFilesDir--) |  |
| [getObbDir()](#getObbDir--) |  |
| [getObbDirs()](#getObbDirs--) |  |
| [getOnBackInvokedDispatcher()](#getOnBackInvokedDispatcher--) |  |
| [getOnBackPressedDispatcher()](#getOnBackPressedDispatcher--) |  |
| [getOpPackageName()](#getOpPackageName--) |  |
| [getPackageCodePath()](#getPackageCodePath--) |  |
| [getPackageManager()](#getPackageManager--) |  |
| [getPackageName()](#getPackageName--) |  |
| [getPackageResourcePath()](#getPackageResourcePath--) |  |
| [getParams()](#getParams--) |  |
| [getParent()](#getParent--) |  |
| [getParentActivityIntent()](#getParentActivityIntent--) |  |
| [getPreferences(int arg0)](#getPreferences-int-) |  |
| [getReferrer()](#getReferrer--) |  |
| [getRequestedOrientation()](#getRequestedOrientation--) |  |
| [getResources()](#getResources--) |  |
| [getSavedStateRegistry()](#getSavedStateRegistry--) |  |
| [getSearchEvent()](#getSearchEvent--) |  |
| [getSharedPreferences(String arg0, int arg1)](#getSharedPreferences-java.lang.String-int-) |  |
| [getSplashScreen()](#getSplashScreen--) |  |
| [getString(int arg0)](#getString-int-) |  |
| [getString(int arg0, Object[] arg1)](#getString-int-java.lang.Object...-) |  |
| [getSupportActionBar()](#getSupportActionBar--) |  |
| [getSupportFragmentManager()](#getSupportFragmentManager--) |  |
| [getSupportLoaderManager()](#getSupportLoaderManager--) |  |
| [getSupportParentActivityIntent()](#getSupportParentActivityIntent--) |  |
| [getSystemService(String arg0)](#getSystemService-java.lang.String-) |  |
| [getSystemServiceName(Class<?> arg0)](#getSystemServiceName-java.lang.Class----) |  |
| [getTaskId()](#getTaskId--) |  |
| [getText(int arg0)](#getText-int-) |  |
| [getTheme()](#getTheme--) |  |
| [getTitle()](#getTitle--) |  |
| [getTitleColor()](#getTitleColor--) |  |
| [getViewModelStore()](#getViewModelStore--) |  |
| [getVoiceInteractor()](#getVoiceInteractor--) |  |
| [getVolumeControlStream()](#getVolumeControlStream--) |  |
| [getWallpaper()](#getWallpaper--) |  |
| [getWallpaperDesiredMinimumHeight()](#getWallpaperDesiredMinimumHeight--) |  |
| [getWallpaperDesiredMinimumWidth()](#getWallpaperDesiredMinimumWidth--) |  |
| [getWindow()](#getWindow--) |  |
| [getWindowManager()](#getWindowManager--) |  |
| [grantUriPermission(String arg0, Uri arg1, int arg2)](#grantUriPermission-java.lang.String-android.net.Uri-int-) |  |
| [hasWindowFocus()](#hasWindowFocus--) |  |
| [hashCode()](#hashCode--) |  |
| [invalidateMenu()](#invalidateMenu--) |  |
| [invalidateOptionsMenu()](#invalidateOptionsMenu--) |  |
| [isActivityTransitionRunning()](#isActivityTransitionRunning--) |  |
| [isChangingConfigurations()](#isChangingConfigurations--) |  |
| [isChild()](#isChild--) |  |
| [isDestroyed()](#isDestroyed--) |  |
| [isDeviceProtectedStorage()](#isDeviceProtectedStorage--) |  |
| [isFinishing()](#isFinishing--) |  |
| [isImmersive()](#isImmersive--) |  |
| [isInMultiWindowMode()](#isInMultiWindowMode--) |  |
| [isInPictureInPictureMode()](#isInPictureInPictureMode--) |  |
| [isLaunchedFromBubble()](#isLaunchedFromBubble--) |  |
| [isLocalVoiceInteractionSupported()](#isLocalVoiceInteractionSupported--) |  |
| [isRestricted()](#isRestricted--) |  |
| [isTaskRoot()](#isTaskRoot--) |  |
| [isUiContext()](#isUiContext--) |  |
| [isVoiceInteraction()](#isVoiceInteraction--) |  |
| [isVoiceInteractionRoot()](#isVoiceInteractionRoot--) |  |
| [managedQuery(Uri arg0, String[] arg1, String arg2, String[] arg3, String arg4)](#managedQuery-android.net.Uri-java.lang.String---java.lang.String-java.lang.String---java.lang.String-) |  |
| [moveDatabaseFrom(Context arg0, String arg1)](#moveDatabaseFrom-android.content.Context-java.lang.String-) |  |
| [moveSharedPreferencesFrom(Context arg0, String arg1)](#moveSharedPreferencesFrom-android.content.Context-java.lang.String-) |  |
| [moveTaskToBack(boolean arg0)](#moveTaskToBack-boolean-) |  |
| [navigateUpTo(Intent arg0)](#navigateUpTo-android.content.Intent-) |  |
| [navigateUpToFromChild(Activity arg0, Intent arg1)](#navigateUpToFromChild-android.app.Activity-android.content.Intent-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [obtainStyledAttributes(AttributeSet arg0, int[] arg1)](#obtainStyledAttributes-android.util.AttributeSet-int---) |  |
| [obtainStyledAttributes(AttributeSet arg0, int[] arg1, int arg2, int arg3)](#obtainStyledAttributes-android.util.AttributeSet-int---int-int-) |  |
| [obtainStyledAttributes(int arg0, int[] arg1)](#obtainStyledAttributes-int-int---) |  |
| [obtainStyledAttributes(int[] arg0)](#obtainStyledAttributes-int---) |  |
| [onActionModeFinished(ActionMode arg0)](#onActionModeFinished-android.view.ActionMode-) |  |
| [onActionModeStarted(ActionMode arg0)](#onActionModeStarted-android.view.ActionMode-) |  |
| [onActivityReenter(int arg0, Intent arg1)](#onActivityReenter-int-android.content.Intent-) |  |
| [onAttachFragment(Fragment arg0)](#onAttachFragment-android.app.Fragment-) |  |
| [onAttachFragment(Fragment arg0)](#onAttachFragment-androidx.fragment.app.Fragment-) |  |
| [onAttachedToWindow()](#onAttachedToWindow--) |  |
| [onBackPressed()](#onBackPressed--) |  |
| [onConfigurationChanged(Configuration arg0)](#onConfigurationChanged-android.content.res.Configuration-) |  |
| [onContentChanged()](#onContentChanged--) |  |
| [onContextItemSelected(MenuItem arg0)](#onContextItemSelected-android.view.MenuItem-) |  |
| [onContextMenuClosed(Menu arg0)](#onContextMenuClosed-android.view.Menu-) |  |
| [onCreate(Bundle arg0, PersistableBundle arg1)](#onCreate-android.os.Bundle-android.os.PersistableBundle-) |  |
| [onCreateContextMenu(ContextMenu arg0, View arg1, ContextMenu.ContextMenuInfo arg2)](#onCreateContextMenu-android.view.ContextMenu-android.view.View-android.view.ContextMenu.ContextMenuInfo-) |  |
| [onCreateDescription()](#onCreateDescription--) |  |
| [onCreateNavigateUpTaskStack(TaskStackBuilder arg0)](#onCreateNavigateUpTaskStack-android.app.TaskStackBuilder-) |  |
| [onCreateOptionsMenu(Menu arg0)](#onCreateOptionsMenu-android.view.Menu-) |  |
| [onCreatePanelMenu(int arg0, Menu arg1)](#onCreatePanelMenu-int-android.view.Menu-) |  |
| [onCreatePanelView(int arg0)](#onCreatePanelView-int-) |  |
| [onCreateSupportNavigateUpTaskStack(TaskStackBuilder arg0)](#onCreateSupportNavigateUpTaskStack-androidx.core.app.TaskStackBuilder-) |  |
| [onCreateThumbnail(Bitmap arg0, Canvas arg1)](#onCreateThumbnail-android.graphics.Bitmap-android.graphics.Canvas-) |  |
| [onCreateView(View arg0, String arg1, Context arg2, AttributeSet arg3)](#onCreateView-android.view.View-java.lang.String-android.content.Context-android.util.AttributeSet-) |  |
| [onCreateView(String arg0, Context arg1, AttributeSet arg2)](#onCreateView-java.lang.String-android.content.Context-android.util.AttributeSet-) |  |
| [onDetachedFromWindow()](#onDetachedFromWindow--) |  |
| [onEnterAnimationComplete()](#onEnterAnimationComplete--) |  |
| [onGenericMotionEvent(MotionEvent arg0)](#onGenericMotionEvent-android.view.MotionEvent-) |  |
| [onGetDirectActions(CancellationSignal arg0, Consumer<List<DirectAction>> arg1)](#onGetDirectActions-android.os.CancellationSignal-java.util.function.Consumer-java.util.List-android.app.DirectAction---) |  |
| [onKeyDown(int arg0, KeyEvent arg1)](#onKeyDown-int-android.view.KeyEvent-) |  |
| [onKeyLongPress(int arg0, KeyEvent arg1)](#onKeyLongPress-int-android.view.KeyEvent-) |  |
| [onKeyMultiple(int arg0, int arg1, KeyEvent arg2)](#onKeyMultiple-int-int-android.view.KeyEvent-) |  |
| [onKeyShortcut(int arg0, KeyEvent arg1)](#onKeyShortcut-int-android.view.KeyEvent-) |  |
| [onKeyUp(int arg0, KeyEvent arg1)](#onKeyUp-int-android.view.KeyEvent-) |  |
| [onLocalVoiceInteractionStarted()](#onLocalVoiceInteractionStarted--) |  |
| [onLocalVoiceInteractionStopped()](#onLocalVoiceInteractionStopped--) |  |
| [onLowMemory()](#onLowMemory--) |  |
| [onMenuItemSelected(int arg0, MenuItem arg1)](#onMenuItemSelected-int-android.view.MenuItem-) |  |
| [onMenuOpened(int arg0, Menu arg1)](#onMenuOpened-int-android.view.Menu-) |  |
| [onMultiWindowModeChanged(boolean arg0)](#onMultiWindowModeChanged-boolean-) |  |
| [onMultiWindowModeChanged(boolean arg0, Configuration arg1)](#onMultiWindowModeChanged-boolean-android.content.res.Configuration-) |  |
| [onNavigateUp()](#onNavigateUp--) |  |
| [onNavigateUpFromChild(Activity arg0)](#onNavigateUpFromChild-android.app.Activity-) |  |
| [onOptionsItemSelected(MenuItem arg0)](#onOptionsItemSelected-android.view.MenuItem-) |  |
| [onOptionsMenuClosed(Menu arg0)](#onOptionsMenuClosed-android.view.Menu-) |  |
| [onPanelClosed(int arg0, Menu arg1)](#onPanelClosed-int-android.view.Menu-) |  |
| [onPerformDirectAction(String arg0, Bundle arg1, CancellationSignal arg2, Consumer<Bundle> arg3)](#onPerformDirectAction-java.lang.String-android.os.Bundle-android.os.CancellationSignal-java.util.function.Consumer-android.os.Bundle--) |  |
| [onPictureInPictureModeChanged(boolean arg0)](#onPictureInPictureModeChanged-boolean-) |  |
| [onPictureInPictureModeChanged(boolean arg0, Configuration arg1)](#onPictureInPictureModeChanged-boolean-android.content.res.Configuration-) |  |
| [onPictureInPictureRequested()](#onPictureInPictureRequested--) |  |
| [onPictureInPictureUiStateChanged(PictureInPictureUiState arg0)](#onPictureInPictureUiStateChanged-android.app.PictureInPictureUiState-) |  |
| [onPostCreate(Bundle arg0, PersistableBundle arg1)](#onPostCreate-android.os.Bundle-android.os.PersistableBundle-) |  |
| [onPrepareNavigateUpTaskStack(TaskStackBuilder arg0)](#onPrepareNavigateUpTaskStack-android.app.TaskStackBuilder-) |  |
| [onPrepareOptionsMenu(Menu arg0)](#onPrepareOptionsMenu-android.view.Menu-) |  |
| [onPreparePanel(int arg0, View arg1, Menu arg2)](#onPreparePanel-int-android.view.View-android.view.Menu-) |  |
| [onPrepareSupportNavigateUpTaskStack(TaskStackBuilder arg0)](#onPrepareSupportNavigateUpTaskStack-androidx.core.app.TaskStackBuilder-) |  |
| [onProvideAssistContent(AssistContent arg0)](#onProvideAssistContent-android.app.assist.AssistContent-) |  |
| [onProvideAssistData(Bundle arg0)](#onProvideAssistData-android.os.Bundle-) |  |
| [onProvideKeyboardShortcuts(List<KeyboardShortcutGroup> arg0, Menu arg1, int arg2)](#onProvideKeyboardShortcuts-java.util.List-android.view.KeyboardShortcutGroup--android.view.Menu-int-) |  |
| [onProvideReferrer()](#onProvideReferrer--) |  |
| [onRequestPermissionsResult(int requestCode, String[] permissions, int[] grantResults)](#onRequestPermissionsResult-int-java.lang.String---int---) |  |
| [onRestoreInstanceState(Bundle arg0, PersistableBundle arg1)](#onRestoreInstanceState-android.os.Bundle-android.os.PersistableBundle-) |  |
| [onRetainCustomNonConfigurationInstance()](#onRetainCustomNonConfigurationInstance--) |  |
| [onRetainNonConfigurationInstance()](#onRetainNonConfigurationInstance--) |  |
| [onSaveInstanceState(Bundle arg0, PersistableBundle arg1)](#onSaveInstanceState-android.os.Bundle-android.os.PersistableBundle-) |  |
| [onSearchRequested()](#onSearchRequested--) |  |
| [onSearchRequested(SearchEvent arg0)](#onSearchRequested-android.view.SearchEvent-) |  |
| [onStateNotSaved()](#onStateNotSaved--) |  |
| [onSupportActionModeFinished(ActionMode arg0)](#onSupportActionModeFinished-androidx.appcompat.view.ActionMode-) |  |
| [onSupportActionModeStarted(ActionMode arg0)](#onSupportActionModeStarted-androidx.appcompat.view.ActionMode-) |  |
| [onSupportContentChanged()](#onSupportContentChanged--) |  |
| [onSupportNavigateUp()](#onSupportNavigateUp--) |  |
| [onTopResumedActivityChanged(boolean arg0)](#onTopResumedActivityChanged-boolean-) |  |
| [onTouchEvent(MotionEvent arg0)](#onTouchEvent-android.view.MotionEvent-) |  |
| [onTrackballEvent(MotionEvent arg0)](#onTrackballEvent-android.view.MotionEvent-) |  |
| [onTrimMemory(int arg0)](#onTrimMemory-int-) |  |
| [onUserInteraction()](#onUserInteraction--) |  |
| [onVisibleBehindCanceled()](#onVisibleBehindCanceled--) |  |
| [onWindowAttributesChanged(WindowManager.LayoutParams arg0)](#onWindowAttributesChanged-android.view.WindowManager.LayoutParams-) |  |
| [onWindowFocusChanged(boolean arg0)](#onWindowFocusChanged-boolean-) |  |
| [onWindowStartingActionMode(ActionMode.Callback arg0)](#onWindowStartingActionMode-android.view.ActionMode.Callback-) |  |
| [onWindowStartingActionMode(ActionMode.Callback arg0, int arg1)](#onWindowStartingActionMode-android.view.ActionMode.Callback-int-) |  |
| [onWindowStartingSupportActionMode(ActionMode.Callback arg0)](#onWindowStartingSupportActionMode-androidx.appcompat.view.ActionMode.Callback-) |  |
| [openContextMenu(View arg0)](#openContextMenu-android.view.View-) |  |
| [openFileInput(String arg0)](#openFileInput-java.lang.String-) |  |
| [openFileOutput(String arg0, int arg1)](#openFileOutput-java.lang.String-int-) |  |
| [openOptionsMenu()](#openOptionsMenu--) |  |
| [openOrCreateDatabase(String arg0, int arg1, SQLiteDatabase.CursorFactory arg2)](#openOrCreateDatabase-java.lang.String-int-android.database.sqlite.SQLiteDatabase.CursorFactory-) |  |
| [openOrCreateDatabase(String arg0, int arg1, SQLiteDatabase.CursorFactory arg2, DatabaseErrorHandler arg3)](#openOrCreateDatabase-java.lang.String-int-android.database.sqlite.SQLiteDatabase.CursorFactory-android.database.DatabaseErrorHandler-) |  |
| [overridePendingTransition(int arg0, int arg1)](#overridePendingTransition-int-int-) |  |
| [overridePendingTransition(int arg0, int arg1, int arg2)](#overridePendingTransition-int-int-int-) |  |
| [peekAvailableContext()](#peekAvailableContext--) |  |
| [peekWallpaper()](#peekWallpaper--) |  |
| [postponeEnterTransition()](#postponeEnterTransition--) |  |
| [putExtraData(ComponentActivity.ExtraData arg0)](#putExtraData-androidx.core.app.ComponentActivity.ExtraData-) |  |
| [recreate()](#recreate--) |  |
| [registerActivityLifecycleCallbacks(Application.ActivityLifecycleCallbacks arg0)](#registerActivityLifecycleCallbacks-android.app.Application.ActivityLifecycleCallbacks-) |  |
| [registerComponentCallbacks(ComponentCallbacks arg0)](#registerComponentCallbacks-android.content.ComponentCallbacks-) |  |
| [registerForContextMenu(View arg0)](#registerForContextMenu-android.view.View-) |  |
| [registerReceiver(BroadcastReceiver arg0, IntentFilter arg1)](#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-) |  |
| [registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, int arg2)](#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-int-) |  |
| [registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, String arg2, Handler arg3)](#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-java.lang.String-android.os.Handler-) |  |
| [registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, String arg2, Handler arg3, int arg4)](#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-java.lang.String-android.os.Handler-int-) |  |
| [releaseInstance()](#releaseInstance--) |  |
| [removeDialog(int arg0)](#removeDialog-int-) |  |
| [removeMenuProvider(MenuProvider arg0)](#removeMenuProvider-androidx.core.view.MenuProvider-) |  |
| [removeOnConfigurationChangedListener(Consumer<Configuration> arg0)](#removeOnConfigurationChangedListener-androidx.core.util.Consumer-android.content.res.Configuration--) |  |
| [removeOnContextAvailableListener(OnContextAvailableListener arg0)](#removeOnContextAvailableListener-androidx.activity.contextaware.OnContextAvailableListener-) |  |
| [removeOnMultiWindowModeChangedListener(Consumer<MultiWindowModeChangedInfo> arg0)](#removeOnMultiWindowModeChangedListener-androidx.core.util.Consumer-androidx.core.app.MultiWindowModeChangedInfo--) |  |
| [removeOnNewIntentListener(Consumer<Intent> arg0)](#removeOnNewIntentListener-androidx.core.util.Consumer-android.content.Intent--) |  |
| [removeOnPictureInPictureModeChangedListener(Consumer<PictureInPictureModeChangedInfo> arg0)](#removeOnPictureInPictureModeChangedListener-androidx.core.util.Consumer-androidx.core.app.PictureInPictureModeChangedInfo--) |  |
| [removeOnTrimMemoryListener(Consumer<Integer> arg0)](#removeOnTrimMemoryListener-androidx.core.util.Consumer-java.lang.Integer--) |  |
| [removeStickyBroadcast(Intent arg0)](#removeStickyBroadcast-android.content.Intent-) |  |
| [removeStickyBroadcastAsUser(Intent arg0, UserHandle arg1)](#removeStickyBroadcastAsUser-android.content.Intent-android.os.UserHandle-) |  |
| [reportFullyDrawn()](#reportFullyDrawn--) |  |
| [requestDragAndDropPermissions(DragEvent arg0)](#requestDragAndDropPermissions-android.view.DragEvent-) |  |
| [requestPermissions(String[] arg0, int arg1)](#requestPermissions-java.lang.String---int-) |  |
| [requestShowKeyboardShortcuts()](#requestShowKeyboardShortcuts--) |  |
| [requestVisibleBehind(boolean arg0)](#requestVisibleBehind-boolean-) |  |
| [requestWindowFeature(int arg0)](#requestWindowFeature-int-) |  |
| [revokeSelfPermissionOnKill(String arg0)](#revokeSelfPermissionOnKill-java.lang.String-) |  |
| [revokeSelfPermissionsOnKill(Collection<String> arg0)](#revokeSelfPermissionsOnKill-java.util.Collection-java.lang.String--) |  |
| [revokeUriPermission(Uri arg0, int arg1)](#revokeUriPermission-android.net.Uri-int-) |  |
| [revokeUriPermission(String arg0, Uri arg1, int arg2)](#revokeUriPermission-java.lang.String-android.net.Uri-int-) |  |
| [runOnUiThread(Runnable arg0)](#runOnUiThread-java.lang.Runnable-) |  |
| [sendBroadcast(Intent arg0)](#sendBroadcast-android.content.Intent-) |  |
| [sendBroadcast(Intent arg0, String arg1)](#sendBroadcast-android.content.Intent-java.lang.String-) |  |
| [sendBroadcastAsUser(Intent arg0, UserHandle arg1)](#sendBroadcastAsUser-android.content.Intent-android.os.UserHandle-) |  |
| [sendBroadcastAsUser(Intent arg0, UserHandle arg1, String arg2)](#sendBroadcastAsUser-android.content.Intent-android.os.UserHandle-java.lang.String-) |  |
| [sendBroadcastWithMultiplePermissions(Intent arg0, String[] arg1)](#sendBroadcastWithMultiplePermissions-android.content.Intent-java.lang.String---) |  |
| [sendOrderedBroadcast(Intent arg0, int arg1, String arg2, String arg3, BroadcastReceiver arg4, Handler arg5, String arg6, Bundle arg7, Bundle arg8)](#sendOrderedBroadcast-android.content.Intent-int-java.lang.String-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-java.lang.String-android.os.Bundle-android.os.Bundle-) |  |
| [sendOrderedBroadcast(Intent arg0, String arg1)](#sendOrderedBroadcast-android.content.Intent-java.lang.String-) |  |
| [sendOrderedBroadcast(Intent arg0, String arg1, BroadcastReceiver arg2, Handler arg3, int arg4, String arg5, Bundle arg6)](#sendOrderedBroadcast-android.content.Intent-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-) |  |
| [sendOrderedBroadcast(Intent arg0, String arg1, String arg2, BroadcastReceiver arg3, Handler arg4, int arg5, String arg6, Bundle arg7)](#sendOrderedBroadcast-android.content.Intent-java.lang.String-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-) |  |
| [sendOrderedBroadcastAsUser(Intent arg0, UserHandle arg1, String arg2, BroadcastReceiver arg3, Handler arg4, int arg5, String arg6, Bundle arg7)](#sendOrderedBroadcastAsUser-android.content.Intent-android.os.UserHandle-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-) |  |
| [sendStickyBroadcast(Intent arg0)](#sendStickyBroadcast-android.content.Intent-) |  |
| [sendStickyBroadcast(Intent arg0, Bundle arg1)](#sendStickyBroadcast-android.content.Intent-android.os.Bundle-) |  |
| [sendStickyBroadcastAsUser(Intent arg0, UserHandle arg1)](#sendStickyBroadcastAsUser-android.content.Intent-android.os.UserHandle-) |  |
| [sendStickyOrderedBroadcast(Intent arg0, BroadcastReceiver arg1, Handler arg2, int arg3, String arg4, Bundle arg5)](#sendStickyOrderedBroadcast-android.content.Intent-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-) |  |
| [sendStickyOrderedBroadcastAsUser(Intent arg0, UserHandle arg1, BroadcastReceiver arg2, Handler arg3, int arg4, String arg5, Bundle arg6)](#sendStickyOrderedBroadcastAsUser-android.content.Intent-android.os.UserHandle-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-) |  |
| [setActionBar(Toolbar arg0)](#setActionBar-android.widget.Toolbar-) |  |
| [setContentTransitionManager(TransitionManager arg0)](#setContentTransitionManager-android.transition.TransitionManager-) |  |
| [setContentView(View arg0)](#setContentView-android.view.View-) |  |
| [setContentView(View arg0, ViewGroup.LayoutParams arg1)](#setContentView-android.view.View-android.view.ViewGroup.LayoutParams-) |  |
| [setContentView(int arg0)](#setContentView-int-) |  |
| [setDefaultKeyMode(int arg0)](#setDefaultKeyMode-int-) |  |
| [setEnterSharedElementCallback(SharedElementCallback arg0)](#setEnterSharedElementCallback-android.app.SharedElementCallback-) |  |
| [setEnterSharedElementCallback(SharedElementCallback arg0)](#setEnterSharedElementCallback-androidx.core.app.SharedElementCallback-) |  |
| [setExitSharedElementCallback(SharedElementCallback arg0)](#setExitSharedElementCallback-android.app.SharedElementCallback-) |  |
| [setExitSharedElementCallback(SharedElementCallback arg0)](#setExitSharedElementCallback-androidx.core.app.SharedElementCallback-) |  |
| [setFeatureDrawable(int arg0, Drawable arg1)](#setFeatureDrawable-int-android.graphics.drawable.Drawable-) |  |
| [setFeatureDrawableAlpha(int arg0, int arg1)](#setFeatureDrawableAlpha-int-int-) |  |
| [setFeatureDrawableResource(int arg0, int arg1)](#setFeatureDrawableResource-int-int-) |  |
| [setFeatureDrawableUri(int arg0, Uri arg1)](#setFeatureDrawableUri-int-android.net.Uri-) |  |
| [setFinishOnTouchOutside(boolean arg0)](#setFinishOnTouchOutside-boolean-) |  |
| [setImmersive(boolean arg0)](#setImmersive-boolean-) |  |
| [setInheritShowWhenLocked(boolean arg0)](#setInheritShowWhenLocked-boolean-) |  |
| [setIntent(Intent arg0)](#setIntent-android.content.Intent-) |  |
| [setLocusContext(LocusId arg0, Bundle arg1)](#setLocusContext-android.content.LocusId-android.os.Bundle-) |  |
| [setMediaController(MediaController arg0)](#setMediaController-android.media.session.MediaController-) |  |
| [setPictureInPictureParams(PictureInPictureParams arg0)](#setPictureInPictureParams-android.app.PictureInPictureParams-) |  |
| [setProgress(int arg0)](#setProgress-int-) |  |
| [setProgressBarIndeterminate(boolean arg0)](#setProgressBarIndeterminate-boolean-) |  |
| [setProgressBarIndeterminateVisibility(boolean arg0)](#setProgressBarIndeterminateVisibility-boolean-) |  |
| [setProgressBarVisibility(boolean arg0)](#setProgressBarVisibility-boolean-) |  |
| [setRecentsScreenshotEnabled(boolean arg0)](#setRecentsScreenshotEnabled-boolean-) |  |
| [setRequestedOrientation(int arg0)](#setRequestedOrientation-int-) |  |
| [setResult(int arg0)](#setResult-int-) |  |
| [setResult(int arg0, Intent arg1)](#setResult-int-android.content.Intent-) |  |
| [setSecondaryProgress(int arg0)](#setSecondaryProgress-int-) |  |
| [setShouldDockBigOverlays(boolean arg0)](#setShouldDockBigOverlays-boolean-) |  |
| [setShowWhenLocked(boolean arg0)](#setShowWhenLocked-boolean-) |  |
| [setSupportActionBar(Toolbar arg0)](#setSupportActionBar-androidx.appcompat.widget.Toolbar-) |  |
| [setSupportProgress(int arg0)](#setSupportProgress-int-) |  |
| [setSupportProgressBarIndeterminate(boolean arg0)](#setSupportProgressBarIndeterminate-boolean-) |  |
| [setSupportProgressBarIndeterminateVisibility(boolean arg0)](#setSupportProgressBarIndeterminateVisibility-boolean-) |  |
| [setSupportProgressBarVisibility(boolean arg0)](#setSupportProgressBarVisibility-boolean-) |  |
| [setTaskDescription(ActivityManager.TaskDescription arg0)](#setTaskDescription-android.app.ActivityManager.TaskDescription-) |  |
| [setTheme(Resources.Theme arg0)](#setTheme-android.content.res.Resources.Theme-) |  |
| [setTheme(int arg0)](#setTheme-int-) |  |
| [setTitle(int arg0)](#setTitle-int-) |  |
| [setTitle(CharSequence arg0)](#setTitle-java.lang.CharSequence-) |  |
| [setTitleColor(int arg0)](#setTitleColor-int-) |  |
| [setTranslucent(boolean arg0)](#setTranslucent-boolean-) |  |
| [setTurnScreenOn(boolean arg0)](#setTurnScreenOn-boolean-) |  |
| [setVisible(boolean arg0)](#setVisible-boolean-) |  |
| [setVolumeControlStream(int arg0)](#setVolumeControlStream-int-) |  |
| [setVrModeEnabled(boolean arg0, ComponentName arg1)](#setVrModeEnabled-boolean-android.content.ComponentName-) |  |
| [setWallpaper(Bitmap arg0)](#setWallpaper-android.graphics.Bitmap-) |  |
| [setWallpaper(InputStream arg0)](#setWallpaper-java.io.InputStream-) |  |
| [shouldDockBigOverlays()](#shouldDockBigOverlays--) |  |
| [shouldShowRequestPermissionRationale(String arg0)](#shouldShowRequestPermissionRationale-java.lang.String-) |  |
| [shouldUpRecreateTask(Intent arg0)](#shouldUpRecreateTask-android.content.Intent-) |  |
| [showAssist(Bundle arg0)](#showAssist-android.os.Bundle-) |  |
| [showDialog(int arg0)](#showDialog-int-) |  |
| [showDialog(int arg0, Bundle arg1)](#showDialog-int-android.os.Bundle-) |  |
| [showLockTaskEscapeMessage()](#showLockTaskEscapeMessage--) |  |
| [startActionMode(ActionMode.Callback arg0)](#startActionMode-android.view.ActionMode.Callback-) |  |
| [startActionMode(ActionMode.Callback arg0, int arg1)](#startActionMode-android.view.ActionMode.Callback-int-) |  |
| [startActivities(Intent[] arg0)](#startActivities-android.content.Intent---) |  |
| [startActivities(Intent[] arg0, Bundle arg1)](#startActivities-android.content.Intent---android.os.Bundle-) |  |
| [startActivity(Intent arg0)](#startActivity-android.content.Intent-) |  |
| [startActivity(Intent arg0, Bundle arg1)](#startActivity-android.content.Intent-android.os.Bundle-) |  |
| [startActivityForResult(Intent arg0, int arg1)](#startActivityForResult-android.content.Intent-int-) |  |
| [startActivityForResult(Intent arg0, int arg1, Bundle arg2)](#startActivityForResult-android.content.Intent-int-android.os.Bundle-) |  |
| [startActivityFromChild(Activity arg0, Intent arg1, int arg2)](#startActivityFromChild-android.app.Activity-android.content.Intent-int-) |  |
| [startActivityFromChild(Activity arg0, Intent arg1, int arg2, Bundle arg3)](#startActivityFromChild-android.app.Activity-android.content.Intent-int-android.os.Bundle-) |  |
| [startActivityFromFragment(Fragment arg0, Intent arg1, int arg2)](#startActivityFromFragment-android.app.Fragment-android.content.Intent-int-) |  |
| [startActivityFromFragment(Fragment arg0, Intent arg1, int arg2, Bundle arg3)](#startActivityFromFragment-android.app.Fragment-android.content.Intent-int-android.os.Bundle-) |  |
| [startActivityFromFragment(Fragment arg0, Intent arg1, int arg2)](#startActivityFromFragment-androidx.fragment.app.Fragment-android.content.Intent-int-) |  |
| [startActivityFromFragment(Fragment arg0, Intent arg1, int arg2, Bundle arg3)](#startActivityFromFragment-androidx.fragment.app.Fragment-android.content.Intent-int-android.os.Bundle-) |  |
| [startActivityIfNeeded(Intent arg0, int arg1)](#startActivityIfNeeded-android.content.Intent-int-) |  |
| [startActivityIfNeeded(Intent arg0, int arg1, Bundle arg2)](#startActivityIfNeeded-android.content.Intent-int-android.os.Bundle-) |  |
| [startForegroundService(Intent arg0)](#startForegroundService-android.content.Intent-) |  |
| [startInstrumentation(ComponentName arg0, String arg1, Bundle arg2)](#startInstrumentation-android.content.ComponentName-java.lang.String-android.os.Bundle-) |  |
| [startIntentSender(IntentSender arg0, Intent arg1, int arg2, int arg3, int arg4)](#startIntentSender-android.content.IntentSender-android.content.Intent-int-int-int-) |  |
| [startIntentSender(IntentSender arg0, Intent arg1, int arg2, int arg3, int arg4, Bundle arg5)](#startIntentSender-android.content.IntentSender-android.content.Intent-int-int-int-android.os.Bundle-) |  |
| [startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5)](#startIntentSenderForResult-android.content.IntentSender-int-android.content.Intent-int-int-int-) |  |
| [startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5, Bundle arg6)](#startIntentSenderForResult-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-) |  |
| [startIntentSenderFromChild(Activity arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6)](#startIntentSenderFromChild-android.app.Activity-android.content.IntentSender-int-android.content.Intent-int-int-int-) |  |
| [startIntentSenderFromChild(Activity arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6, Bundle arg7)](#startIntentSenderFromChild-android.app.Activity-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-) |  |
| [startIntentSenderFromFragment(Fragment arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6, Bundle arg7)](#startIntentSenderFromFragment-androidx.fragment.app.Fragment-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-) |  |
| [startLocalVoiceInteraction(Bundle arg0)](#startLocalVoiceInteraction-android.os.Bundle-) |  |
| [startLockTask()](#startLockTask--) |  |
| [startManagingCursor(Cursor arg0)](#startManagingCursor-android.database.Cursor-) |  |
| [startNextMatchingActivity(Intent arg0)](#startNextMatchingActivity-android.content.Intent-) |  |
| [startNextMatchingActivity(Intent arg0, Bundle arg1)](#startNextMatchingActivity-android.content.Intent-android.os.Bundle-) |  |
| [startPostponedEnterTransition()](#startPostponedEnterTransition--) |  |
| [startSearch(String arg0, boolean arg1, Bundle arg2, boolean arg3)](#startSearch-java.lang.String-boolean-android.os.Bundle-boolean-) |  |
| [startService(Intent arg0)](#startService-android.content.Intent-) |  |
| [startSupportActionMode(ActionMode.Callback arg0)](#startSupportActionMode-androidx.appcompat.view.ActionMode.Callback-) |  |
| [stopLocalVoiceInteraction()](#stopLocalVoiceInteraction--) |  |
| [stopLockTask()](#stopLockTask--) |  |
| [stopManagingCursor(Cursor arg0)](#stopManagingCursor-android.database.Cursor-) |  |
| [stopService(Intent arg0)](#stopService-android.content.Intent-) |  |
| [superDispatchKeyEvent(KeyEvent arg0)](#superDispatchKeyEvent-android.view.KeyEvent-) |  |
| [supportFinishAfterTransition()](#supportFinishAfterTransition--) |  |
| [supportInvalidateOptionsMenu()](#supportInvalidateOptionsMenu--) |  |
| [supportNavigateUpTo(Intent arg0)](#supportNavigateUpTo-android.content.Intent-) |  |
| [supportPostponeEnterTransition()](#supportPostponeEnterTransition--) |  |
| [supportRequestWindowFeature(int arg0)](#supportRequestWindowFeature-int-) |  |
| [supportShouldUpRecreateTask(Intent arg0)](#supportShouldUpRecreateTask-android.content.Intent-) |  |
| [supportStartPostponedEnterTransition()](#supportStartPostponedEnterTransition--) |  |
| [takeKeyEvents(boolean arg0)](#takeKeyEvents-boolean-) |  |
| [toString()](#toString--) |  |
| [triggerSearch(String arg0, Bundle arg1)](#triggerSearch-java.lang.String-android.os.Bundle-) |  |
| [unbindService(ServiceConnection arg0)](#unbindService-android.content.ServiceConnection-) |  |
| [unregisterActivityLifecycleCallbacks(Application.ActivityLifecycleCallbacks arg0)](#unregisterActivityLifecycleCallbacks-android.app.Application.ActivityLifecycleCallbacks-) |  |
| [unregisterComponentCallbacks(ComponentCallbacks arg0)](#unregisterComponentCallbacks-android.content.ComponentCallbacks-) |  |
| [unregisterForContextMenu(View arg0)](#unregisterForContextMenu-android.view.View-) |  |
| [unregisterReceiver(BroadcastReceiver arg0)](#unregisterReceiver-android.content.BroadcastReceiver-) |  |
| [updateServiceGroup(ServiceConnection arg0, int arg1, int arg2)](#updateServiceGroup-android.content.ServiceConnection-int-int-) |  |
| [validateRequestPermissionsRequestCode(int arg0)](#validateRequestPermissionsRequestCode-int-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeScannerActivity() {#BarcodeScannerActivity--}
```
public BarcodeScannerActivity()
```


### ACCESSIBILITY_SERVICE {#ACCESSIBILITY-SERVICE}
```
public static final String ACCESSIBILITY_SERVICE
```


### ACCOUNT_SERVICE {#ACCOUNT-SERVICE}
```
public static final String ACCOUNT_SERVICE
```


### ACTIVITY_SERVICE {#ACTIVITY-SERVICE}
```
public static final String ACTIVITY_SERVICE
```


### ALARM_SERVICE {#ALARM-SERVICE}
```
public static final String ALARM_SERVICE
```


### APPWIDGET_SERVICE {#APPWIDGET-SERVICE}
```
public static final String APPWIDGET_SERVICE
```


### APP_OPS_SERVICE {#APP-OPS-SERVICE}
```
public static final String APP_OPS_SERVICE
```


### APP_SEARCH_SERVICE {#APP-SEARCH-SERVICE}
```
public static final String APP_SEARCH_SERVICE
```


### AUDIO_SERVICE {#AUDIO-SERVICE}
```
public static final String AUDIO_SERVICE
```


### BATTERY_SERVICE {#BATTERY-SERVICE}
```
public static final String BATTERY_SERVICE
```


### BIND_ABOVE_CLIENT {#BIND-ABOVE-CLIENT}
```
public static final int BIND_ABOVE_CLIENT
```


### BIND_ADJUST_WITH_ACTIVITY {#BIND-ADJUST-WITH-ACTIVITY}
```
public static final int BIND_ADJUST_WITH_ACTIVITY
```


### BIND_ALLOW_OOM_MANAGEMENT {#BIND-ALLOW-OOM-MANAGEMENT}
```
public static final int BIND_ALLOW_OOM_MANAGEMENT
```


### BIND_AUTO_CREATE {#BIND-AUTO-CREATE}
```
public static final int BIND_AUTO_CREATE
```


### BIND_DEBUG_UNBIND {#BIND-DEBUG-UNBIND}
```
public static final int BIND_DEBUG_UNBIND
```


### BIND_EXTERNAL_SERVICE {#BIND-EXTERNAL-SERVICE}
```
public static final int BIND_EXTERNAL_SERVICE
```


### BIND_IMPORTANT {#BIND-IMPORTANT}
```
public static final int BIND_IMPORTANT
```


### BIND_INCLUDE_CAPABILITIES {#BIND-INCLUDE-CAPABILITIES}
```
public static final int BIND_INCLUDE_CAPABILITIES
```


### BIND_NOT_FOREGROUND {#BIND-NOT-FOREGROUND}
```
public static final int BIND_NOT_FOREGROUND
```


### BIND_NOT_PERCEPTIBLE {#BIND-NOT-PERCEPTIBLE}
```
public static final int BIND_NOT_PERCEPTIBLE
```


### BIND_WAIVE_PRIORITY {#BIND-WAIVE-PRIORITY}
```
public static final int BIND_WAIVE_PRIORITY
```


### BIOMETRIC_SERVICE {#BIOMETRIC-SERVICE}
```
public static final String BIOMETRIC_SERVICE
```


### BLOB_STORE_SERVICE {#BLOB-STORE-SERVICE}
```
public static final String BLOB_STORE_SERVICE
```


### BLUETOOTH_SERVICE {#BLUETOOTH-SERVICE}
```
public static final String BLUETOOTH_SERVICE
```


### BUGREPORT_SERVICE {#BUGREPORT-SERVICE}
```
public static final String BUGREPORT_SERVICE
```


### CAMERA_SERVICE {#CAMERA-SERVICE}
```
public static final String CAMERA_SERVICE
```


### CAPTIONING_SERVICE {#CAPTIONING-SERVICE}
```
public static final String CAPTIONING_SERVICE
```


### CARRIER_CONFIG_SERVICE {#CARRIER-CONFIG-SERVICE}
```
public static final String CARRIER_CONFIG_SERVICE
```


### CLIPBOARD_SERVICE {#CLIPBOARD-SERVICE}
```
public static final String CLIPBOARD_SERVICE
```


### COMPANION_DEVICE_SERVICE {#COMPANION-DEVICE-SERVICE}
```
public static final String COMPANION_DEVICE_SERVICE
```


### CONNECTIVITY_DIAGNOSTICS_SERVICE {#CONNECTIVITY-DIAGNOSTICS-SERVICE}
```
public static final String CONNECTIVITY_DIAGNOSTICS_SERVICE
```


### CONNECTIVITY_SERVICE {#CONNECTIVITY-SERVICE}
```
public static final String CONNECTIVITY_SERVICE
```


### CONSUMER_IR_SERVICE {#CONSUMER-IR-SERVICE}
```
public static final String CONSUMER_IR_SERVICE
```


### CONTEXT_IGNORE_SECURITY {#CONTEXT-IGNORE-SECURITY}
```
public static final int CONTEXT_IGNORE_SECURITY
```


### CONTEXT_INCLUDE_CODE {#CONTEXT-INCLUDE-CODE}
```
public static final int CONTEXT_INCLUDE_CODE
```


### CONTEXT_RESTRICTED {#CONTEXT-RESTRICTED}
```
public static final int CONTEXT_RESTRICTED
```


### CROSS_PROFILE_APPS_SERVICE {#CROSS-PROFILE-APPS-SERVICE}
```
public static final String CROSS_PROFILE_APPS_SERVICE
```


### DEFAULT_KEYS_DIALER {#DEFAULT-KEYS-DIALER}
```
public static final int DEFAULT_KEYS_DIALER
```


### DEFAULT_KEYS_DISABLE {#DEFAULT-KEYS-DISABLE}
```
public static final int DEFAULT_KEYS_DISABLE
```


### DEFAULT_KEYS_SEARCH_GLOBAL {#DEFAULT-KEYS-SEARCH-GLOBAL}
```
public static final int DEFAULT_KEYS_SEARCH_GLOBAL
```


### DEFAULT_KEYS_SEARCH_LOCAL {#DEFAULT-KEYS-SEARCH-LOCAL}
```
public static final int DEFAULT_KEYS_SEARCH_LOCAL
```


### DEFAULT_KEYS_SHORTCUT {#DEFAULT-KEYS-SHORTCUT}
```
public static final int DEFAULT_KEYS_SHORTCUT
```


### DEVICE_POLICY_SERVICE {#DEVICE-POLICY-SERVICE}
```
public static final String DEVICE_POLICY_SERVICE
```


### DISPLAY_HASH_SERVICE {#DISPLAY-HASH-SERVICE}
```
public static final String DISPLAY_HASH_SERVICE
```


### DISPLAY_SERVICE {#DISPLAY-SERVICE}
```
public static final String DISPLAY_SERVICE
```


### DOMAIN_VERIFICATION_SERVICE {#DOMAIN-VERIFICATION-SERVICE}
```
public static final String DOMAIN_VERIFICATION_SERVICE
```


### DOWNLOAD_SERVICE {#DOWNLOAD-SERVICE}
```
public static final String DOWNLOAD_SERVICE
```


### DROPBOX_SERVICE {#DROPBOX-SERVICE}
```
public static final String DROPBOX_SERVICE
```


### EUICC_SERVICE {#EUICC-SERVICE}
```
public static final String EUICC_SERVICE
```


### FILE_INTEGRITY_SERVICE {#FILE-INTEGRITY-SERVICE}
```
public static final String FILE_INTEGRITY_SERVICE
```


### FINGERPRINT_SERVICE {#FINGERPRINT-SERVICE}
```
public static final String FINGERPRINT_SERVICE
```


### GAME_SERVICE {#GAME-SERVICE}
```
public static final String GAME_SERVICE
```


### HARDWARE_PROPERTIES_SERVICE {#HARDWARE-PROPERTIES-SERVICE}
```
public static final String HARDWARE_PROPERTIES_SERVICE
```


### INPUT_METHOD_SERVICE {#INPUT-METHOD-SERVICE}
```
public static final String INPUT_METHOD_SERVICE
```


### INPUT_SERVICE {#INPUT-SERVICE}
```
public static final String INPUT_SERVICE
```


### IPSEC_SERVICE {#IPSEC-SERVICE}
```
public static final String IPSEC_SERVICE
```


### JOB_SCHEDULER_SERVICE {#JOB-SCHEDULER-SERVICE}
```
public static final String JOB_SCHEDULER_SERVICE
```


### KEYGUARD_SERVICE {#KEYGUARD-SERVICE}
```
public static final String KEYGUARD_SERVICE
```


### LAUNCHER_APPS_SERVICE {#LAUNCHER-APPS-SERVICE}
```
public static final String LAUNCHER_APPS_SERVICE
```


### LAYOUT_INFLATER_SERVICE {#LAYOUT-INFLATER-SERVICE}
```
public static final String LAYOUT_INFLATER_SERVICE
```


### LOCALE_SERVICE {#LOCALE-SERVICE}
```
public static final String LOCALE_SERVICE
```


### LOCATION_SERVICE {#LOCATION-SERVICE}
```
public static final String LOCATION_SERVICE
```


### MEDIA_COMMUNICATION_SERVICE {#MEDIA-COMMUNICATION-SERVICE}
```
public static final String MEDIA_COMMUNICATION_SERVICE
```


### MEDIA_METRICS_SERVICE {#MEDIA-METRICS-SERVICE}
```
public static final String MEDIA_METRICS_SERVICE
```


### MEDIA_PROJECTION_SERVICE {#MEDIA-PROJECTION-SERVICE}
```
public static final String MEDIA_PROJECTION_SERVICE
```


### MEDIA_ROUTER_SERVICE {#MEDIA-ROUTER-SERVICE}
```
public static final String MEDIA_ROUTER_SERVICE
```


### MEDIA_SESSION_SERVICE {#MEDIA-SESSION-SERVICE}
```
public static final String MEDIA_SESSION_SERVICE
```


### MIDI_SERVICE {#MIDI-SERVICE}
```
public static final String MIDI_SERVICE
```


### MODE_APPEND {#MODE-APPEND}
```
public static final int MODE_APPEND
```


### MODE_ENABLE_WRITE_AHEAD_LOGGING {#MODE-ENABLE-WRITE-AHEAD-LOGGING}
```
public static final int MODE_ENABLE_WRITE_AHEAD_LOGGING
```


### MODE_MULTI_PROCESS {#MODE-MULTI-PROCESS}
```
public static final int MODE_MULTI_PROCESS
```


### MODE_NO_LOCALIZED_COLLATORS {#MODE-NO-LOCALIZED-COLLATORS}
```
public static final int MODE_NO_LOCALIZED_COLLATORS
```


### MODE_PRIVATE {#MODE-PRIVATE}
```
public static final int MODE_PRIVATE
```


### MODE_WORLD_READABLE {#MODE-WORLD-READABLE}
```
public static final int MODE_WORLD_READABLE
```


### MODE_WORLD_WRITEABLE {#MODE-WORLD-WRITEABLE}
```
public static final int MODE_WORLD_WRITEABLE
```


### NETWORK_STATS_SERVICE {#NETWORK-STATS-SERVICE}
```
public static final String NETWORK_STATS_SERVICE
```


### NFC_SERVICE {#NFC-SERVICE}
```
public static final String NFC_SERVICE
```


### NOTIFICATION_SERVICE {#NOTIFICATION-SERVICE}
```
public static final String NOTIFICATION_SERVICE
```


### NSD_SERVICE {#NSD-SERVICE}
```
public static final String NSD_SERVICE
```


### PEOPLE_SERVICE {#PEOPLE-SERVICE}
```
public static final String PEOPLE_SERVICE
```


### PERFORMANCE_HINT_SERVICE {#PERFORMANCE-HINT-SERVICE}
```
public static final String PERFORMANCE_HINT_SERVICE
```


### POWER_SERVICE {#POWER-SERVICE}
```
public static final String POWER_SERVICE
```


### PRINT_SERVICE {#PRINT-SERVICE}
```
public static final String PRINT_SERVICE
```


### RECEIVER_EXPORTED {#RECEIVER-EXPORTED}
```
public static final int RECEIVER_EXPORTED
```


### RECEIVER_NOT_EXPORTED {#RECEIVER-NOT-EXPORTED}
```
public static final int RECEIVER_NOT_EXPORTED
```


### RECEIVER_VISIBLE_TO_INSTANT_APPS {#RECEIVER-VISIBLE-TO-INSTANT-APPS}
```
public static final int RECEIVER_VISIBLE_TO_INSTANT_APPS
```


### RESTRICTIONS_SERVICE {#RESTRICTIONS-SERVICE}
```
public static final String RESTRICTIONS_SERVICE
```


### RESULT_CANCELED {#RESULT-CANCELED}
```
public static final int RESULT_CANCELED
```


### RESULT_FIRST_USER {#RESULT-FIRST-USER}
```
public static final int RESULT_FIRST_USER
```


### RESULT_OK {#RESULT-OK}
```
public static final int RESULT_OK
```


### ROLE_SERVICE {#ROLE-SERVICE}
```
public static final String ROLE_SERVICE
```


### SEARCH_SERVICE {#SEARCH-SERVICE}
```
public static final String SEARCH_SERVICE
```


### SENSOR_SERVICE {#SENSOR-SERVICE}
```
public static final String SENSOR_SERVICE
```


### SHORTCUT_SERVICE {#SHORTCUT-SERVICE}
```
public static final String SHORTCUT_SERVICE
```


### STATUS_BAR_SERVICE {#STATUS-BAR-SERVICE}
```
public static final String STATUS_BAR_SERVICE
```


### STORAGE_SERVICE {#STORAGE-SERVICE}
```
public static final String STORAGE_SERVICE
```


### STORAGE_STATS_SERVICE {#STORAGE-STATS-SERVICE}
```
public static final String STORAGE_STATS_SERVICE
```


### SYSTEM_HEALTH_SERVICE {#SYSTEM-HEALTH-SERVICE}
```
public static final String SYSTEM_HEALTH_SERVICE
```


### TELECOM_SERVICE {#TELECOM-SERVICE}
```
public static final String TELECOM_SERVICE
```


### TELEPHONY_IMS_SERVICE {#TELEPHONY-IMS-SERVICE}
```
public static final String TELEPHONY_IMS_SERVICE
```


### TELEPHONY_SERVICE {#TELEPHONY-SERVICE}
```
public static final String TELEPHONY_SERVICE
```


### TELEPHONY_SUBSCRIPTION_SERVICE {#TELEPHONY-SUBSCRIPTION-SERVICE}
```
public static final String TELEPHONY_SUBSCRIPTION_SERVICE
```


### TEXT_CLASSIFICATION_SERVICE {#TEXT-CLASSIFICATION-SERVICE}
```
public static final String TEXT_CLASSIFICATION_SERVICE
```


### TEXT_SERVICES_MANAGER_SERVICE {#TEXT-SERVICES-MANAGER-SERVICE}
```
public static final String TEXT_SERVICES_MANAGER_SERVICE
```


### TV_INPUT_SERVICE {#TV-INPUT-SERVICE}
```
public static final String TV_INPUT_SERVICE
```


### TV_INTERACTIVE_APP_SERVICE {#TV-INTERACTIVE-APP-SERVICE}
```
public static final String TV_INTERACTIVE_APP_SERVICE
```


### UI_MODE_SERVICE {#UI-MODE-SERVICE}
```
public static final String UI_MODE_SERVICE
```


### USAGE_STATS_SERVICE {#USAGE-STATS-SERVICE}
```
public static final String USAGE_STATS_SERVICE
```


### USB_SERVICE {#USB-SERVICE}
```
public static final String USB_SERVICE
```


### USER_SERVICE {#USER-SERVICE}
```
public static final String USER_SERVICE
```


### VIBRATOR_MANAGER_SERVICE {#VIBRATOR-MANAGER-SERVICE}
```
public static final String VIBRATOR_MANAGER_SERVICE
```


### VIBRATOR_SERVICE {#VIBRATOR-SERVICE}
```
public static final String VIBRATOR_SERVICE
```


### VPN_MANAGEMENT_SERVICE {#VPN-MANAGEMENT-SERVICE}
```
public static final String VPN_MANAGEMENT_SERVICE
```


### WALLPAPER_SERVICE {#WALLPAPER-SERVICE}
```
public static final String WALLPAPER_SERVICE
```


### WIFI_AWARE_SERVICE {#WIFI-AWARE-SERVICE}
```
public static final String WIFI_AWARE_SERVICE
```


### WIFI_P2P_SERVICE {#WIFI-P2P-SERVICE}
```
public static final String WIFI_P2P_SERVICE
```


### WIFI_RTT_RANGING_SERVICE {#WIFI-RTT-RANGING-SERVICE}
```
public static final String WIFI_RTT_RANGING_SERVICE
```


### WIFI_SERVICE {#WIFI-SERVICE}
```
public static final String WIFI_SERVICE
```


### WINDOW_SERVICE {#WINDOW-SERVICE}
```
public static final String WINDOW_SERVICE
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
### <T>findViewById(int arg0) {#-T-findViewById-int-}
```
public T <T>findViewById(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### <T>getExtraData(Class<T> arg0) {#-T-getExtraData-java.lang.Class-T--}
```
public T <T>getExtraData(Class<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |

**Returns:**
T
### <T>getSystemService(Class<T> arg0) {#-T-getSystemService-java.lang.Class-T--}
```
public final T <T>getSystemService(Class<T> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |

**Returns:**
T
### <T>requireViewById(int arg0) {#-T-requireViewById-int-}
```
public final T <T>requireViewById(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### addContentView(View arg0, ViewGroup.LayoutParams arg1) {#addContentView-android.view.View-android.view.ViewGroup.LayoutParams-}
```
public void addContentView(View arg0, ViewGroup.LayoutParams arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |
| arg1 | android.view.ViewGroup.LayoutParams |  |

### addMenuProvider(MenuProvider arg0) {#addMenuProvider-androidx.core.view.MenuProvider-}
```
public void addMenuProvider(MenuProvider arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.view.MenuProvider |  |

### addMenuProvider(MenuProvider arg0, LifecycleOwner arg1) {#addMenuProvider-androidx.core.view.MenuProvider-androidx.lifecycle.LifecycleOwner-}
```
public void addMenuProvider(MenuProvider arg0, LifecycleOwner arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.view.MenuProvider |  |
| arg1 | androidx.lifecycle.LifecycleOwner |  |

### addMenuProvider(MenuProvider arg0, LifecycleOwner arg1, Lifecycle.State arg2) {#addMenuProvider-androidx.core.view.MenuProvider-androidx.lifecycle.LifecycleOwner-androidx.lifecycle.Lifecycle.State-}
```
public void addMenuProvider(MenuProvider arg0, LifecycleOwner arg1, Lifecycle.State arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.view.MenuProvider |  |
| arg1 | androidx.lifecycle.LifecycleOwner |  |
| arg2 | androidx.lifecycle.Lifecycle.State |  |

### addOnConfigurationChangedListener(Consumer<Configuration> arg0) {#addOnConfigurationChangedListener-androidx.core.util.Consumer-android.content.res.Configuration--}
```
public final void addOnConfigurationChangedListener(Consumer<Configuration> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<android.content.res.Configuration> |  |

### addOnContextAvailableListener(OnContextAvailableListener arg0) {#addOnContextAvailableListener-androidx.activity.contextaware.OnContextAvailableListener-}
```
public final void addOnContextAvailableListener(OnContextAvailableListener arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.activity.contextaware.OnContextAvailableListener |  |

### addOnMultiWindowModeChangedListener(Consumer<MultiWindowModeChangedInfo> arg0) {#addOnMultiWindowModeChangedListener-androidx.core.util.Consumer-androidx.core.app.MultiWindowModeChangedInfo--}
```
public final void addOnMultiWindowModeChangedListener(Consumer<MultiWindowModeChangedInfo> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<androidx.core.app.MultiWindowModeChangedInfo> |  |

### addOnNewIntentListener(Consumer<Intent> arg0) {#addOnNewIntentListener-androidx.core.util.Consumer-android.content.Intent--}
```
public final void addOnNewIntentListener(Consumer<Intent> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<android.content.Intent> |  |

### addOnPictureInPictureModeChangedListener(Consumer<PictureInPictureModeChangedInfo> arg0) {#addOnPictureInPictureModeChangedListener-androidx.core.util.Consumer-androidx.core.app.PictureInPictureModeChangedInfo--}
```
public final void addOnPictureInPictureModeChangedListener(Consumer<PictureInPictureModeChangedInfo> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<androidx.core.app.PictureInPictureModeChangedInfo> |  |

### addOnTrimMemoryListener(Consumer<Integer> arg0) {#addOnTrimMemoryListener-androidx.core.util.Consumer-java.lang.Integer--}
```
public final void addOnTrimMemoryListener(Consumer<Integer> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<java.lang.Integer> |  |

### applyOverrideConfiguration(Configuration arg0) {#applyOverrideConfiguration-android.content.res.Configuration-}
```
public void applyOverrideConfiguration(Configuration arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.res.Configuration |  |

### bindIsolatedService(Intent arg0, int arg1, String arg2, Executor arg3, ServiceConnection arg4) {#bindIsolatedService-android.content.Intent-int-java.lang.String-java.util.concurrent.Executor-android.content.ServiceConnection-}
```
public boolean bindIsolatedService(Intent arg0, int arg1, String arg2, Executor arg3, ServiceConnection arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |
| arg2 | java.lang.String |  |
| arg3 | java.util.concurrent.Executor |  |
| arg4 | android.content.ServiceConnection |  |

**Returns:**
boolean
### bindService(Intent arg0, ServiceConnection arg1, int arg2) {#bindService-android.content.Intent-android.content.ServiceConnection-int-}
```
public boolean bindService(Intent arg0, ServiceConnection arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.content.ServiceConnection |  |
| arg2 | int |  |

**Returns:**
boolean
### bindService(Intent arg0, int arg1, Executor arg2, ServiceConnection arg3) {#bindService-android.content.Intent-int-java.util.concurrent.Executor-android.content.ServiceConnection-}
```
public boolean bindService(Intent arg0, int arg1, Executor arg2, ServiceConnection arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |
| arg2 | java.util.concurrent.Executor |  |
| arg3 | android.content.ServiceConnection |  |

**Returns:**
boolean
### bindServiceAsUser(Intent arg0, ServiceConnection arg1, int arg2, UserHandle arg3) {#bindServiceAsUser-android.content.Intent-android.content.ServiceConnection-int-android.os.UserHandle-}
```
public boolean bindServiceAsUser(Intent arg0, ServiceConnection arg1, int arg2, UserHandle arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.content.ServiceConnection |  |
| arg2 | int |  |
| arg3 | android.os.UserHandle |  |

**Returns:**
boolean
### checkCallingOrSelfPermission(String arg0) {#checkCallingOrSelfPermission-java.lang.String-}
```
public int checkCallingOrSelfPermission(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
int
### checkCallingOrSelfUriPermission(Uri arg0, int arg1) {#checkCallingOrSelfUriPermission-android.net.Uri-int-}
```
public int checkCallingOrSelfUriPermission(Uri arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |

**Returns:**
int
### checkCallingOrSelfUriPermissions(List<Uri> arg0, int arg1) {#checkCallingOrSelfUriPermissions-java.util.List-android.net.Uri--int-}
```
public int[] checkCallingOrSelfUriPermissions(List<Uri> arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.List<android.net.Uri> |  |
| arg1 | int |  |

**Returns:**
int[]
### checkCallingPermission(String arg0) {#checkCallingPermission-java.lang.String-}
```
public int checkCallingPermission(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
int
### checkCallingUriPermission(Uri arg0, int arg1) {#checkCallingUriPermission-android.net.Uri-int-}
```
public int checkCallingUriPermission(Uri arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |

**Returns:**
int
### checkCallingUriPermissions(List<Uri> arg0, int arg1) {#checkCallingUriPermissions-java.util.List-android.net.Uri--int-}
```
public int[] checkCallingUriPermissions(List<Uri> arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.List<android.net.Uri> |  |
| arg1 | int |  |

**Returns:**
int[]
### checkPermission(String arg0, int arg1, int arg2) {#checkPermission-java.lang.String-int-int-}
```
public int checkPermission(String arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |
| arg2 | int |  |

**Returns:**
int
### checkSelfPermission(String arg0) {#checkSelfPermission-java.lang.String-}
```
public int checkSelfPermission(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
int
### checkUriPermission(Uri arg0, int arg1, int arg2, int arg3) {#checkUriPermission-android.net.Uri-int-int-int-}
```
public int checkUriPermission(Uri arg0, int arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |

**Returns:**
int
### checkUriPermission(Uri arg0, String arg1, String arg2, int arg3, int arg4, int arg5) {#checkUriPermission-android.net.Uri-java.lang.String-java.lang.String-int-int-int-}
```
public int checkUriPermission(Uri arg0, String arg1, String arg2, int arg3, int arg4, int arg5)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.String |  |
| arg3 | int |  |
| arg4 | int |  |
| arg5 | int |  |

**Returns:**
int
### checkUriPermissions(List<Uri> arg0, int arg1, int arg2, int arg3) {#checkUriPermissions-java.util.List-android.net.Uri--int-int-int-}
```
public int[] checkUriPermissions(List<Uri> arg0, int arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.List<android.net.Uri> |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |

**Returns:**
int[]
### clearWallpaper() {#clearWallpaper--}
```
public void clearWallpaper()
```




### closeContextMenu() {#closeContextMenu--}
```
public void closeContextMenu()
```




### closeOptionsMenu() {#closeOptionsMenu--}
```
public void closeOptionsMenu()
```




### createAttributionContext(String arg0) {#createAttributionContext-java.lang.String-}
```
public Context createAttributionContext(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
android.content.Context
### createConfigurationContext(Configuration arg0) {#createConfigurationContext-android.content.res.Configuration-}
```
public Context createConfigurationContext(Configuration arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.res.Configuration |  |

**Returns:**
android.content.Context
### createContext(ContextParams arg0) {#createContext-android.content.ContextParams-}
```
public Context createContext(ContextParams arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.ContextParams |  |

**Returns:**
android.content.Context
### createContextForSplit(String arg0) {#createContextForSplit-java.lang.String-}
```
public Context createContextForSplit(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
android.content.Context
### createDeviceProtectedStorageContext() {#createDeviceProtectedStorageContext--}
```
public Context createDeviceProtectedStorageContext()
```




**Returns:**
android.content.Context
### createDisplayContext(Display arg0) {#createDisplayContext-android.view.Display-}
```
public Context createDisplayContext(Display arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Display |  |

**Returns:**
android.content.Context
### createPackageContext(String arg0, int arg1) {#createPackageContext-java.lang.String-int-}
```
public Context createPackageContext(String arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |

**Returns:**
android.content.Context
### createPendingResult(int arg0, Intent arg1, int arg2) {#createPendingResult-int-android.content.Intent-int-}
```
public PendingIntent createPendingResult(int arg0, Intent arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |

**Returns:**
android.app.PendingIntent
### createWindowContext(Display arg0, int arg1, Bundle arg2) {#createWindowContext-android.view.Display-int-android.os.Bundle-}
```
public Context createWindowContext(Display arg0, int arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Display |  |
| arg1 | int |  |
| arg2 | android.os.Bundle |  |

**Returns:**
android.content.Context
### createWindowContext(int arg0, Bundle arg1) {#createWindowContext-int-android.os.Bundle-}
```
public Context createWindowContext(int arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.os.Bundle |  |

**Returns:**
android.content.Context
### databaseList() {#databaseList--}
```
public String[] databaseList()
```




**Returns:**
java.lang.String[]
### deleteDatabase(String arg0) {#deleteDatabase-java.lang.String-}
```
public boolean deleteDatabase(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
boolean
### deleteFile(String arg0) {#deleteFile-java.lang.String-}
```
public boolean deleteFile(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
boolean
### deleteSharedPreferences(String arg0) {#deleteSharedPreferences-java.lang.String-}
```
public boolean deleteSharedPreferences(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
boolean
### dismissDialog(int arg0) {#dismissDialog-int-}
```
public final void dismissDialog(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### dismissKeyboardShortcutsHelper() {#dismissKeyboardShortcutsHelper--}
```
public final void dismissKeyboardShortcutsHelper()
```




### dispatchGenericMotionEvent(MotionEvent arg0) {#dispatchGenericMotionEvent-android.view.MotionEvent-}
```
public boolean dispatchGenericMotionEvent(MotionEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MotionEvent |  |

**Returns:**
boolean
### dispatchKeyEvent(KeyEvent arg0) {#dispatchKeyEvent-android.view.KeyEvent-}
```
public boolean dispatchKeyEvent(KeyEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.KeyEvent |  |

**Returns:**
boolean
### dispatchKeyShortcutEvent(KeyEvent arg0) {#dispatchKeyShortcutEvent-android.view.KeyEvent-}
```
public boolean dispatchKeyShortcutEvent(KeyEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.KeyEvent |  |

**Returns:**
boolean
### dispatchPopulateAccessibilityEvent(AccessibilityEvent arg0) {#dispatchPopulateAccessibilityEvent-android.view.accessibility.AccessibilityEvent-}
```
public boolean dispatchPopulateAccessibilityEvent(AccessibilityEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.accessibility.AccessibilityEvent |  |

**Returns:**
boolean
### dispatchTouchEvent(MotionEvent arg0) {#dispatchTouchEvent-android.view.MotionEvent-}
```
public boolean dispatchTouchEvent(MotionEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MotionEvent |  |

**Returns:**
boolean
### dispatchTrackballEvent(MotionEvent arg0) {#dispatchTrackballEvent-android.view.MotionEvent-}
```
public boolean dispatchTrackballEvent(MotionEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MotionEvent |  |

**Returns:**
boolean
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

### enforceCallingOrSelfPermission(String arg0, String arg1) {#enforceCallingOrSelfPermission-java.lang.String-java.lang.String-}
```
public void enforceCallingOrSelfPermission(String arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | java.lang.String |  |

### enforceCallingOrSelfUriPermission(Uri arg0, int arg1, String arg2) {#enforceCallingOrSelfUriPermission-android.net.Uri-int-java.lang.String-}
```
public void enforceCallingOrSelfUriPermission(Uri arg0, int arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |
| arg2 | java.lang.String |  |

### enforceCallingPermission(String arg0, String arg1) {#enforceCallingPermission-java.lang.String-java.lang.String-}
```
public void enforceCallingPermission(String arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | java.lang.String |  |

### enforceCallingUriPermission(Uri arg0, int arg1, String arg2) {#enforceCallingUriPermission-android.net.Uri-int-java.lang.String-}
```
public void enforceCallingUriPermission(Uri arg0, int arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |
| arg2 | java.lang.String |  |

### enforcePermission(String arg0, int arg1, int arg2, String arg3) {#enforcePermission-java.lang.String-int-int-java.lang.String-}
```
public void enforcePermission(String arg0, int arg1, int arg2, String arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | java.lang.String |  |

### enforceUriPermission(Uri arg0, int arg1, int arg2, int arg3, String arg4) {#enforceUriPermission-android.net.Uri-int-int-int-java.lang.String-}
```
public void enforceUriPermission(Uri arg0, int arg1, int arg2, int arg3, String arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | int |  |
| arg4 | java.lang.String |  |

### enforceUriPermission(Uri arg0, String arg1, String arg2, int arg3, int arg4, int arg5, String arg6) {#enforceUriPermission-android.net.Uri-java.lang.String-java.lang.String-int-int-int-java.lang.String-}
```
public void enforceUriPermission(Uri arg0, String arg1, String arg2, int arg3, int arg4, int arg5, String arg6)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.String |  |
| arg3 | int |  |
| arg4 | int |  |
| arg5 | int |  |
| arg6 | java.lang.String |  |

### enterPictureInPictureMode() {#enterPictureInPictureMode--}
```
public void enterPictureInPictureMode()
```




### enterPictureInPictureMode(PictureInPictureParams arg0) {#enterPictureInPictureMode-android.app.PictureInPictureParams-}
```
public boolean enterPictureInPictureMode(PictureInPictureParams arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.PictureInPictureParams |  |

**Returns:**
boolean
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
### fileList() {#fileList--}
```
public String[] fileList()
```




**Returns:**
java.lang.String[]
### finish() {#finish--}
```
public void finish()
```




### finishActivity(int arg0) {#finishActivity-int-}
```
public void finishActivity(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### finishActivityFromChild(Activity arg0, int arg1) {#finishActivityFromChild-android.app.Activity-int-}
```
public void finishActivityFromChild(Activity arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | int |  |

### finishAffinity() {#finishAffinity--}
```
public void finishAffinity()
```




### finishAfterTransition() {#finishAfterTransition--}
```
public void finishAfterTransition()
```




### finishAndRemoveTask() {#finishAndRemoveTask--}
```
public void finishAndRemoveTask()
```




### finishFromChild(Activity arg0) {#finishFromChild-android.app.Activity-}
```
public void finishFromChild(Activity arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |

### getActionBar() {#getActionBar--}
```
public ActionBar getActionBar()
```




**Returns:**
android.app.ActionBar
### getActivityResultRegistry() {#getActivityResultRegistry--}
```
public final ActivityResultRegistry getActivityResultRegistry()
```




**Returns:**
androidx.activity.result.ActivityResultRegistry
### getApplication() {#getApplication--}
```
public final Application getApplication()
```




**Returns:**
android.app.Application
### getApplicationContext() {#getApplicationContext--}
```
public Context getApplicationContext()
```




**Returns:**
android.content.Context
### getApplicationInfo() {#getApplicationInfo--}
```
public ApplicationInfo getApplicationInfo()
```




**Returns:**
android.content.pm.ApplicationInfo
### getAssets() {#getAssets--}
```
public AssetManager getAssets()
```




**Returns:**
android.content.res.AssetManager
### getAttributionSource() {#getAttributionSource--}
```
public AttributionSource getAttributionSource()
```




**Returns:**
android.content.AttributionSource
### getAttributionTag() {#getAttributionTag--}
```
public String getAttributionTag()
```




**Returns:**
java.lang.String
### getBaseContext() {#getBaseContext--}
```
public Context getBaseContext()
```




**Returns:**
android.content.Context
### getCacheDir() {#getCacheDir--}
```
public File getCacheDir()
```




**Returns:**
java.io.File
### getCallingActivity() {#getCallingActivity--}
```
public ComponentName getCallingActivity()
```




**Returns:**
android.content.ComponentName
### getCallingPackage() {#getCallingPackage--}
```
public String getCallingPackage()
```




**Returns:**
java.lang.String
### getChangingConfigurations() {#getChangingConfigurations--}
```
public int getChangingConfigurations()
```




**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassLoader() {#getClassLoader--}
```
public ClassLoader getClassLoader()
```




**Returns:**
java.lang.ClassLoader
### getCodeCacheDir() {#getCodeCacheDir--}
```
public File getCodeCacheDir()
```




**Returns:**
java.io.File
### getColor(int arg0) {#getColor-int-}
```
public final int getColor(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
int
### getColorStateList(int arg0) {#getColorStateList-int-}
```
public final ColorStateList getColorStateList(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
android.content.res.ColorStateList
### getComponentName() {#getComponentName--}
```
public ComponentName getComponentName()
```




**Returns:**
android.content.ComponentName
### getContentResolver() {#getContentResolver--}
```
public ContentResolver getContentResolver()
```




**Returns:**
android.content.ContentResolver
### getContentScene() {#getContentScene--}
```
public Scene getContentScene()
```




**Returns:**
android.transition.Scene
### getContentTransitionManager() {#getContentTransitionManager--}
```
public TransitionManager getContentTransitionManager()
```




**Returns:**
android.transition.TransitionManager
### getCurrentFocus() {#getCurrentFocus--}
```
public View getCurrentFocus()
```




**Returns:**
android.view.View
### getDataDir() {#getDataDir--}
```
public File getDataDir()
```




**Returns:**
java.io.File
### getDatabasePath(String arg0) {#getDatabasePath-java.lang.String-}
```
public File getDatabasePath(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.io.File
### getDefaultViewModelCreationExtras() {#getDefaultViewModelCreationExtras--}
```
public CreationExtras getDefaultViewModelCreationExtras()
```




**Returns:**
androidx.lifecycle.viewmodel.CreationExtras
### getDefaultViewModelProviderFactory() {#getDefaultViewModelProviderFactory--}
```
public ViewModelProvider.Factory getDefaultViewModelProviderFactory()
```




**Returns:**
androidx.lifecycle.ViewModelProvider.Factory
### getDelegate() {#getDelegate--}
```
public AppCompatDelegate getDelegate()
```




**Returns:**
androidx.appcompat.app.AppCompatDelegate
### getDir(String arg0, int arg1) {#getDir-java.lang.String-int-}
```
public File getDir(String arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |

**Returns:**
java.io.File
### getDisplay() {#getDisplay--}
```
public Display getDisplay()
```




**Returns:**
android.view.Display
### getDrawable(int arg0) {#getDrawable-int-}
```
public final Drawable getDrawable(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
android.graphics.drawable.Drawable
### getDrawerToggleDelegate() {#getDrawerToggleDelegate--}
```
public ActionBarDrawerToggle.Delegate getDrawerToggleDelegate()
```




**Returns:**
androidx.appcompat.app.ActionBarDrawerToggle.Delegate
### getExternalCacheDir() {#getExternalCacheDir--}
```
public File getExternalCacheDir()
```




**Returns:**
java.io.File
### getExternalCacheDirs() {#getExternalCacheDirs--}
```
public File[] getExternalCacheDirs()
```




**Returns:**
java.io.File[]
### getExternalFilesDir(String arg0) {#getExternalFilesDir-java.lang.String-}
```
public File getExternalFilesDir(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.io.File
### getExternalFilesDirs(String arg0) {#getExternalFilesDirs-java.lang.String-}
```
public File[] getExternalFilesDirs(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.io.File[]
### getExternalMediaDirs() {#getExternalMediaDirs--}
```
public File[] getExternalMediaDirs()
```




**Returns:**
java.io.File[]
### getFileStreamPath(String arg0) {#getFileStreamPath-java.lang.String-}
```
public File getFileStreamPath(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.io.File
### getFilesDir() {#getFilesDir--}
```
public File getFilesDir()
```




**Returns:**
java.io.File
### getFragmentManager() {#getFragmentManager--}
```
public FragmentManager getFragmentManager()
```




**Returns:**
android.app.FragmentManager
### getIntent() {#getIntent--}
```
public Intent getIntent()
```




**Returns:**
android.content.Intent
### getLastCustomNonConfigurationInstance() {#getLastCustomNonConfigurationInstance--}
```
public Object getLastCustomNonConfigurationInstance()
```




**Returns:**
java.lang.Object
### getLastNonConfigurationInstance() {#getLastNonConfigurationInstance--}
```
public Object getLastNonConfigurationInstance()
```




**Returns:**
java.lang.Object
### getLayoutInflater() {#getLayoutInflater--}
```
public LayoutInflater getLayoutInflater()
```




**Returns:**
android.view.LayoutInflater
### getLifecycle() {#getLifecycle--}
```
public Lifecycle getLifecycle()
```




**Returns:**
androidx.lifecycle.Lifecycle
### getLoaderManager() {#getLoaderManager--}
```
public LoaderManager getLoaderManager()
```




**Returns:**
android.app.LoaderManager
### getLocalClassName() {#getLocalClassName--}
```
public String getLocalClassName()
```




**Returns:**
java.lang.String
### getMainExecutor() {#getMainExecutor--}
```
public Executor getMainExecutor()
```




**Returns:**
java.util.concurrent.Executor
### getMainLooper() {#getMainLooper--}
```
public Looper getMainLooper()
```




**Returns:**
android.os.Looper
### getMaxNumPictureInPictureActions() {#getMaxNumPictureInPictureActions--}
```
public int getMaxNumPictureInPictureActions()
```




**Returns:**
int
### getMediaController() {#getMediaController--}
```
public final MediaController getMediaController()
```




**Returns:**
android.media.session.MediaController
### getMenuInflater() {#getMenuInflater--}
```
public MenuInflater getMenuInflater()
```




**Returns:**
android.view.MenuInflater
### getNoBackupFilesDir() {#getNoBackupFilesDir--}
```
public File getNoBackupFilesDir()
```




**Returns:**
java.io.File
### getObbDir() {#getObbDir--}
```
public File getObbDir()
```




**Returns:**
java.io.File
### getObbDirs() {#getObbDirs--}
```
public File[] getObbDirs()
```




**Returns:**
java.io.File[]
### getOnBackInvokedDispatcher() {#getOnBackInvokedDispatcher--}
```
public OnBackInvokedDispatcher getOnBackInvokedDispatcher()
```




**Returns:**
android.window.OnBackInvokedDispatcher
### getOnBackPressedDispatcher() {#getOnBackPressedDispatcher--}
```
public final OnBackPressedDispatcher getOnBackPressedDispatcher()
```




**Returns:**
androidx.activity.OnBackPressedDispatcher
### getOpPackageName() {#getOpPackageName--}
```
public String getOpPackageName()
```




**Returns:**
java.lang.String
### getPackageCodePath() {#getPackageCodePath--}
```
public String getPackageCodePath()
```




**Returns:**
java.lang.String
### getPackageManager() {#getPackageManager--}
```
public PackageManager getPackageManager()
```




**Returns:**
android.content.pm.PackageManager
### getPackageName() {#getPackageName--}
```
public String getPackageName()
```




**Returns:**
java.lang.String
### getPackageResourcePath() {#getPackageResourcePath--}
```
public String getPackageResourcePath()
```




**Returns:**
java.lang.String
### getParams() {#getParams--}
```
public ContextParams getParams()
```




**Returns:**
android.content.ContextParams
### getParent() {#getParent--}
```
public final Activity getParent()
```




**Returns:**
android.app.Activity
### getParentActivityIntent() {#getParentActivityIntent--}
```
public Intent getParentActivityIntent()
```




**Returns:**
android.content.Intent
### getPreferences(int arg0) {#getPreferences-int-}
```
public SharedPreferences getPreferences(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
android.content.SharedPreferences
### getReferrer() {#getReferrer--}
```
public Uri getReferrer()
```




**Returns:**
android.net.Uri
### getRequestedOrientation() {#getRequestedOrientation--}
```
public int getRequestedOrientation()
```




**Returns:**
int
### getResources() {#getResources--}
```
public Resources getResources()
```




**Returns:**
android.content.res.Resources
### getSavedStateRegistry() {#getSavedStateRegistry--}
```
public final SavedStateRegistry getSavedStateRegistry()
```




**Returns:**
androidx.savedstate.SavedStateRegistry
### getSearchEvent() {#getSearchEvent--}
```
public final SearchEvent getSearchEvent()
```




**Returns:**
android.view.SearchEvent
### getSharedPreferences(String arg0, int arg1) {#getSharedPreferences-java.lang.String-int-}
```
public SharedPreferences getSharedPreferences(String arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |

**Returns:**
android.content.SharedPreferences
### getSplashScreen() {#getSplashScreen--}
```
public final SplashScreen getSplashScreen()
```




**Returns:**
android.window.SplashScreen
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
### getSupportActionBar() {#getSupportActionBar--}
```
public ActionBar getSupportActionBar()
```




**Returns:**
androidx.appcompat.app.ActionBar
### getSupportFragmentManager() {#getSupportFragmentManager--}
```
public FragmentManager getSupportFragmentManager()
```




**Returns:**
androidx.fragment.app.FragmentManager
### getSupportLoaderManager() {#getSupportLoaderManager--}
```
public LoaderManager getSupportLoaderManager()
```




**Returns:**
androidx.loader.app.LoaderManager
### getSupportParentActivityIntent() {#getSupportParentActivityIntent--}
```
public Intent getSupportParentActivityIntent()
```




**Returns:**
android.content.Intent
### getSystemService(String arg0) {#getSystemService-java.lang.String-}
```
public Object getSystemService(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.lang.Object
### getSystemServiceName(Class<?> arg0) {#getSystemServiceName-java.lang.Class----}
```
public String getSystemServiceName(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.String
### getTaskId() {#getTaskId--}
```
public int getTaskId()
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
### getTheme() {#getTheme--}
```
public Resources.Theme getTheme()
```




**Returns:**
android.content.res.Resources.Theme
### getTitle() {#getTitle--}
```
public final CharSequence getTitle()
```




**Returns:**
java.lang.CharSequence
### getTitleColor() {#getTitleColor--}
```
public final int getTitleColor()
```




**Returns:**
int
### getViewModelStore() {#getViewModelStore--}
```
public ViewModelStore getViewModelStore()
```




**Returns:**
androidx.lifecycle.ViewModelStore
### getVoiceInteractor() {#getVoiceInteractor--}
```
public VoiceInteractor getVoiceInteractor()
```




**Returns:**
android.app.VoiceInteractor
### getVolumeControlStream() {#getVolumeControlStream--}
```
public final int getVolumeControlStream()
```




**Returns:**
int
### getWallpaper() {#getWallpaper--}
```
public Drawable getWallpaper()
```




**Returns:**
android.graphics.drawable.Drawable
### getWallpaperDesiredMinimumHeight() {#getWallpaperDesiredMinimumHeight--}
```
public int getWallpaperDesiredMinimumHeight()
```




**Returns:**
int
### getWallpaperDesiredMinimumWidth() {#getWallpaperDesiredMinimumWidth--}
```
public int getWallpaperDesiredMinimumWidth()
```




**Returns:**
int
### getWindow() {#getWindow--}
```
public Window getWindow()
```




**Returns:**
android.view.Window
### getWindowManager() {#getWindowManager--}
```
public WindowManager getWindowManager()
```




**Returns:**
android.view.WindowManager
### grantUriPermission(String arg0, Uri arg1, int arg2) {#grantUriPermission-java.lang.String-android.net.Uri-int-}
```
public void grantUriPermission(String arg0, Uri arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | android.net.Uri |  |
| arg2 | int |  |

### hasWindowFocus() {#hasWindowFocus--}
```
public boolean hasWindowFocus()
```




**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### invalidateMenu() {#invalidateMenu--}
```
public void invalidateMenu()
```




### invalidateOptionsMenu() {#invalidateOptionsMenu--}
```
public void invalidateOptionsMenu()
```




### isActivityTransitionRunning() {#isActivityTransitionRunning--}
```
public boolean isActivityTransitionRunning()
```




**Returns:**
boolean
### isChangingConfigurations() {#isChangingConfigurations--}
```
public boolean isChangingConfigurations()
```




**Returns:**
boolean
### isChild() {#isChild--}
```
public final boolean isChild()
```




**Returns:**
boolean
### isDestroyed() {#isDestroyed--}
```
public boolean isDestroyed()
```




**Returns:**
boolean
### isDeviceProtectedStorage() {#isDeviceProtectedStorage--}
```
public boolean isDeviceProtectedStorage()
```




**Returns:**
boolean
### isFinishing() {#isFinishing--}
```
public boolean isFinishing()
```




**Returns:**
boolean
### isImmersive() {#isImmersive--}
```
public boolean isImmersive()
```




**Returns:**
boolean
### isInMultiWindowMode() {#isInMultiWindowMode--}
```
public boolean isInMultiWindowMode()
```




**Returns:**
boolean
### isInPictureInPictureMode() {#isInPictureInPictureMode--}
```
public boolean isInPictureInPictureMode()
```




**Returns:**
boolean
### isLaunchedFromBubble() {#isLaunchedFromBubble--}
```
public boolean isLaunchedFromBubble()
```




**Returns:**
boolean
### isLocalVoiceInteractionSupported() {#isLocalVoiceInteractionSupported--}
```
public boolean isLocalVoiceInteractionSupported()
```




**Returns:**
boolean
### isRestricted() {#isRestricted--}
```
public boolean isRestricted()
```




**Returns:**
boolean
### isTaskRoot() {#isTaskRoot--}
```
public boolean isTaskRoot()
```




**Returns:**
boolean
### isUiContext() {#isUiContext--}
```
public boolean isUiContext()
```




**Returns:**
boolean
### isVoiceInteraction() {#isVoiceInteraction--}
```
public boolean isVoiceInteraction()
```




**Returns:**
boolean
### isVoiceInteractionRoot() {#isVoiceInteractionRoot--}
```
public boolean isVoiceInteractionRoot()
```




**Returns:**
boolean
### managedQuery(Uri arg0, String[] arg1, String arg2, String[] arg3, String arg4) {#managedQuery-android.net.Uri-java.lang.String---java.lang.String-java.lang.String---java.lang.String-}
```
public final Cursor managedQuery(Uri arg0, String[] arg1, String arg2, String[] arg3, String arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | java.lang.String[] |  |
| arg2 | java.lang.String |  |
| arg3 | java.lang.String[] |  |
| arg4 | java.lang.String |  |

**Returns:**
android.database.Cursor
### moveDatabaseFrom(Context arg0, String arg1) {#moveDatabaseFrom-android.content.Context-java.lang.String-}
```
public boolean moveDatabaseFrom(Context arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### moveSharedPreferencesFrom(Context arg0, String arg1) {#moveSharedPreferencesFrom-android.content.Context-java.lang.String-}
```
public boolean moveSharedPreferencesFrom(Context arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### moveTaskToBack(boolean arg0) {#moveTaskToBack-boolean-}
```
public boolean moveTaskToBack(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

**Returns:**
boolean
### navigateUpTo(Intent arg0) {#navigateUpTo-android.content.Intent-}
```
public boolean navigateUpTo(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
boolean
### navigateUpToFromChild(Activity arg0, Intent arg1) {#navigateUpToFromChild-android.app.Activity-android.content.Intent-}
```
public boolean navigateUpToFromChild(Activity arg0, Intent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | android.content.Intent |  |

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




### obtainStyledAttributes(AttributeSet arg0, int[] arg1) {#obtainStyledAttributes-android.util.AttributeSet-int---}
```
public final TypedArray obtainStyledAttributes(AttributeSet arg0, int[] arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.util.AttributeSet |  |
| arg1 | int[] |  |

**Returns:**
android.content.res.TypedArray
### obtainStyledAttributes(AttributeSet arg0, int[] arg1, int arg2, int arg3) {#obtainStyledAttributes-android.util.AttributeSet-int---int-int-}
```
public final TypedArray obtainStyledAttributes(AttributeSet arg0, int[] arg1, int arg2, int arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.util.AttributeSet |  |
| arg1 | int[] |  |
| arg2 | int |  |
| arg3 | int |  |

**Returns:**
android.content.res.TypedArray
### obtainStyledAttributes(int arg0, int[] arg1) {#obtainStyledAttributes-int-int---}
```
public final TypedArray obtainStyledAttributes(int arg0, int[] arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int[] |  |

**Returns:**
android.content.res.TypedArray
### obtainStyledAttributes(int[] arg0) {#obtainStyledAttributes-int---}
```
public final TypedArray obtainStyledAttributes(int[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int[] |  |

**Returns:**
android.content.res.TypedArray
### onActionModeFinished(ActionMode arg0) {#onActionModeFinished-android.view.ActionMode-}
```
public void onActionModeFinished(ActionMode arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ActionMode |  |

### onActionModeStarted(ActionMode arg0) {#onActionModeStarted-android.view.ActionMode-}
```
public void onActionModeStarted(ActionMode arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ActionMode |  |

### onActivityReenter(int arg0, Intent arg1) {#onActivityReenter-int-android.content.Intent-}
```
public void onActivityReenter(int arg0, Intent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.content.Intent |  |

### onAttachFragment(Fragment arg0) {#onAttachFragment-android.app.Fragment-}
```
public void onAttachFragment(Fragment arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Fragment |  |

### onAttachFragment(Fragment arg0) {#onAttachFragment-androidx.fragment.app.Fragment-}
```
public void onAttachFragment(Fragment arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment |  |

### onAttachedToWindow() {#onAttachedToWindow--}
```
public void onAttachedToWindow()
```




### onBackPressed() {#onBackPressed--}
```
public void onBackPressed()
```




### onConfigurationChanged(Configuration arg0) {#onConfigurationChanged-android.content.res.Configuration-}
```
public void onConfigurationChanged(Configuration arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.res.Configuration |  |

### onContentChanged() {#onContentChanged--}
```
public void onContentChanged()
```




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
### onContextMenuClosed(Menu arg0) {#onContextMenuClosed-android.view.Menu-}
```
public void onContextMenuClosed(Menu arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Menu |  |

### onCreate(Bundle arg0, PersistableBundle arg1) {#onCreate-android.os.Bundle-android.os.PersistableBundle-}
```
public void onCreate(Bundle arg0, PersistableBundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |
| arg1 | android.os.PersistableBundle |  |

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

### onCreateDescription() {#onCreateDescription--}
```
public CharSequence onCreateDescription()
```




**Returns:**
java.lang.CharSequence
### onCreateNavigateUpTaskStack(TaskStackBuilder arg0) {#onCreateNavigateUpTaskStack-android.app.TaskStackBuilder-}
```
public void onCreateNavigateUpTaskStack(TaskStackBuilder arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.TaskStackBuilder |  |

### onCreateOptionsMenu(Menu arg0) {#onCreateOptionsMenu-android.view.Menu-}
```
public boolean onCreateOptionsMenu(Menu arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Menu |  |

**Returns:**
boolean
### onCreatePanelMenu(int arg0, Menu arg1) {#onCreatePanelMenu-int-android.view.Menu-}
```
public boolean onCreatePanelMenu(int arg0, Menu arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.Menu |  |

**Returns:**
boolean
### onCreatePanelView(int arg0) {#onCreatePanelView-int-}
```
public View onCreatePanelView(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
android.view.View
### onCreateSupportNavigateUpTaskStack(TaskStackBuilder arg0) {#onCreateSupportNavigateUpTaskStack-androidx.core.app.TaskStackBuilder-}
```
public void onCreateSupportNavigateUpTaskStack(TaskStackBuilder arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.TaskStackBuilder |  |

### onCreateThumbnail(Bitmap arg0, Canvas arg1) {#onCreateThumbnail-android.graphics.Bitmap-android.graphics.Canvas-}
```
public boolean onCreateThumbnail(Bitmap arg0, Canvas arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.graphics.Bitmap |  |
| arg1 | android.graphics.Canvas |  |

**Returns:**
boolean
### onCreateView(View arg0, String arg1, Context arg2, AttributeSet arg3) {#onCreateView-android.view.View-java.lang.String-android.content.Context-android.util.AttributeSet-}
```
public View onCreateView(View arg0, String arg1, Context arg2, AttributeSet arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |
| arg1 | java.lang.String |  |
| arg2 | android.content.Context |  |
| arg3 | android.util.AttributeSet |  |

**Returns:**
android.view.View
### onCreateView(String arg0, Context arg1, AttributeSet arg2) {#onCreateView-java.lang.String-android.content.Context-android.util.AttributeSet-}
```
public View onCreateView(String arg0, Context arg1, AttributeSet arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | android.content.Context |  |
| arg2 | android.util.AttributeSet |  |

**Returns:**
android.view.View
### onDetachedFromWindow() {#onDetachedFromWindow--}
```
public void onDetachedFromWindow()
```




### onEnterAnimationComplete() {#onEnterAnimationComplete--}
```
public void onEnterAnimationComplete()
```




### onGenericMotionEvent(MotionEvent arg0) {#onGenericMotionEvent-android.view.MotionEvent-}
```
public boolean onGenericMotionEvent(MotionEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MotionEvent |  |

**Returns:**
boolean
### onGetDirectActions(CancellationSignal arg0, Consumer<List<DirectAction>> arg1) {#onGetDirectActions-android.os.CancellationSignal-java.util.function.Consumer-java.util.List-android.app.DirectAction---}
```
public void onGetDirectActions(CancellationSignal arg0, Consumer<List<DirectAction>> arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.CancellationSignal |  |
| arg1 | java.util.function.Consumer<java.util.List<android.app.DirectAction>> |  |

### onKeyDown(int arg0, KeyEvent arg1) {#onKeyDown-int-android.view.KeyEvent-}
```
public boolean onKeyDown(int arg0, KeyEvent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.KeyEvent |  |

**Returns:**
boolean
### onKeyLongPress(int arg0, KeyEvent arg1) {#onKeyLongPress-int-android.view.KeyEvent-}
```
public boolean onKeyLongPress(int arg0, KeyEvent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.KeyEvent |  |

**Returns:**
boolean
### onKeyMultiple(int arg0, int arg1, KeyEvent arg2) {#onKeyMultiple-int-int-android.view.KeyEvent-}
```
public boolean onKeyMultiple(int arg0, int arg1, KeyEvent arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | android.view.KeyEvent |  |

**Returns:**
boolean
### onKeyShortcut(int arg0, KeyEvent arg1) {#onKeyShortcut-int-android.view.KeyEvent-}
```
public boolean onKeyShortcut(int arg0, KeyEvent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.KeyEvent |  |

**Returns:**
boolean
### onKeyUp(int arg0, KeyEvent arg1) {#onKeyUp-int-android.view.KeyEvent-}
```
public boolean onKeyUp(int arg0, KeyEvent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.KeyEvent |  |

**Returns:**
boolean
### onLocalVoiceInteractionStarted() {#onLocalVoiceInteractionStarted--}
```
public void onLocalVoiceInteractionStarted()
```




### onLocalVoiceInteractionStopped() {#onLocalVoiceInteractionStopped--}
```
public void onLocalVoiceInteractionStopped()
```




### onLowMemory() {#onLowMemory--}
```
public void onLowMemory()
```




### onMenuItemSelected(int arg0, MenuItem arg1) {#onMenuItemSelected-int-android.view.MenuItem-}
```
public final boolean onMenuItemSelected(int arg0, MenuItem arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.MenuItem |  |

**Returns:**
boolean
### onMenuOpened(int arg0, Menu arg1) {#onMenuOpened-int-android.view.Menu-}
```
public boolean onMenuOpened(int arg0, Menu arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.Menu |  |

**Returns:**
boolean
### onMultiWindowModeChanged(boolean arg0) {#onMultiWindowModeChanged-boolean-}
```
public void onMultiWindowModeChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onMultiWindowModeChanged(boolean arg0, Configuration arg1) {#onMultiWindowModeChanged-boolean-android.content.res.Configuration-}
```
public void onMultiWindowModeChanged(boolean arg0, Configuration arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |
| arg1 | android.content.res.Configuration |  |

### onNavigateUp() {#onNavigateUp--}
```
public boolean onNavigateUp()
```




**Returns:**
boolean
### onNavigateUpFromChild(Activity arg0) {#onNavigateUpFromChild-android.app.Activity-}
```
public boolean onNavigateUpFromChild(Activity arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |

**Returns:**
boolean
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

### onPanelClosed(int arg0, Menu arg1) {#onPanelClosed-int-android.view.Menu-}
```
public void onPanelClosed(int arg0, Menu arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.Menu |  |

### onPerformDirectAction(String arg0, Bundle arg1, CancellationSignal arg2, Consumer<Bundle> arg3) {#onPerformDirectAction-java.lang.String-android.os.Bundle-android.os.CancellationSignal-java.util.function.Consumer-android.os.Bundle--}
```
public void onPerformDirectAction(String arg0, Bundle arg1, CancellationSignal arg2, Consumer<Bundle> arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | android.os.Bundle |  |
| arg2 | android.os.CancellationSignal |  |
| arg3 | java.util.function.Consumer<android.os.Bundle> |  |

### onPictureInPictureModeChanged(boolean arg0) {#onPictureInPictureModeChanged-boolean-}
```
public void onPictureInPictureModeChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onPictureInPictureModeChanged(boolean arg0, Configuration arg1) {#onPictureInPictureModeChanged-boolean-android.content.res.Configuration-}
```
public void onPictureInPictureModeChanged(boolean arg0, Configuration arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |
| arg1 | android.content.res.Configuration |  |

### onPictureInPictureRequested() {#onPictureInPictureRequested--}
```
public boolean onPictureInPictureRequested()
```




**Returns:**
boolean
### onPictureInPictureUiStateChanged(PictureInPictureUiState arg0) {#onPictureInPictureUiStateChanged-android.app.PictureInPictureUiState-}
```
public void onPictureInPictureUiStateChanged(PictureInPictureUiState arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.PictureInPictureUiState |  |

### onPostCreate(Bundle arg0, PersistableBundle arg1) {#onPostCreate-android.os.Bundle-android.os.PersistableBundle-}
```
public void onPostCreate(Bundle arg0, PersistableBundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |
| arg1 | android.os.PersistableBundle |  |

### onPrepareNavigateUpTaskStack(TaskStackBuilder arg0) {#onPrepareNavigateUpTaskStack-android.app.TaskStackBuilder-}
```
public void onPrepareNavigateUpTaskStack(TaskStackBuilder arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.TaskStackBuilder |  |

### onPrepareOptionsMenu(Menu arg0) {#onPrepareOptionsMenu-android.view.Menu-}
```
public boolean onPrepareOptionsMenu(Menu arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.Menu |  |

**Returns:**
boolean
### onPreparePanel(int arg0, View arg1, Menu arg2) {#onPreparePanel-int-android.view.View-android.view.Menu-}
```
public boolean onPreparePanel(int arg0, View arg1, Menu arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.view.View |  |
| arg2 | android.view.Menu |  |

**Returns:**
boolean
### onPrepareSupportNavigateUpTaskStack(TaskStackBuilder arg0) {#onPrepareSupportNavigateUpTaskStack-androidx.core.app.TaskStackBuilder-}
```
public void onPrepareSupportNavigateUpTaskStack(TaskStackBuilder arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.TaskStackBuilder |  |

### onProvideAssistContent(AssistContent arg0) {#onProvideAssistContent-android.app.assist.AssistContent-}
```
public void onProvideAssistContent(AssistContent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.assist.AssistContent |  |

### onProvideAssistData(Bundle arg0) {#onProvideAssistData-android.os.Bundle-}
```
public void onProvideAssistData(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

### onProvideKeyboardShortcuts(List<KeyboardShortcutGroup> arg0, Menu arg1, int arg2) {#onProvideKeyboardShortcuts-java.util.List-android.view.KeyboardShortcutGroup--android.view.Menu-int-}
```
public void onProvideKeyboardShortcuts(List<KeyboardShortcutGroup> arg0, Menu arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.List<android.view.KeyboardShortcutGroup> |  |
| arg1 | android.view.Menu |  |
| arg2 | int |  |

### onProvideReferrer() {#onProvideReferrer--}
```
public Uri onProvideReferrer()
```




**Returns:**
android.net.Uri
### onRequestPermissionsResult(int requestCode, String[] permissions, int[] grantResults) {#onRequestPermissionsResult-int-java.lang.String---int---}
```
public void onRequestPermissionsResult(int requestCode, String[] permissions, int[] grantResults)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| requestCode | int |  |
| permissions | java.lang.String[] |  |
| grantResults | int[] |  |

### onRestoreInstanceState(Bundle arg0, PersistableBundle arg1) {#onRestoreInstanceState-android.os.Bundle-android.os.PersistableBundle-}
```
public void onRestoreInstanceState(Bundle arg0, PersistableBundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |
| arg1 | android.os.PersistableBundle |  |

### onRetainCustomNonConfigurationInstance() {#onRetainCustomNonConfigurationInstance--}
```
public Object onRetainCustomNonConfigurationInstance()
```




**Returns:**
java.lang.Object
### onRetainNonConfigurationInstance() {#onRetainNonConfigurationInstance--}
```
public final Object onRetainNonConfigurationInstance()
```




**Returns:**
java.lang.Object
### onSaveInstanceState(Bundle arg0, PersistableBundle arg1) {#onSaveInstanceState-android.os.Bundle-android.os.PersistableBundle-}
```
public void onSaveInstanceState(Bundle arg0, PersistableBundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |
| arg1 | android.os.PersistableBundle |  |

### onSearchRequested() {#onSearchRequested--}
```
public boolean onSearchRequested()
```




**Returns:**
boolean
### onSearchRequested(SearchEvent arg0) {#onSearchRequested-android.view.SearchEvent-}
```
public boolean onSearchRequested(SearchEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.SearchEvent |  |

**Returns:**
boolean
### onStateNotSaved() {#onStateNotSaved--}
```
public void onStateNotSaved()
```




### onSupportActionModeFinished(ActionMode arg0) {#onSupportActionModeFinished-androidx.appcompat.view.ActionMode-}
```
public void onSupportActionModeFinished(ActionMode arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.appcompat.view.ActionMode |  |

### onSupportActionModeStarted(ActionMode arg0) {#onSupportActionModeStarted-androidx.appcompat.view.ActionMode-}
```
public void onSupportActionModeStarted(ActionMode arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.appcompat.view.ActionMode |  |

### onSupportContentChanged() {#onSupportContentChanged--}
```
public void onSupportContentChanged()
```




### onSupportNavigateUp() {#onSupportNavigateUp--}
```
public boolean onSupportNavigateUp()
```




**Returns:**
boolean
### onTopResumedActivityChanged(boolean arg0) {#onTopResumedActivityChanged-boolean-}
```
public void onTopResumedActivityChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onTouchEvent(MotionEvent arg0) {#onTouchEvent-android.view.MotionEvent-}
```
public boolean onTouchEvent(MotionEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MotionEvent |  |

**Returns:**
boolean
### onTrackballEvent(MotionEvent arg0) {#onTrackballEvent-android.view.MotionEvent-}
```
public boolean onTrackballEvent(MotionEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.MotionEvent |  |

**Returns:**
boolean
### onTrimMemory(int arg0) {#onTrimMemory-int-}
```
public void onTrimMemory(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### onUserInteraction() {#onUserInteraction--}
```
public void onUserInteraction()
```




### onVisibleBehindCanceled() {#onVisibleBehindCanceled--}
```
public void onVisibleBehindCanceled()
```




### onWindowAttributesChanged(WindowManager.LayoutParams arg0) {#onWindowAttributesChanged-android.view.WindowManager.LayoutParams-}
```
public void onWindowAttributesChanged(WindowManager.LayoutParams arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.WindowManager.LayoutParams |  |

### onWindowFocusChanged(boolean arg0) {#onWindowFocusChanged-boolean-}
```
public void onWindowFocusChanged(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### onWindowStartingActionMode(ActionMode.Callback arg0) {#onWindowStartingActionMode-android.view.ActionMode.Callback-}
```
public ActionMode onWindowStartingActionMode(ActionMode.Callback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ActionMode.Callback |  |

**Returns:**
android.view.ActionMode
### onWindowStartingActionMode(ActionMode.Callback arg0, int arg1) {#onWindowStartingActionMode-android.view.ActionMode.Callback-int-}
```
public ActionMode onWindowStartingActionMode(ActionMode.Callback arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ActionMode.Callback |  |
| arg1 | int |  |

**Returns:**
android.view.ActionMode
### onWindowStartingSupportActionMode(ActionMode.Callback arg0) {#onWindowStartingSupportActionMode-androidx.appcompat.view.ActionMode.Callback-}
```
public ActionMode onWindowStartingSupportActionMode(ActionMode.Callback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.appcompat.view.ActionMode.Callback |  |

**Returns:**
androidx.appcompat.view.ActionMode
### openContextMenu(View arg0) {#openContextMenu-android.view.View-}
```
public void openContextMenu(View arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |

### openFileInput(String arg0) {#openFileInput-java.lang.String-}
```
public FileInputStream openFileInput(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
java.io.FileInputStream
### openFileOutput(String arg0, int arg1) {#openFileOutput-java.lang.String-int-}
```
public FileOutputStream openFileOutput(String arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |

**Returns:**
java.io.FileOutputStream
### openOptionsMenu() {#openOptionsMenu--}
```
public void openOptionsMenu()
```




### openOrCreateDatabase(String arg0, int arg1, SQLiteDatabase.CursorFactory arg2) {#openOrCreateDatabase-java.lang.String-int-android.database.sqlite.SQLiteDatabase.CursorFactory-}
```
public SQLiteDatabase openOrCreateDatabase(String arg0, int arg1, SQLiteDatabase.CursorFactory arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |
| arg2 | android.database.sqlite.SQLiteDatabase.CursorFactory |  |

**Returns:**
android.database.sqlite.SQLiteDatabase
### openOrCreateDatabase(String arg0, int arg1, SQLiteDatabase.CursorFactory arg2, DatabaseErrorHandler arg3) {#openOrCreateDatabase-java.lang.String-int-android.database.sqlite.SQLiteDatabase.CursorFactory-android.database.DatabaseErrorHandler-}
```
public SQLiteDatabase openOrCreateDatabase(String arg0, int arg1, SQLiteDatabase.CursorFactory arg2, DatabaseErrorHandler arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | int |  |
| arg2 | android.database.sqlite.SQLiteDatabase.CursorFactory |  |
| arg3 | android.database.DatabaseErrorHandler |  |

**Returns:**
android.database.sqlite.SQLiteDatabase
### overridePendingTransition(int arg0, int arg1) {#overridePendingTransition-int-int-}
```
public void overridePendingTransition(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### overridePendingTransition(int arg0, int arg1, int arg2) {#overridePendingTransition-int-int-int-}
```
public void overridePendingTransition(int arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |
| arg2 | int |  |

### peekAvailableContext() {#peekAvailableContext--}
```
public Context peekAvailableContext()
```




**Returns:**
android.content.Context
### peekWallpaper() {#peekWallpaper--}
```
public Drawable peekWallpaper()
```




**Returns:**
android.graphics.drawable.Drawable
### postponeEnterTransition() {#postponeEnterTransition--}
```
public void postponeEnterTransition()
```




### putExtraData(ComponentActivity.ExtraData arg0) {#putExtraData-androidx.core.app.ComponentActivity.ExtraData-}
```
public void putExtraData(ComponentActivity.ExtraData arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.ComponentActivity.ExtraData |  |

### recreate() {#recreate--}
```
public void recreate()
```




### registerActivityLifecycleCallbacks(Application.ActivityLifecycleCallbacks arg0) {#registerActivityLifecycleCallbacks-android.app.Application.ActivityLifecycleCallbacks-}
```
public void registerActivityLifecycleCallbacks(Application.ActivityLifecycleCallbacks arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Application.ActivityLifecycleCallbacks |  |

### registerComponentCallbacks(ComponentCallbacks arg0) {#registerComponentCallbacks-android.content.ComponentCallbacks-}
```
public void registerComponentCallbacks(ComponentCallbacks arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.ComponentCallbacks |  |

### registerForContextMenu(View arg0) {#registerForContextMenu-android.view.View-}
```
public void registerForContextMenu(View arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |

### registerReceiver(BroadcastReceiver arg0, IntentFilter arg1) {#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-}
```
public Intent registerReceiver(BroadcastReceiver arg0, IntentFilter arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.BroadcastReceiver |  |
| arg1 | android.content.IntentFilter |  |

**Returns:**
android.content.Intent
### registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, int arg2) {#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-int-}
```
public Intent registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.BroadcastReceiver |  |
| arg1 | android.content.IntentFilter |  |
| arg2 | int |  |

**Returns:**
android.content.Intent
### registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, String arg2, Handler arg3) {#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-java.lang.String-android.os.Handler-}
```
public Intent registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, String arg2, Handler arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.BroadcastReceiver |  |
| arg1 | android.content.IntentFilter |  |
| arg2 | java.lang.String |  |
| arg3 | android.os.Handler |  |

**Returns:**
android.content.Intent
### registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, String arg2, Handler arg3, int arg4) {#registerReceiver-android.content.BroadcastReceiver-android.content.IntentFilter-java.lang.String-android.os.Handler-int-}
```
public Intent registerReceiver(BroadcastReceiver arg0, IntentFilter arg1, String arg2, Handler arg3, int arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.BroadcastReceiver |  |
| arg1 | android.content.IntentFilter |  |
| arg2 | java.lang.String |  |
| arg3 | android.os.Handler |  |
| arg4 | int |  |

**Returns:**
android.content.Intent
### releaseInstance() {#releaseInstance--}
```
public boolean releaseInstance()
```




**Returns:**
boolean
### removeDialog(int arg0) {#removeDialog-int-}
```
public final void removeDialog(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### removeMenuProvider(MenuProvider arg0) {#removeMenuProvider-androidx.core.view.MenuProvider-}
```
public void removeMenuProvider(MenuProvider arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.view.MenuProvider |  |

### removeOnConfigurationChangedListener(Consumer<Configuration> arg0) {#removeOnConfigurationChangedListener-androidx.core.util.Consumer-android.content.res.Configuration--}
```
public final void removeOnConfigurationChangedListener(Consumer<Configuration> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<android.content.res.Configuration> |  |

### removeOnContextAvailableListener(OnContextAvailableListener arg0) {#removeOnContextAvailableListener-androidx.activity.contextaware.OnContextAvailableListener-}
```
public final void removeOnContextAvailableListener(OnContextAvailableListener arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.activity.contextaware.OnContextAvailableListener |  |

### removeOnMultiWindowModeChangedListener(Consumer<MultiWindowModeChangedInfo> arg0) {#removeOnMultiWindowModeChangedListener-androidx.core.util.Consumer-androidx.core.app.MultiWindowModeChangedInfo--}
```
public final void removeOnMultiWindowModeChangedListener(Consumer<MultiWindowModeChangedInfo> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<androidx.core.app.MultiWindowModeChangedInfo> |  |

### removeOnNewIntentListener(Consumer<Intent> arg0) {#removeOnNewIntentListener-androidx.core.util.Consumer-android.content.Intent--}
```
public final void removeOnNewIntentListener(Consumer<Intent> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<android.content.Intent> |  |

### removeOnPictureInPictureModeChangedListener(Consumer<PictureInPictureModeChangedInfo> arg0) {#removeOnPictureInPictureModeChangedListener-androidx.core.util.Consumer-androidx.core.app.PictureInPictureModeChangedInfo--}
```
public final void removeOnPictureInPictureModeChangedListener(Consumer<PictureInPictureModeChangedInfo> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<androidx.core.app.PictureInPictureModeChangedInfo> |  |

### removeOnTrimMemoryListener(Consumer<Integer> arg0) {#removeOnTrimMemoryListener-androidx.core.util.Consumer-java.lang.Integer--}
```
public final void removeOnTrimMemoryListener(Consumer<Integer> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.util.Consumer<java.lang.Integer> |  |

### removeStickyBroadcast(Intent arg0) {#removeStickyBroadcast-android.content.Intent-}
```
public void removeStickyBroadcast(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

### removeStickyBroadcastAsUser(Intent arg0, UserHandle arg1) {#removeStickyBroadcastAsUser-android.content.Intent-android.os.UserHandle-}
```
public void removeStickyBroadcastAsUser(Intent arg0, UserHandle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.UserHandle |  |

### reportFullyDrawn() {#reportFullyDrawn--}
```
public void reportFullyDrawn()
```




### requestDragAndDropPermissions(DragEvent arg0) {#requestDragAndDropPermissions-android.view.DragEvent-}
```
public DragAndDropPermissions requestDragAndDropPermissions(DragEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.DragEvent |  |

**Returns:**
android.view.DragAndDropPermissions
### requestPermissions(String[] arg0, int arg1) {#requestPermissions-java.lang.String---int-}
```
public final void requestPermissions(String[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String[] |  |
| arg1 | int |  |

### requestShowKeyboardShortcuts() {#requestShowKeyboardShortcuts--}
```
public final void requestShowKeyboardShortcuts()
```




### requestVisibleBehind(boolean arg0) {#requestVisibleBehind-boolean-}
```
public boolean requestVisibleBehind(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

**Returns:**
boolean
### requestWindowFeature(int arg0) {#requestWindowFeature-int-}
```
public final boolean requestWindowFeature(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
boolean
### revokeSelfPermissionOnKill(String arg0) {#revokeSelfPermissionOnKill-java.lang.String-}
```
public void revokeSelfPermissionOnKill(String arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

### revokeSelfPermissionsOnKill(Collection<String> arg0) {#revokeSelfPermissionsOnKill-java.util.Collection-java.lang.String--}
```
public void revokeSelfPermissionsOnKill(Collection<String> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.util.Collection<java.lang.String> |  |

### revokeUriPermission(Uri arg0, int arg1) {#revokeUriPermission-android.net.Uri-int-}
```
public void revokeUriPermission(Uri arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.net.Uri |  |
| arg1 | int |  |

### revokeUriPermission(String arg0, Uri arg1, int arg2) {#revokeUriPermission-java.lang.String-android.net.Uri-int-}
```
public void revokeUriPermission(String arg0, Uri arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | android.net.Uri |  |
| arg2 | int |  |

### runOnUiThread(Runnable arg0) {#runOnUiThread-java.lang.Runnable-}
```
public final void runOnUiThread(Runnable arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Runnable |  |

### sendBroadcast(Intent arg0) {#sendBroadcast-android.content.Intent-}
```
public void sendBroadcast(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

### sendBroadcast(Intent arg0, String arg1) {#sendBroadcast-android.content.Intent-java.lang.String-}
```
public void sendBroadcast(Intent arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | java.lang.String |  |

### sendBroadcastAsUser(Intent arg0, UserHandle arg1) {#sendBroadcastAsUser-android.content.Intent-android.os.UserHandle-}
```
public void sendBroadcastAsUser(Intent arg0, UserHandle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.UserHandle |  |

### sendBroadcastAsUser(Intent arg0, UserHandle arg1, String arg2) {#sendBroadcastAsUser-android.content.Intent-android.os.UserHandle-java.lang.String-}
```
public void sendBroadcastAsUser(Intent arg0, UserHandle arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.UserHandle |  |
| arg2 | java.lang.String |  |

### sendBroadcastWithMultiplePermissions(Intent arg0, String[] arg1) {#sendBroadcastWithMultiplePermissions-android.content.Intent-java.lang.String---}
```
public void sendBroadcastWithMultiplePermissions(Intent arg0, String[] arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | java.lang.String[] |  |

### sendOrderedBroadcast(Intent arg0, int arg1, String arg2, String arg3, BroadcastReceiver arg4, Handler arg5, String arg6, Bundle arg7, Bundle arg8) {#sendOrderedBroadcast-android.content.Intent-int-java.lang.String-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-java.lang.String-android.os.Bundle-android.os.Bundle-}
```
public void sendOrderedBroadcast(Intent arg0, int arg1, String arg2, String arg3, BroadcastReceiver arg4, Handler arg5, String arg6, Bundle arg7, Bundle arg8)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |
| arg2 | java.lang.String |  |
| arg3 | java.lang.String |  |
| arg4 | android.content.BroadcastReceiver |  |
| arg5 | android.os.Handler |  |
| arg6 | java.lang.String |  |
| arg7 | android.os.Bundle |  |
| arg8 | android.os.Bundle |  |

### sendOrderedBroadcast(Intent arg0, String arg1) {#sendOrderedBroadcast-android.content.Intent-java.lang.String-}
```
public void sendOrderedBroadcast(Intent arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | java.lang.String |  |

### sendOrderedBroadcast(Intent arg0, String arg1, BroadcastReceiver arg2, Handler arg3, int arg4, String arg5, Bundle arg6) {#sendOrderedBroadcast-android.content.Intent-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-}
```
public void sendOrderedBroadcast(Intent arg0, String arg1, BroadcastReceiver arg2, Handler arg3, int arg4, String arg5, Bundle arg6)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | java.lang.String |  |
| arg2 | android.content.BroadcastReceiver |  |
| arg3 | android.os.Handler |  |
| arg4 | int |  |
| arg5 | java.lang.String |  |
| arg6 | android.os.Bundle |  |

### sendOrderedBroadcast(Intent arg0, String arg1, String arg2, BroadcastReceiver arg3, Handler arg4, int arg5, String arg6, Bundle arg7) {#sendOrderedBroadcast-android.content.Intent-java.lang.String-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-}
```
public void sendOrderedBroadcast(Intent arg0, String arg1, String arg2, BroadcastReceiver arg3, Handler arg4, int arg5, String arg6, Bundle arg7)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.String |  |
| arg3 | android.content.BroadcastReceiver |  |
| arg4 | android.os.Handler |  |
| arg5 | int |  |
| arg6 | java.lang.String |  |
| arg7 | android.os.Bundle |  |

### sendOrderedBroadcastAsUser(Intent arg0, UserHandle arg1, String arg2, BroadcastReceiver arg3, Handler arg4, int arg5, String arg6, Bundle arg7) {#sendOrderedBroadcastAsUser-android.content.Intent-android.os.UserHandle-java.lang.String-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-}
```
public void sendOrderedBroadcastAsUser(Intent arg0, UserHandle arg1, String arg2, BroadcastReceiver arg3, Handler arg4, int arg5, String arg6, Bundle arg7)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.UserHandle |  |
| arg2 | java.lang.String |  |
| arg3 | android.content.BroadcastReceiver |  |
| arg4 | android.os.Handler |  |
| arg5 | int |  |
| arg6 | java.lang.String |  |
| arg7 | android.os.Bundle |  |

### sendStickyBroadcast(Intent arg0) {#sendStickyBroadcast-android.content.Intent-}
```
public void sendStickyBroadcast(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

### sendStickyBroadcast(Intent arg0, Bundle arg1) {#sendStickyBroadcast-android.content.Intent-android.os.Bundle-}
```
public void sendStickyBroadcast(Intent arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.Bundle |  |

### sendStickyBroadcastAsUser(Intent arg0, UserHandle arg1) {#sendStickyBroadcastAsUser-android.content.Intent-android.os.UserHandle-}
```
public void sendStickyBroadcastAsUser(Intent arg0, UserHandle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.UserHandle |  |

### sendStickyOrderedBroadcast(Intent arg0, BroadcastReceiver arg1, Handler arg2, int arg3, String arg4, Bundle arg5) {#sendStickyOrderedBroadcast-android.content.Intent-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-}
```
public void sendStickyOrderedBroadcast(Intent arg0, BroadcastReceiver arg1, Handler arg2, int arg3, String arg4, Bundle arg5)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.content.BroadcastReceiver |  |
| arg2 | android.os.Handler |  |
| arg3 | int |  |
| arg4 | java.lang.String |  |
| arg5 | android.os.Bundle |  |

### sendStickyOrderedBroadcastAsUser(Intent arg0, UserHandle arg1, BroadcastReceiver arg2, Handler arg3, int arg4, String arg5, Bundle arg6) {#sendStickyOrderedBroadcastAsUser-android.content.Intent-android.os.UserHandle-android.content.BroadcastReceiver-android.os.Handler-int-java.lang.String-android.os.Bundle-}
```
public void sendStickyOrderedBroadcastAsUser(Intent arg0, UserHandle arg1, BroadcastReceiver arg2, Handler arg3, int arg4, String arg5, Bundle arg6)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.UserHandle |  |
| arg2 | android.content.BroadcastReceiver |  |
| arg3 | android.os.Handler |  |
| arg4 | int |  |
| arg5 | java.lang.String |  |
| arg6 | android.os.Bundle |  |

### setActionBar(Toolbar arg0) {#setActionBar-android.widget.Toolbar-}
```
public void setActionBar(Toolbar arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.widget.Toolbar |  |

### setContentTransitionManager(TransitionManager arg0) {#setContentTransitionManager-android.transition.TransitionManager-}
```
public void setContentTransitionManager(TransitionManager arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.transition.TransitionManager |  |

### setContentView(View arg0) {#setContentView-android.view.View-}
```
public void setContentView(View arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |

### setContentView(View arg0, ViewGroup.LayoutParams arg1) {#setContentView-android.view.View-android.view.ViewGroup.LayoutParams-}
```
public void setContentView(View arg0, ViewGroup.LayoutParams arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |
| arg1 | android.view.ViewGroup.LayoutParams |  |

### setContentView(int arg0) {#setContentView-int-}
```
public void setContentView(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setDefaultKeyMode(int arg0) {#setDefaultKeyMode-int-}
```
public final void setDefaultKeyMode(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setEnterSharedElementCallback(SharedElementCallback arg0) {#setEnterSharedElementCallback-android.app.SharedElementCallback-}
```
public void setEnterSharedElementCallback(SharedElementCallback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.SharedElementCallback |  |

### setEnterSharedElementCallback(SharedElementCallback arg0) {#setEnterSharedElementCallback-androidx.core.app.SharedElementCallback-}
```
public void setEnterSharedElementCallback(SharedElementCallback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.SharedElementCallback |  |

### setExitSharedElementCallback(SharedElementCallback arg0) {#setExitSharedElementCallback-android.app.SharedElementCallback-}
```
public void setExitSharedElementCallback(SharedElementCallback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.SharedElementCallback |  |

### setExitSharedElementCallback(SharedElementCallback arg0) {#setExitSharedElementCallback-androidx.core.app.SharedElementCallback-}
```
public void setExitSharedElementCallback(SharedElementCallback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.core.app.SharedElementCallback |  |

### setFeatureDrawable(int arg0, Drawable arg1) {#setFeatureDrawable-int-android.graphics.drawable.Drawable-}
```
public final void setFeatureDrawable(int arg0, Drawable arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.graphics.drawable.Drawable |  |

### setFeatureDrawableAlpha(int arg0, int arg1) {#setFeatureDrawableAlpha-int-int-}
```
public final void setFeatureDrawableAlpha(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### setFeatureDrawableResource(int arg0, int arg1) {#setFeatureDrawableResource-int-int-}
```
public final void setFeatureDrawableResource(int arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | int |  |

### setFeatureDrawableUri(int arg0, Uri arg1) {#setFeatureDrawableUri-int-android.net.Uri-}
```
public final void setFeatureDrawableUri(int arg0, Uri arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.net.Uri |  |

### setFinishOnTouchOutside(boolean arg0) {#setFinishOnTouchOutside-boolean-}
```
public void setFinishOnTouchOutside(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setImmersive(boolean arg0) {#setImmersive-boolean-}
```
public void setImmersive(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setInheritShowWhenLocked(boolean arg0) {#setInheritShowWhenLocked-boolean-}
```
public void setInheritShowWhenLocked(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setIntent(Intent arg0) {#setIntent-android.content.Intent-}
```
public void setIntent(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

### setLocusContext(LocusId arg0, Bundle arg1) {#setLocusContext-android.content.LocusId-android.os.Bundle-}
```
public void setLocusContext(LocusId arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.LocusId |  |
| arg1 | android.os.Bundle |  |

### setMediaController(MediaController arg0) {#setMediaController-android.media.session.MediaController-}
```
public final void setMediaController(MediaController arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.media.session.MediaController |  |

### setPictureInPictureParams(PictureInPictureParams arg0) {#setPictureInPictureParams-android.app.PictureInPictureParams-}
```
public void setPictureInPictureParams(PictureInPictureParams arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.PictureInPictureParams |  |

### setProgress(int arg0) {#setProgress-int-}
```
public final void setProgress(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setProgressBarIndeterminate(boolean arg0) {#setProgressBarIndeterminate-boolean-}
```
public final void setProgressBarIndeterminate(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setProgressBarIndeterminateVisibility(boolean arg0) {#setProgressBarIndeterminateVisibility-boolean-}
```
public final void setProgressBarIndeterminateVisibility(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setProgressBarVisibility(boolean arg0) {#setProgressBarVisibility-boolean-}
```
public final void setProgressBarVisibility(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setRecentsScreenshotEnabled(boolean arg0) {#setRecentsScreenshotEnabled-boolean-}
```
public void setRecentsScreenshotEnabled(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setRequestedOrientation(int arg0) {#setRequestedOrientation-int-}
```
public void setRequestedOrientation(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setResult(int arg0) {#setResult-int-}
```
public final void setResult(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setResult(int arg0, Intent arg1) {#setResult-int-android.content.Intent-}
```
public final void setResult(int arg0, Intent arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.content.Intent |  |

### setSecondaryProgress(int arg0) {#setSecondaryProgress-int-}
```
public final void setSecondaryProgress(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setShouldDockBigOverlays(boolean arg0) {#setShouldDockBigOverlays-boolean-}
```
public void setShouldDockBigOverlays(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setShowWhenLocked(boolean arg0) {#setShowWhenLocked-boolean-}
```
public void setShowWhenLocked(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setSupportActionBar(Toolbar arg0) {#setSupportActionBar-androidx.appcompat.widget.Toolbar-}
```
public void setSupportActionBar(Toolbar arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.appcompat.widget.Toolbar |  |

### setSupportProgress(int arg0) {#setSupportProgress-int-}
```
public void setSupportProgress(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setSupportProgressBarIndeterminate(boolean arg0) {#setSupportProgressBarIndeterminate-boolean-}
```
public void setSupportProgressBarIndeterminate(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setSupportProgressBarIndeterminateVisibility(boolean arg0) {#setSupportProgressBarIndeterminateVisibility-boolean-}
```
public void setSupportProgressBarIndeterminateVisibility(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setSupportProgressBarVisibility(boolean arg0) {#setSupportProgressBarVisibility-boolean-}
```
public void setSupportProgressBarVisibility(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setTaskDescription(ActivityManager.TaskDescription arg0) {#setTaskDescription-android.app.ActivityManager.TaskDescription-}
```
public void setTaskDescription(ActivityManager.TaskDescription arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.ActivityManager.TaskDescription |  |

### setTheme(Resources.Theme arg0) {#setTheme-android.content.res.Resources.Theme-}
```
public void setTheme(Resources.Theme arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.res.Resources.Theme |  |

### setTheme(int arg0) {#setTheme-int-}
```
public void setTheme(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setTitle(int arg0) {#setTitle-int-}
```
public void setTitle(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setTitle(CharSequence arg0) {#setTitle-java.lang.CharSequence-}
```
public void setTitle(CharSequence arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.CharSequence |  |

### setTitleColor(int arg0) {#setTitleColor-int-}
```
public void setTitleColor(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setTranslucent(boolean arg0) {#setTranslucent-boolean-}
```
public boolean setTranslucent(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

**Returns:**
boolean
### setTurnScreenOn(boolean arg0) {#setTurnScreenOn-boolean-}
```
public void setTurnScreenOn(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setVisible(boolean arg0) {#setVisible-boolean-}
```
public void setVisible(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### setVolumeControlStream(int arg0) {#setVolumeControlStream-int-}
```
public final void setVolumeControlStream(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setVrModeEnabled(boolean arg0, ComponentName arg1) {#setVrModeEnabled-boolean-android.content.ComponentName-}
```
public void setVrModeEnabled(boolean arg0, ComponentName arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |
| arg1 | android.content.ComponentName |  |

### setWallpaper(Bitmap arg0) {#setWallpaper-android.graphics.Bitmap-}
```
public void setWallpaper(Bitmap arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.graphics.Bitmap |  |

### setWallpaper(InputStream arg0) {#setWallpaper-java.io.InputStream-}
```
public void setWallpaper(InputStream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.io.InputStream |  |

### shouldDockBigOverlays() {#shouldDockBigOverlays--}
```
public boolean shouldDockBigOverlays()
```




**Returns:**
boolean
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
### shouldUpRecreateTask(Intent arg0) {#shouldUpRecreateTask-android.content.Intent-}
```
public boolean shouldUpRecreateTask(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
boolean
### showAssist(Bundle arg0) {#showAssist-android.os.Bundle-}
```
public boolean showAssist(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

**Returns:**
boolean
### showDialog(int arg0) {#showDialog-int-}
```
public final void showDialog(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### showDialog(int arg0, Bundle arg1) {#showDialog-int-android.os.Bundle-}
```
public final boolean showDialog(int arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | android.os.Bundle |  |

**Returns:**
boolean
### showLockTaskEscapeMessage() {#showLockTaskEscapeMessage--}
```
public void showLockTaskEscapeMessage()
```




### startActionMode(ActionMode.Callback arg0) {#startActionMode-android.view.ActionMode.Callback-}
```
public ActionMode startActionMode(ActionMode.Callback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ActionMode.Callback |  |

**Returns:**
android.view.ActionMode
### startActionMode(ActionMode.Callback arg0, int arg1) {#startActionMode-android.view.ActionMode.Callback-int-}
```
public ActionMode startActionMode(ActionMode.Callback arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.ActionMode.Callback |  |
| arg1 | int |  |

**Returns:**
android.view.ActionMode
### startActivities(Intent[] arg0) {#startActivities-android.content.Intent---}
```
public void startActivities(Intent[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent[] |  |

### startActivities(Intent[] arg0, Bundle arg1) {#startActivities-android.content.Intent---android.os.Bundle-}
```
public void startActivities(Intent[] arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent[] |  |
| arg1 | android.os.Bundle |  |

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

### startActivityFromChild(Activity arg0, Intent arg1, int arg2) {#startActivityFromChild-android.app.Activity-android.content.Intent-int-}
```
public void startActivityFromChild(Activity arg0, Intent arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |

### startActivityFromChild(Activity arg0, Intent arg1, int arg2, Bundle arg3) {#startActivityFromChild-android.app.Activity-android.content.Intent-int-android.os.Bundle-}
```
public void startActivityFromChild(Activity arg0, Intent arg1, int arg2, Bundle arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |
| arg3 | android.os.Bundle |  |

### startActivityFromFragment(Fragment arg0, Intent arg1, int arg2) {#startActivityFromFragment-android.app.Fragment-android.content.Intent-int-}
```
public void startActivityFromFragment(Fragment arg0, Intent arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Fragment |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |

### startActivityFromFragment(Fragment arg0, Intent arg1, int arg2, Bundle arg3) {#startActivityFromFragment-android.app.Fragment-android.content.Intent-int-android.os.Bundle-}
```
public void startActivityFromFragment(Fragment arg0, Intent arg1, int arg2, Bundle arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Fragment |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |
| arg3 | android.os.Bundle |  |

### startActivityFromFragment(Fragment arg0, Intent arg1, int arg2) {#startActivityFromFragment-androidx.fragment.app.Fragment-android.content.Intent-int-}
```
public void startActivityFromFragment(Fragment arg0, Intent arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |

### startActivityFromFragment(Fragment arg0, Intent arg1, int arg2, Bundle arg3) {#startActivityFromFragment-androidx.fragment.app.Fragment-android.content.Intent-int-android.os.Bundle-}
```
public void startActivityFromFragment(Fragment arg0, Intent arg1, int arg2, Bundle arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |
| arg3 | android.os.Bundle |  |

### startActivityIfNeeded(Intent arg0, int arg1) {#startActivityIfNeeded-android.content.Intent-int-}
```
public boolean startActivityIfNeeded(Intent arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |

**Returns:**
boolean
### startActivityIfNeeded(Intent arg0, int arg1, Bundle arg2) {#startActivityIfNeeded-android.content.Intent-int-android.os.Bundle-}
```
public boolean startActivityIfNeeded(Intent arg0, int arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | int |  |
| arg2 | android.os.Bundle |  |

**Returns:**
boolean
### startForegroundService(Intent arg0) {#startForegroundService-android.content.Intent-}
```
public ComponentName startForegroundService(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
android.content.ComponentName
### startInstrumentation(ComponentName arg0, String arg1, Bundle arg2) {#startInstrumentation-android.content.ComponentName-java.lang.String-android.os.Bundle-}
```
public boolean startInstrumentation(ComponentName arg0, String arg1, Bundle arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.ComponentName |  |
| arg1 | java.lang.String |  |
| arg2 | android.os.Bundle |  |

**Returns:**
boolean
### startIntentSender(IntentSender arg0, Intent arg1, int arg2, int arg3, int arg4) {#startIntentSender-android.content.IntentSender-android.content.Intent-int-int-int-}
```
public void startIntentSender(IntentSender arg0, Intent arg1, int arg2, int arg3, int arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.IntentSender |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |
| arg3 | int |  |
| arg4 | int |  |

### startIntentSender(IntentSender arg0, Intent arg1, int arg2, int arg3, int arg4, Bundle arg5) {#startIntentSender-android.content.IntentSender-android.content.Intent-int-int-int-android.os.Bundle-}
```
public void startIntentSender(IntentSender arg0, Intent arg1, int arg2, int arg3, int arg4, Bundle arg5)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.IntentSender |  |
| arg1 | android.content.Intent |  |
| arg2 | int |  |
| arg3 | int |  |
| arg4 | int |  |
| arg5 | android.os.Bundle |  |

### startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5) {#startIntentSenderForResult-android.content.IntentSender-int-android.content.Intent-int-int-int-}
```
public void startIntentSenderForResult(IntentSender arg0, int arg1, Intent arg2, int arg3, int arg4, int arg5)
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

### startIntentSenderFromChild(Activity arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6) {#startIntentSenderFromChild-android.app.Activity-android.content.IntentSender-int-android.content.Intent-int-int-int-}
```
public void startIntentSenderFromChild(Activity arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | android.content.IntentSender |  |
| arg2 | int |  |
| arg3 | android.content.Intent |  |
| arg4 | int |  |
| arg5 | int |  |
| arg6 | int |  |

### startIntentSenderFromChild(Activity arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6, Bundle arg7) {#startIntentSenderFromChild-android.app.Activity-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-}
```
public void startIntentSenderFromChild(Activity arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6, Bundle arg7)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Activity |  |
| arg1 | android.content.IntentSender |  |
| arg2 | int |  |
| arg3 | android.content.Intent |  |
| arg4 | int |  |
| arg5 | int |  |
| arg6 | int |  |
| arg7 | android.os.Bundle |  |

### startIntentSenderFromFragment(Fragment arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6, Bundle arg7) {#startIntentSenderFromFragment-androidx.fragment.app.Fragment-android.content.IntentSender-int-android.content.Intent-int-int-int-android.os.Bundle-}
```
public void startIntentSenderFromFragment(Fragment arg0, IntentSender arg1, int arg2, Intent arg3, int arg4, int arg5, int arg6, Bundle arg7)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.fragment.app.Fragment |  |
| arg1 | android.content.IntentSender |  |
| arg2 | int |  |
| arg3 | android.content.Intent |  |
| arg4 | int |  |
| arg5 | int |  |
| arg6 | int |  |
| arg7 | android.os.Bundle |  |

### startLocalVoiceInteraction(Bundle arg0) {#startLocalVoiceInteraction-android.os.Bundle-}
```
public void startLocalVoiceInteraction(Bundle arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Bundle |  |

### startLockTask() {#startLockTask--}
```
public void startLockTask()
```




### startManagingCursor(Cursor arg0) {#startManagingCursor-android.database.Cursor-}
```
public void startManagingCursor(Cursor arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.database.Cursor |  |

### startNextMatchingActivity(Intent arg0) {#startNextMatchingActivity-android.content.Intent-}
```
public boolean startNextMatchingActivity(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
boolean
### startNextMatchingActivity(Intent arg0, Bundle arg1) {#startNextMatchingActivity-android.content.Intent-android.os.Bundle-}
```
public boolean startNextMatchingActivity(Intent arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |
| arg1 | android.os.Bundle |  |

**Returns:**
boolean
### startPostponedEnterTransition() {#startPostponedEnterTransition--}
```
public void startPostponedEnterTransition()
```




### startSearch(String arg0, boolean arg1, Bundle arg2, boolean arg3) {#startSearch-java.lang.String-boolean-android.os.Bundle-boolean-}
```
public void startSearch(String arg0, boolean arg1, Bundle arg2, boolean arg3)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | boolean |  |
| arg2 | android.os.Bundle |  |
| arg3 | boolean |  |

### startService(Intent arg0) {#startService-android.content.Intent-}
```
public ComponentName startService(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
android.content.ComponentName
### startSupportActionMode(ActionMode.Callback arg0) {#startSupportActionMode-androidx.appcompat.view.ActionMode.Callback-}
```
public ActionMode startSupportActionMode(ActionMode.Callback arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | androidx.appcompat.view.ActionMode.Callback |  |

**Returns:**
androidx.appcompat.view.ActionMode
### stopLocalVoiceInteraction() {#stopLocalVoiceInteraction--}
```
public void stopLocalVoiceInteraction()
```




### stopLockTask() {#stopLockTask--}
```
public void stopLockTask()
```




### stopManagingCursor(Cursor arg0) {#stopManagingCursor-android.database.Cursor-}
```
public void stopManagingCursor(Cursor arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.database.Cursor |  |

### stopService(Intent arg0) {#stopService-android.content.Intent-}
```
public boolean stopService(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
boolean
### superDispatchKeyEvent(KeyEvent arg0) {#superDispatchKeyEvent-android.view.KeyEvent-}
```
public boolean superDispatchKeyEvent(KeyEvent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.KeyEvent |  |

**Returns:**
boolean
### supportFinishAfterTransition() {#supportFinishAfterTransition--}
```
public void supportFinishAfterTransition()
```




### supportInvalidateOptionsMenu() {#supportInvalidateOptionsMenu--}
```
public void supportInvalidateOptionsMenu()
```




### supportNavigateUpTo(Intent arg0) {#supportNavigateUpTo-android.content.Intent-}
```
public void supportNavigateUpTo(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

### supportPostponeEnterTransition() {#supportPostponeEnterTransition--}
```
public void supportPostponeEnterTransition()
```




### supportRequestWindowFeature(int arg0) {#supportRequestWindowFeature-int-}
```
public boolean supportRequestWindowFeature(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
boolean
### supportShouldUpRecreateTask(Intent arg0) {#supportShouldUpRecreateTask-android.content.Intent-}
```
public boolean supportShouldUpRecreateTask(Intent arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.Intent |  |

**Returns:**
boolean
### supportStartPostponedEnterTransition() {#supportStartPostponedEnterTransition--}
```
public void supportStartPostponedEnterTransition()
```




### takeKeyEvents(boolean arg0) {#takeKeyEvents-boolean-}
```
public void takeKeyEvents(boolean arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triggerSearch(String arg0, Bundle arg1) {#triggerSearch-java.lang.String-android.os.Bundle-}
```
public void triggerSearch(String arg0, Bundle arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |
| arg1 | android.os.Bundle |  |

### unbindService(ServiceConnection arg0) {#unbindService-android.content.ServiceConnection-}
```
public void unbindService(ServiceConnection arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.ServiceConnection |  |

### unregisterActivityLifecycleCallbacks(Application.ActivityLifecycleCallbacks arg0) {#unregisterActivityLifecycleCallbacks-android.app.Application.ActivityLifecycleCallbacks-}
```
public void unregisterActivityLifecycleCallbacks(Application.ActivityLifecycleCallbacks arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.app.Application.ActivityLifecycleCallbacks |  |

### unregisterComponentCallbacks(ComponentCallbacks arg0) {#unregisterComponentCallbacks-android.content.ComponentCallbacks-}
```
public void unregisterComponentCallbacks(ComponentCallbacks arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.ComponentCallbacks |  |

### unregisterForContextMenu(View arg0) {#unregisterForContextMenu-android.view.View-}
```
public void unregisterForContextMenu(View arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.view.View |  |

### unregisterReceiver(BroadcastReceiver arg0) {#unregisterReceiver-android.content.BroadcastReceiver-}
```
public void unregisterReceiver(BroadcastReceiver arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.BroadcastReceiver |  |

### updateServiceGroup(ServiceConnection arg0, int arg1, int arg2) {#updateServiceGroup-android.content.ServiceConnection-int-int-}
```
public void updateServiceGroup(ServiceConnection arg0, int arg1, int arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | android.content.ServiceConnection |  |
| arg1 | int |  |
| arg2 | int |  |

### validateRequestPermissionsRequestCode(int arg0) {#validateRequestPermissionsRequestCode-int-}
```
public final void validateRequestPermissionsRequestCode(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

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

