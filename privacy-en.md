# Privacy Policy

**App name:** IdPhoto (증명사진)
**Developer:** gyodonggoo
**Contact:** peach44400@gmail.com
**Effective date:** 2026-05-19
**Last updated:** 2026-05-19

This policy describes how the IdPhoto app handles user information. The app **does not transmit your photos or personal information to any external server.** All photo processing happens on your device.

---

## 1. Information processed

The app processes the following information **on your device only.** Nothing is sent to the developer or any third party.

| Item | How it is processed | Purpose |
| --- | --- | --- |
| Live camera frames (while shooting) | On-device only | ID-photo capture; face-position guidance |
| Photos picked from your gallery | On-device only | Editing photos you explicitly select |
| Saved output photos | Stored on your device | To keep the prints you requested |
| Photo-type preference | Stored on your device (DataStore) | Convenience — remembers your last choice |

The app **does not collect** your name, phone number, email address, account credentials, payment details, or any other personally identifying information.

---

## 2. Permissions

| Permission | Why it is requested | If you deny it |
| --- | --- | --- |
| Camera (`CAMERA`) | To take ID photos | Capture is unavailable; gallery import still works |
| Photos & media (`READ_MEDIA_IMAGES`) | To import a photo from your gallery | Gallery import is unavailable |
| External storage write (`WRITE_EXTERNAL_STORAGE`, Android 9 and below) | To save output files | Save location may be restricted |

---

## 3. Photo handling

- **All image processing — face detection, background segmentation — runs on your device** using on-device Google ML Kit models. No images or frames are uploaded to any server.
- Captured or edited photos are written to your device's photo storage **only when you choose to save them**.
- Neither the photos nor their metadata are sent to the developer.
- If you share a photo with another app (e.g., messaging, email), that other app's privacy policy applies to whatever you share.

---

## 4. Third-party libraries / SDKs

The app bundles the following on-device libraries. Within this app, they **do not transmit images or personal information off the device.**

- Google ML Kit Face Detection — face position and orientation
- Google ML Kit Subject Segmentation — subject / background separation
- AndroidX CameraX — camera preview and capture
- Jetpack Compose, Coil — UI and image loading

The app contains **no advertising SDKs, no analytics SDKs, and no crash-reporting SDKs.**

---

## 5. Retention

- Photos you save remain on your device until you delete them.
- The photo-type preference remains on your device until you uninstall the app.
- The developer does not store any user data on any server.

---

## 6. Your rights

- You can delete saved photos at any time using your device's Photos or Files app.
- Uninstalling the app removes all preferences the app has stored.
- Because the developer does not retain any of your data, there is no separate access, correction, or deletion request process.

---

## 7. Children

The app is not directed at children under 14, and does not knowingly collect personal information from children.

---

## 8. Changes to this policy

If this policy changes, the new version will be published in the app's update notes and/or in this document with an updated "Last updated" date.

---

## 9. Contact

Questions about this policy can be sent to:

- Email: peach44400@gmail.com

---

## Appendix — Disclaimer about "passport photo regulations"

The app provides a capture guide that **references** the Korean Ministry of Foreign Affairs passport-photo regulations. The app is an unofficial tool, not affiliated with the Ministry or any government agency. **It does not guarantee that the resulting photo will be accepted by every issuing authority.** Final acceptance is at the discretion of the issuing authority.
