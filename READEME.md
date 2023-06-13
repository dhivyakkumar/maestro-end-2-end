# Maestro

Maestro is the easiest way to run test for Android app. Since the Flows run in the cloud, there's no need to configure any simulators or emulators. 

## Installig Maestro:

```
curl -Ls "https://get.maestro.mobile.dev" | bash
```

## Running locally: 
1. Make sure we have a emulator running on your laptop.
2. Install the apk file from https://install.appcenter.ms/orgs/sumup/apps/sumup-android-kiwi/distribution_groups/ucars-public

```
maestro test flow.yaml
```

## Running in Maestro Cloud:
```
1. maestro login
2. maestro cloud sample.apk flow.yaml
```

## Launch Maestro Studio for identify UI elements:
```
maestro studio
```
