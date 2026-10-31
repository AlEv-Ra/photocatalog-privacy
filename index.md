# PhotoCatalog — Privacy Policy

**Last updated: October 31, 2026**

## 1. Overview

PhotoCatalog is a macOS application designed to organize, browse, and manage photographs stored on your computer and connected storage devices.

We respect your privacy. PhotoCatalog is designed to work primarily with local data and does not require an account or an internet connection for its core functionality.

This Privacy Policy explains how PhotoCatalog processes information and when data may be shared with third-party services.

## 2. Local Data Storage

PhotoCatalog processes photographs and related information locally on your Mac.

This includes:

- Photographs and other supported image files.
- File names, file locations, and file metadata.
- Virtual albums and their organization.
- Comments, hashtags, and privacy settings associated with photographs.
- Application preferences and authorized folder locations.

PhotoCatalog stores its catalog database locally using SQLite. Original photographs remain in their existing locations unless you explicitly perform file operations such as copying, moving, renaming, deleting, or resizing.

PhotoCatalog does not automatically upload your photographs or catalog database to the developer's servers.

## 3. Google Gemini Integration

PhotoCatalog offers an optional AI-assisted feature powered by Google Gemini to organize photographs based on their file names.

When you explicitly authorize a Gemini analysis, PhotoCatalog sends the following information to Google's Gemini API:

- File names, including file extensions, from the selected analysis set.
- Temporary identifiers assigned to those files.
- Your current text instructions for the analysis.
- The application interface language and technical instructions required to process the request.

The complete file-name list may be transmitted again when you refine an analysis.

**PhotoCatalog does not send image contents, image files, absolute file paths, EXIF metadata, album names, comments, hashtags, or photograph privacy flags as part of these requests.**

File names and user-provided instructions may themselves contain personal information. Please review them before authorizing transmission.

Google processes the submitted information under its applicable terms and privacy policies.

For more information, visit:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google AI for Developers](https://ai.google.dev/)

## 4. Your Consent and Control

Google Gemini integration is optional.

Before transmitting file names for an AI-assisted analysis, PhotoCatalog requests your confirmation.

You may decline the request and continue using local functionality.

Your consent applies to the current analysis session, including subsequent refinements within that session. A new session requires new confirmation.

PhotoCatalog can be used without configuring Gemini or providing an API key.

A separate connection-test feature sends a fixed test instruction to Google without including your photograph file names.

## 5. API Key Security

If you choose to use Google Gemini, you provide your own API key.

PhotoCatalog stores this key locally in macOS Keychain rather than in its SQLite catalog database or application preferences.

The key is transmitted to Google's API when you initiate an authorized Gemini request or connection test.

Your API key is not transmitted to the PhotoCatalog developer.

## 6. Analytics and Diagnostics

PhotoCatalog does not include developer-operated analytics, advertising trackers, or an application-specific telemetry service.

The application may record limited technical diagnostics in the local macOS system log, including Gemini request duration and token usage statistics.

These diagnostics do not intentionally include API keys, photograph file names, user instructions, or request and response contents.

Apple and Google may independently process technical information according to their respective policies and services.

## 7. Data Retention and Deletion

PhotoCatalog stores its local catalog information and preferences on your device.

You can manage photographs, virtual albums, and associated information using the application's available features.

Removing a photograph from a virtual album does not necessarily delete the original file or all catalog information associated with it.

PhotoCatalog does not provide a single in-app command to erase all locally stored application data.

Information sent to Google Gemini is subject to Google's applicable data handling and retention practices. PhotoCatalog cannot independently delete information retained by Google.

## 8. Data Sharing

PhotoCatalog does not sell your personal information.

The application does not transmit your local photo catalog to the developer.

The optional Gemini integration transmits the information described in Section 3 directly to Google's API when authorized.

No other application-specific external data transfer was identified in the reviewed implementation.

## 9. Security

PhotoCatalog uses macOS file access permissions and security mechanisms to access authorized locations.

The application's private-photo visibility feature restricts access within the PhotoCatalog interface. It does not encrypt original photographs or the local catalog database.

You remain responsible for securing your Mac, storage devices, backups, and Google API credentials.

## 10. Changes to This Policy

This Privacy Policy may be updated to reflect changes in PhotoCatalog, its features, or applicable requirements.

The latest version will be available on this page, with the revision date shown above.

## 11. Contact

For privacy-related questions or requests concerning PhotoCatalog, please contact:

**gogagevara@gmail.com**

---

*PhotoCatalog for macOS*
