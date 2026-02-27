# Apk app with html content coding

## 1. Cloning Project
```ruby
git clone https://github.com/GEORGECR0/apk-app-base.git
cd apk-app-base
cd myapp
```

## 2. Install Node
```ruby
npm install
```

## 3. Install / Sync / Open Android
```ruby
npx cap add android
npx cap sync
npx cap open android
```

## 4. Update and built apk file
```ruby
cd android
.\gradlew assembleDebug
```


#How set up landspace mode

### PATH:
```ruby
myapp/android/app/src/main/AndroidManifest.xml
```

Add this `android:screenOrientation="landscape"` to the `<activity>` tag
