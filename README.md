# fastlaneDemo

on file ./fastlane/Fastfile

1. run fastlane 'internal' need declare variable

@playStoreFile = "File Json"
"android.injected.signing.store.file" => "File KeyStore",


2. run fastlane 'distribute' need declare variable
app: "App ID Firebase",
firebase_cli_token: "Firebase CI Token",
