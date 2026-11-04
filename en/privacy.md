---
title: Privacy Policy
permalink: /en/privacy/
lang: en
description: ClipMoa Privacy Policy
---

# ClipMoa Privacy Policy

Apart from email you choose to send, the developer of ClipMoa does not receive or keep your personal information. The items you save stay only on your devices and in your iCloud (iPhone and Mac), and in your Google Drive if you turn on Google Drive sync. Cloud AI is used only if you turn it on yourself, and then content is sent directly to that company with your own key. This policy covers both the iPhone and Mac app and the Android app; anything that applies to only one of them says so.

Effective date: November 5, 2026 · Developer: ByoungRak Song

## 1. Information the developer receives
- The app sends nothing to the developer. It has no sign-up, login, ads, analytics tools or tracking, and the developer runs no servers.
- Crash reports: If you turn on "Share with App Developers" in your device settings on iPhone and Mac, Apple — and if you turn on sharing usage and diagnostics with Google on Android, Google Play — passes crash reports and usage statistics to the developer in a form that does not identify you.
- Email you send: If you write to the developer with a question or to report an AI result, the developer receives your address and message and uses them only to reply and to fix the app. On Android, tapping Report next to a summary only opens your email app with the model name, the summary and the app version filled in; you check it, edit it and send it yourself.

