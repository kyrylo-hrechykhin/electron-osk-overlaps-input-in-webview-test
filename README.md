# electron-osk-overlaps-input-in-webview-test

This repo shows an issue Electron has with touch devices and webview tags. Demo application has two identical lists embedded in iframe and webview. On touch device if user focuses on input OSK (On screen keyboard) behaves differently whether it is iframe or webview. Iframe lifts up the whole application in order to show focused input. Webview does nothing and OSK just overlaps focused input.
