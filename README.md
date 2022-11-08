# ee490-review

<activity android:name= "ShareActivitity">
   <intent-filter>
     <action android: name = "android.intent.action.SEND">
     <category android: name = "androis.intent.category.DEFAULT"/>
      <data android:mineType="text/plain">
    </intent-filter>
   </activity>
     
   retrieves the intent content in onCreate()
     val bundle: Bundle? = intent.extras
     val name: String? = bundle?.getString("key")
