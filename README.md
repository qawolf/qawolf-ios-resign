# QA Wolf iOS Resign

After downloading `zsign` and `instrumentation.dylib` file from https://github.com/qawolf/qawolf-ios-resign/releases

Run the command
```bash
zsign \
  -k $PRIVATE_KEY_OR_P12_FILE \
  -p $PASSWORD_FOR_PRIVATE_KEY_OR_P12_FILE \
  -m $MOBILE_PROVISIONING_FILE \
  -b $APP_BUNDLE_ID \
  -l $QA_WOLF_INSTRUMENTATION_DYLIB_FILE \
  -d $IPA_FILE
```