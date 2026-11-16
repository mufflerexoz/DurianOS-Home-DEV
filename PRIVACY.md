# Privacy Policy — DurianOS Home

**Effective date:** 16 November 2026
**App:** DurianOS Home (`com.durianos.mufflerexoz`)
**Developer:** mufflerexoz

DurianOS Home is a home screen (launcher) app for Android. This policy explains what information the app uses, why, and where it goes.

## The short version

- **No account and no sign-in.**
- **No ads, no analytics and no tracking.**
- **We have no servers.** Your layout, settings and icons stay on your phone.
- **We don't sell or share your data.**
- The app only connects to the internet for two things:
  - **weather**, sent to Open-Meteo, only if you allow location
  - **the optional Pro purchase**, through Google Play

## Information stored on your phone

To work as your Home Screen, the app saves on your device only:

- your Home Screen layout: pages, app positions, folders, dock and widgets
- your settings: appearance, icon style, tint colour, icon pack choice and similar options
- custom app names and icons, including copies of any photos you choose for icons or the Photo widget
- whether you own DurianOS Home Pro, so Pro features work offline

This data stays in the app's private storage. You can remove it at any time:
- **Settings → Apps → DurianOS Home → Clear storage**, or
- uninstall the app.

**Backups.** When you use **Customise → Back Up Home Screen**, the app writes a file to the place you choose. It contains your layout, settings, names and custom icon images. The file is under your control; we never receive it.

## Permissions and how they are used

| Permission | Why it's needed |
|---|---|
| **See installed apps** (`QUERY_ALL_PACKAGES`) | A launcher must list your apps to show and open them. The list is only used on your device. |
| **Approximate location** (`ACCESS_COARSE_LOCATION`), optional | Only for the Weather widget, and only if you allow it. See "Weather" below. |
| **Internet** (`INTERNET`) | Weather data and Google Play purchases. |
| **Notification access**, optional, granted in system settings | Only to show the red badge numbers on app icons. The app reads which app a notification belongs to and how many there are. It does **not** read, store or send notification titles or text, and counts are kept in memory only. |
| **Storage / All files access** (`READ_EXTERNAL_STORAGE`, `MANAGE_EXTERNAL_STORAGE`), optional | Only to read your current wallpaper image so the glass effect can blur it. No other files are read. |
| **Request app removal** (`REQUEST_DELETE_PACKAGES`) | Opens Android's own uninstall screen when you choose "Delete App". |
| **Photo picker** | Only the photos you pick (for custom icons or the Photo widget) are copied into the app. No other photos are accessed. |

You can turn off location, notification access and file access at any time in Android Settings. The rest of the app keeps working.

## Weather

If you allow location, the app:

1. Uses Android's last known approximate location.
2. Sends the coordinates, **rounded to about 100 m**, to **[Open-Meteo](https://open-meteo.com/)** to get the forecast. As with any internet request, Open-Meteo also sees your IP address. See the [Open-Meteo terms & privacy](https://open-meteo.com/en/terms).
3. Uses your phone's built-in geocoding service to turn the coordinates into a city name. On most phones this service is provided by Google.

The location is not stored by the app and is not used for anything else.

## Purchases (DurianOS Home Pro)

Pro is an optional one-time purchase handled entirely by **Google Play**.
- Your payment details go to Google, never to us.
- The app only receives the purchase status from Google Play, to unlock Pro and to restore it on a new phone.

See the [Google Privacy Policy](https://policies.google.com/privacy).

## Other apps and links

- **Search:** web searches you start from Search open your browser or Google app, and they are handled by that app.
- **Play Store links:** these open the Play Store app.
- **Opening apps:** apps you open from the Home Screen have their own privacy policies.

## Children

DurianOS Home is a general-purpose launcher. It is not directed at children and does not knowingly collect personal information from anyone.

## Security

All data is stored in the app's private storage, which Android protects from other apps. The weather request uses HTTPS.

## Changes to this policy

If this policy changes, the updated version will be published here with a new effective date.

## Contact

For questions about this policy or your data, email **kulimambangfoto@gmail.com**.
