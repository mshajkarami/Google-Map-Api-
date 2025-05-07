# 🗺️ Google Map API Project

This is a simple Android project written in **Java** that demonstrates how to use the **Google Maps API** in an Android application.  
It is designed as a beginner-level example for understanding how to display a map, add markers, and interact with basic map features.

## 📱 Features

- Displaying Google Map inside the app  
- Adding a default marker  
- Zoom controls and map gestures  
- Requesting location permissions  
- Customizing map type (normal, satellite, hybrid, terrain)

## 🛠️ Tech Stack

- **Java** (for Android)
- **Google Maps SDK for Android**
- **Android Studio**
- **Gradle**

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Google-Map-Api-.git
```

### 2. Open in Android Studio

### 3. Add Your Google Maps API Key  
Go to `local.properties` or directly to the `AndroidManifest.xml` and insert your key like this:
```xml
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY_HERE"/>
```

## 🔐 Permissions

Make sure to add the required permissions in `AndroidManifest.xml`:
```xml
<uses-permission android:name="android.permission.INTERNET"/>
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
```

## 📚 Learning Goals

- Understand how to integrate and use Google Maps in Android
- Practice requesting permissions at runtime
- Learn how to manipulate and customize map views
- Explore the basics of the Maps SDK

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
