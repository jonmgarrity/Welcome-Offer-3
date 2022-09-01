# Welcome-Offer-3

1. Install [Android Studio](url)
2. Edit MainActivity.java  in the src/main/java/com/launchdarkly/hello_android directory and set the value of MOBILE_KEY to your LaunchDarkly mobile key. If there is an existing boolean feature flag in your LaunchDarkly project that you want to evaluate, set FLAG_KEY to the flag 

  key..mobileKey("123456abcdef")

  private static final String FLAG_KEY = "my-boolean-flag";
  
3. Run your application through the Emulator or on a real device.
You should receive the message ”Feature flag ‘’ is <true/false> for this user”.
