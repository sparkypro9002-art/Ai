# Birthday & Program Reminder

`index.html` is intentionally in the repository root.

Features:
- Birthday name, date of birth and passport-size photo
- Automatic age, next birthday and countdown
- Programs/functions with date, time, location, notes and photo
- Reminder selection
- Edit/delete and local persistence
- Android Capacitor project configuration
- Local Notifications and Calendar plugins prepared

Android build:
1. `npm install`
2. `npx cap add android`
3. `npx cap sync android`
4. Build the APK in Android Studio, or use the GitHub Actions workflow.

The Android layer is where reliable scheduled notifications, calendar events and alarms are implemented. Calendar/alarm permissions must be requested at runtime.
