# Privacy Policy — Hibiscus Korean Dictionary

Effective date and last updated: October 26, 2026.

App: Hibiscus Korean Dictionary (槿花辭典 / 근화 사전), Android package org.coldscholar.hibiscus.

Developer: Adam Woeltz, The Coldscholar Studio.

Privacy contact: coldscholarstudio@gmail.com.

## Overview

Hibiscus Korean Dictionary is an offline Korean dictionary with word lists and flashcard study. You do not need an account or provide personal information to use it. The app uses the Internet only when you tap Download or Update on its Language packs screen, to fetch that language's file from GitHub, and makes no other connection. It does not connect to developer-operated servers, and does not include advertising, analytics, tracking, or remote crash-reporting services. We do not sell or rent your personal data.

The app processes information on your device to provide its features. Information leaves the app only through actions you choose, such as downloading a language pack (which sends GitHub only the technical request described below), exporting a word list, saving a backup of your lists, tapping the Listen button, or separately sending us an email. Android and services you choose may also handle information as described below.

## Information processed on your device

- Search: The app uses the text you enter to find dictionary entries locally. Search input is held in memory during use. The app does not maintain a search-history database. Search text may also appear in Android diagnostic logs, as explained below.
- Text from other apps: If you select text in another app and choose Hibiscus from its menu, Android passes the selected text to the app. The app places its first 100 characters in the search field and handles them like text you typed. It does not send anything back to the other app.
- Listen: If your device has a Korean text-to-speech voice installed for offline use, an entry shows a Listen button. When you tap it, the app passes that entry's headword to your device's text-to-speech engine, a separate app such as Speech Services by Google, which speaks it and handles it under its own privacy policy. The app only uses a voice that the engine reports as installed and as not needing a network connection. To find out whether such a voice exists, the app asks Android which text-to-speech engines are installed and asks them which voices they have.
- Dictionary languages: Chinese ships inside the app. When you turn it on in Settings, the app unpacks it and builds its search index in its private storage. Nothing is downloaded.
- Language packs: Japanese, Vietnamese, French and Spanish are language packs, which you can download on the Language packs screen (Settings → More languages). When you tap Download or Update, the app requests that language's file from github.com, which passes the request on to GitHub's file host, release-assets.githubusercontent.com. The app checks the file's size and SHA-256 fingerprint against values built into the app, deletes a file that does not match, and installs the pack in its private storage, where it works without a connection. The app does not check for updates, download anything in the background, or connect at any other time. If a download is cut off, its partial file stays in private storage so that tapping Download again can continue it; cancelling the download deletes it.
- Word lists and study: The app stores list names, the dictionary entries you add, their order, list creation times, and each card's latest “Known” or “Not known” result and the time it was marked. For each list it also keeps the most recent study session: the order of its cards, how far it has gone, whether Shuffle or Meaning first was on, the results marked in it, and each card's previous result and time, so an unfinished session can resume and its answers can be undone. Starting a new session for that list replaces it. When you take a word out of a list, the app remembers its place and result in memory until the app closes, so that putting it back restores them. This information lets you organize vocabulary and review words. A new list imported from a file may use that file's name as its list name.
- Settings: The app stores your display and study preferences, including the interface language, text size, whether romanization and examples are shown, the dictionary languages you turned on and which of them search back to Korean, and your default word list.
- Selected files: If you import a word list, the app reads the text file you select and its displayed name to match words and add them to a local list. It does not copy the original file into its private storage. If you export a list, it writes the selected words and dictionary information, such as Hanja, pronunciation, romanization, definitions, and examples, to the destination you select. Study marks are not included in exports.
- Backups: If you use Back up, the app writes all your word lists to one text file at the destination you select: each list's name and creation time, which list is the default, the dictionary entries in each list and their order, and each card's latest “Known” or “Not known” result and the time it was marked. Settings and study sessions are not included. If you use Restore, or import a file that is a backup, the app reads the file you select and adds its lists, entries, and results to the lists on your device; it does not delete anything, and it does not copy the file into its private storage.
- Diagnostics: The app writes search text, words looked up in an entry, the entries and characters opened, result counts, performance timings, and each language pack download's progress and outcome (the language, the server's host name, and any error) to Android's local diagnostic log to help diagnose app behavior. For Listen, it logs the voice's name and the headword's length, not the headword. The app does not upload these logs. Android controls access to and retention of its diagnostic logs. They may be accessible through device debugging or included in a diagnostic report that you choose to share.

