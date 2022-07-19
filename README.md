# React Native Custom Fonts Android (2022)

In this tutorial, I will tell you how to implement custom fonts in React-Native both in Android

# Step 1:

Create an assets folder in Adroid/app/src/main. Then create a fonts folder inside it. Finally, copy your fonts file inside the fonts folder.

# Step 2:

Create an "Info.plist" file in android/app

# Step 3:

Add the following code in "Info.plist"

```

<?xml version="1.0" encoding="UTF-8"?>
<plist version="1.0">
<dict>
  <key>UIAppFonts</key>
  <array>
    <string>OpenSans-BoldItalic.ttf</string>
    <string>Waffle Story.ttf</string>
  </array>
</dict>
</plist>


```

# Step 3:

Use in font fontFamily that we have downloaded

```
fontFamily: 'Waffle Story',

```
