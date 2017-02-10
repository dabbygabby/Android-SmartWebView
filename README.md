# Android Smart WebView
This project will help you create Smart Android applications on the go without much re-creating a whole app or learning JAVA or Android programming. You can embed your existing website or can develop a simple HTML based app.

Android Smart WebView gathers all necessary information needed to make an Advanced Android App with Location Tracking, File Uploads, Using Camera for Uploading Images, Custom Dialogues and Notifications.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Requirement
The project requires minimum Android API 16+ (4.1 JellyBean) SDK to test. And you can use any development software of your choice, I used Android Studio making this.

### Test Run
Try rebuilding the project on your programming environment, once you are done fixing any error (incase if one came up), you'll be ready to look into the project.

### Easy Setup
Once your project is ready here are some static variables you can change as per your Apps requirement.

#### Permission variables
```java
ASWP_JSCRIPT     = true;     // enable JavaScript for webview
ASWP_FUPLOAD     = true;     // upload file from webview
ASWP_CAMUPLOAD   = true;     // enable upload from camera for photos
ASWP_LOCATION    = true;     // track device locations with GPS
ASWP_RATINGS     = true;     // ask user for app ratings; edit method get_rating() for dialogue customizations
ASWP_PBAR        = true;     // show page load progress (progess bar) in app
ASWP_ZOOM        = false;    // ability to zoom view content
ASWP_SFORM       = false;    // save form cache and auto-fill information
```

#### Configuration variables
Complete URL of your website, landing page or local file as (file:///android_res/dir/file)
```java
ASWV_URL      = "http://mgks.infeeds.com";
```
If file upload enabled, you can define its extention type, default is "\*/\*" for all file types;

Use "image/*" for image types; check file type references on web for more
```java
ASWV_F_TYPE   = "*/*";
```