Settings and word lists are stored in the app's private storage on your device. We do not receive them automatically and cannot remotely read or delete them.

## Permissions and external services

The app requests Android's Internet permission and uses it only for the language pack downloads you start. It does not request access to your location, contacts, camera, microphone, photos, phone records, advertising identifier, or general device storage. File import and export use Android's system file picker, which grants access to the documents you select.

When you download a language pack, your device connects to GitHub, a service of GitHub, Inc., which hosts the packs. GitHub receives your device's IP address, the time, the file requested, and the request's headers, which name the app (“Hibiscus”) but not you, your device model, or your Android version. The app sends no account, identifier, search text, word lists, or settings. GitHub handles this information under its own privacy statement, available at https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement. Your network provider can also see that your device connected to GitHub.

If you select a cloud storage provider in the file picker, that provider may download or upload the selected file under its own privacy policy. An exported or backup file can also be accessed by apps or people with access to the destination you choose. Your keyboard, your text-to-speech engine, the app you select text in, Android, your device manufacturer, and Google Play operate independently and may process information under their own privacy policies.

The app disables Android's automatic cloud backup and provides no developer-operated sync or backup service. Its Back up feature only writes a file to a destination you select. Some devices may still transfer app data when you use a manufacturer or Android device-transfer feature. Those transfers are controlled by your device and its provider.

## If you contact us

If you email coldscholarstudio@gmail.com, we receive your email address, any name you provide, your message, and attachments you choose to send. We use this information to respond to your inquiry, troubleshoot problems you report, and handle privacy requests. Contacting us is optional; the app does not automatically attach your searches, lists, or logs to an email.

Our contact address uses Google's Gmail service to receive and store correspondence. Your email provider and Google process email as part of providing their services. Google's privacy policy is available at https://policies.google.com/privacy. We do not use support correspondence for advertising or sell it. We disclose correspondence only as needed to handle your request through these email services, with your permission, or when required by law.

## Security

The app relies on Android's application sandbox and private storage to restrict ordinary access to settings and word lists. It does not add its own encryption to local databases or exported text files. Language packs are downloaded only over HTTPS, and a downloaded file is used only if its size and SHA-256 fingerprint match the values built into the app. Your device's security settings protect local information; choose export destinations and recipients with care. Support email is handled through the security protections of the email services involved. Access to support correspondence is limited to the developer and the email providers needed to deliver and store it, except for the disclosures described above. No storage or communication method can guarantee complete security.

## Retention and deletion

- Local lists and study results remain until you remove words, delete their lists, clear the app's storage, or uninstall the app. Deleting a list removes its cards, their study results and its study session; deleting the last list creates a new, empty list. Marking a card again replaces its latest result and time; the previous ones stay only in that list's most recent study session, until a new session replaces it.
- Settings, unpacked dictionary languages, and installed language packs remain until you change or remove them, clear the app's storage, or uninstall the app. Turning Chinese off deletes its unpacked files. Turning a language pack off keeps its files; Remove on the Language packs screen deletes them. A downloaded file is deleted once its pack is installed. To remove all app-managed settings and word-list data, open Android Settings, select Hibiscus, and use “Clear storage” or “Clear data,” or uninstall the app. Exact labels vary by device.
- Search input and text received from other apps are temporary in-memory state. Android separately controls how long diagnostic logs remain; clearing app data or uninstalling does not necessarily erase those logs or reports you have already saved.
- Imported source files, exported files, backup files, and any copies in other apps or cloud services remain outside the app. Clearing app data or uninstalling does not delete them. Delete those files and copies using the relevant file manager or service.
- We retain support correspondence only as long as needed to resolve the inquiry and necessary follow-up, or to meet a legal obligation. You may request deletion of correspondence by emailing our privacy contact. If a legal obligation requires retention, we will explain any applicable limitation when responding.

There are no app accounts to delete. You can contact us with questions about accessing, correcting, or deleting information you have sent us. For information held only on your device, use the controls described above.

## Children

The same local processing applies to all users. The app does not ask for age or require children to submit personal information. If you believe a child has provided personal information in a support message, contact coldscholarstudio@gmail.com so we can address it and delete the information where appropriate.

## Changes and contact

We will update this policy if the app's data practices change and revise the date above. You can read this policy within the app under Settings → Privacy policy or About → Privacy policy. Korean, Simplified Chinese and Traditional Chinese translations are provided for convenience; if a translation differs from this English text, the English text governs.

For privacy questions or requests, contact Adam Woeltz at coldscholarstudio@gmail.com.
