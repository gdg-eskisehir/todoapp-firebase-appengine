##TODO APP 

The sample app stores a to-do list in Firebase, which automatically synchronizes the data across devices and then uses backend logic running on App Engine to send out daily reminder emails.

## Note

If you want to compile this project, you need to edit Constants class.

```java
public class Constants {

    public static final String FIREBASE_ENDPOINT = "https://[REPLACE-WITH-YOUR-APP].firebaseio.com/";
    public static final String MAIL_TO = "[REPLACE-WITH-YOUR-MAIL-ADDRESS]";
    public static final String APP_ID = "[GET-YOU-APP-ID-FROM-CLOUD-CONSOLE]";
}
```

Note: This is just a compiled project. You can follow [this](https://cloud.google.com/solutions/mobile/firebase-app-engine-android-studio) documentation to create this project.