## 2. Information stored on your devices
- Items you save: photos and screenshots, links, shared text, text read from images, titles, summaries, tags and categories, and any edits you make.
- These items are stored in the app's storage on your device. On iPhone and Mac, if you use iCloud, they are synced to your other iPhones and Macs through your private iCloud database, and the developer cannot access this data. [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) applies to iCloud.
- The Android app does not use iCloud. To keep your devices in step, use Google Drive sync (section 4). The Android app also turns off automatic backup (Google account backup), so app data does not go to Google's backup.
- App settings, cloud AI keys and whether you agreed to sending are stored only on that device and are not synced. Keys are stored encrypted (in the Keychain on iPhone and Mac; on Android, encrypted with a key in the Android Keystore and kept in the app's storage). The permission used to connect Google Drive is also kept only on that device (on iPhone and Mac, a token in the Keychain; on Android, managed by Google Play services).

## 3. What is processed only on the device
- Reading text in images (Apple Vision on iPhone and Mac; on Android, the Google ML Kit model that comes inside the app), on-device AI summaries (Apple Intelligence on iPhone and Mac), in-app search, and the index that lets Spotlight and Siri find items (iPhone and Mac) are all processed on the device. Images are not sent off the device to read their text. The diagnostic information that ML Kit sends on Android is described in section 4.
- When you search ClipMoa with Visual Intelligence on iPhone, the screen image the system passes to the app is used on the device only to read text for the search, and it is not stored.

## 4. Information that leaves the device
- Whoever receives an internet request also receives ordinary connection information, such as the device's IP address. All of the app's internet requests use encrypted connections (HTTPS).
- **When you save a link**: the app connects to that web page to get its title, body text and main image. For YouTube links, it asks YouTube (Google) for the title, channel and thumbnail. No cookies are stored.
- **Text reading diagnostics (Android)**: For diagnostics and usage analytics, Google ML Kit, which the Android app uses to read text, sends Google information such as the device model and OS version, the app name and version, a per-installation identifier (not intended to identify a person or a device), and processing time, settings, input and output sizes and error codes. Images and the text read from them are not part of this. It is sent over an encrypted connection, and Google states that it does not pass this information to third parties ([ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure)). The developer does not receive this information, and the app has no setting to turn it off.
- **Cloud AI (optional)**: used only if you enter an API key for one of Anthropic (Claude), Google (Gemini) or OpenAI in the app's settings and agree to sending to that company. Nothing is sent before you agree.
    - What is sent: text taken from the item (for very long text, only the beginning and the end), the item type, and up to 10 existing category names. This is to make summaries, tags and categories.
    - What is not sent: original images, videos and files, your Apple Account or Google Account, location, device identifiers.
    - It goes directly from your device to that company's servers, sent with the key you entered. The developer never receives or sees the content.
    - That company's terms and privacy policy apply to what is sent: [Anthropic](https://www.anthropic.com/legal/privacy) · [Google](https://policies.google.com/privacy) · [Gemini API Terms](https://ai.google.dev/gemini-api/terms) · [OpenAI](https://openai.com/policies/privacy-policy/)
    - For Gemini, the app recommends a key with billing set up (paid tier). If you send with a free-tier key, Google may use the content to improve its products, and people may review it. Keys with billing set up are not used that way.
- **iCloud sync (iPhone and Mac)**: the items in section 2 go to your other iPhones and Macs through your iCloud.
- **Google Drive sync (optional)**: used only if you connect Google Drive under "Sync" in the app's settings.
    - When connecting, you sign in yourself on Google's sign-in and consent screens. The app never receives your password and only gets permission to access its own app-only folder. To show the connected account's address in Settings, the app asks Google for that address (kept only on that device).
    - What is sent: all of the saved items in section 2 (including original photos and screenshots) and the times each item uses for syncing. iPhone and Mac also send a record of which device on the same iCloud is connected to Drive — the device type (iPhone or Mac) and a value for recognizing the iCloud account (a hash made from the iCloud account; it is not the account name or Apple Account address).
    - Where it goes: a hidden app-only folder in your Google Drive. This folder does not appear in Drive, and only this app reads and writes it. Your other devices connected with the same Google account receive items from it.
    - The app does not access any of your Drive files other than this folder.
    - The developer cannot access this data. It is uploaded without encryption, so Google can technically access it, and the [Google Privacy Policy](https://policies.google.com/privacy) applies.
- **Places you choose**: if you use export or connect an Obsidian vault (iPhone and Mac), files are saved to the location you choose. On Android, export hands the file to the share menu, and it goes where you choose.
- The servers of the cloud AI companies, Apple and Google may be located outside the Republic of Korea.

## 5. Permissions
- Photos: the app uses the system photo picker, so it can access only the photos you pick.
- Clipboard: on iPhone and Mac, the app only checks, with a system feature, whether there is a link, and reads the content only when you tap Save. On Android, it reads the clipboard only when you tap "Paste link from clipboard".
- Sharing: when you pick ClipMoa from another app's share menu, the app receives that content.
- Folders (iPhone and Mac): the app accesses only the folder you pick as your Obsidian vault.

## 6. Retention and deletion
- Saved items are kept until you delete them. Deleting an item in the app deletes it from the device and iCloud (iPhone and Mac), and, if Google Drive sync is on, from Drive and your other connected devices.
- You can delete the sync data in Google Drive with "Delete all sync data in Drive" in the app's settings. You can remove the app's access to Drive in your Google Account settings under third-party apps with account access.
- Deleting the app deletes the data on the device. On iPhone and Mac, data left in iCloud can be deleted under iCloud storage management in your device settings.
- You can delete cloud AI keys in the app's settings, and you can withdraw your agreement to sending at any time under "Cloud models" in the app's settings. After you withdraw, nothing more is sent to that company. Keeping and deleting content that was already sent follow that company's policy.

## 7. Children
- This app is not directed at children, and it does not collect anyone's personal information.

## 8. Changes to this policy
- If this policy changes, the change will be posted on this page with a new effective date. If what is sent to cloud AI changes, the app will ask for your agreement again.

## 9. Contact
- Privacy officer: ByoungRak Song · [red@enfre.com](mailto:red@enfre.com)
- Reporting and advice on privacy violations (Republic of Korea): [Personal Information Infringement Report Center](https://privacy.kisa.or.kr) 118 (no area code), [Personal Information Dispute Mediation Committee](https://www.kopico.go.kr) 1833-6972, Supreme Prosecutors' Office 1301 (no area code), Korean National Police Agency 182 (no area code)
