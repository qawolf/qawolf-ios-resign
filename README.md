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

## Licensing

| Component | License |
|-----------|---------|
| zsign | BSD-3-Clause |
| instrumentation.dylib | Proprietary – © 2024 QA Wolf, all rights reserved |

This repository bundles the `zsign` binary under its original BSD-3-Clause license.
The `instrumentation.dylib` library is proprietary to QA Wolf and is provided solely for use with QA Wolf products. Redistribution or modification is not permitted without prior written consent from QA Wolf.

See the `LICENSE` file for full license texts.