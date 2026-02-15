# Privacy Policy for Vocalize AI

**Last Updated: February 15, 2026**

## Overview

Vocalize AI ("the App") is developed by Ishtec ("we", "us", or "our"). We are committed to protecting your privacy. This Privacy Policy explains how the App handles your data.

**The core principle: Vocalize AI processes everything on your device. Your voice recordings, transcriptions, and AI analysis never leave your iPhone.**

## Data Collection

**We do not collect any personal data.** Vocalize AI is designed with a privacy-first architecture where all processing happens locally on your device.

### Data Not Collected

We do not collect, transmit, or store any of the following on external servers:

- Voice recordings
- Transcriptions
- AI analysis results (summaries, key points, action items, sentiment)
- Personal Voice data
- Calendar or reminder information
- File contents or metadata
- Usage analytics or telemetry
- Device identifiers
- Location data
- Contact information

## On-Device Processing

All features of Vocalize AI run entirely on your device using Apple's native frameworks:

- **Voice Recording**: Audio is captured and stored locally using AVFoundation.
- **Transcription**: Speech-to-text is performed on-device using Apple's Speech framework (SFSpeechRecognizer). No audio is sent to external servers.
- **AI Analysis**: Summaries, key points, action items, sentiment analysis, and topic extraction are performed on-device using Apple's NaturalLanguage framework.
- **Text-to-Speech**: Voice synthesis, including Personal Voice, is handled on-device by AVSpeechSynthesizer.
- **Voice Separation**: Audio processing uses on-device CoreML models and the Accelerate framework.
- **Noise Reduction & Audio Enhancement**: All audio processing is performed locally using vDSP and Accelerate.

## iCloud Sync

If you choose to enable iCloud Sync, your recordings, folders, and tags are synced across your devices using **Apple's CloudKit** service. This data is:

- Stored in your **private iCloud account**, not accessible by us
- Protected by Apple's encryption and security measures
- Governed by [Apple's Privacy Policy](https://www.apple.com/privacy/)

We do not have access to your iCloud data. You can disable iCloud Sync at any time in the App's Settings.

## Calendar & Reminders Access

If you grant permission, the App can read your calendar events to enable the Smart Meeting Assistant feature and create reminders from AI-detected action items. This data is:

- Accessed locally on your device using Apple's EventKit framework
- Never transmitted to external servers
- Only used when you explicitly initiate an action

You can revoke these permissions at any time in iOS Settings.

## Microphone & Speech Recognition

The App requires microphone access to record audio and speech recognition permission for transcription. These permissions are:

- Requested explicitly with clear explanations
- Used only when you actively initiate recording or transcription
- Processed entirely on-device (Apple's on-device speech recognition)

## Third-Party Services

**Vocalize AI does not use any third-party analytics, advertising, or tracking services.** There are no third-party SDKs embedded in the App.

The only external service used is Apple's CloudKit for optional iCloud Sync, which is governed by Apple's own privacy practices.

## AI Voice Models

If you choose to download a custom AI voice separation model, the App will fetch the model file from the URL you provide. This is a one-time download initiated by you. No personal data is sent during this process.

## Data Storage & Security

- All app data is stored locally on your device in the App's sandboxed container
- Data is protected by iOS's built-in encryption and device passcode
- If iCloud Sync is enabled, data is additionally protected by Apple's iCloud security

## Data Deletion

You can delete all your data at any time:

- **Individual recordings**: Swipe to delete in the Library
- **All data**: Settings > Reset > Delete All Data
- **Uninstalling the App** removes all locally stored data

## Children's Privacy

Vocalize AI does not knowingly collect any data from children under the age of 13. Since the App does not collect any personal data from any user, it is compliant with COPPA and similar regulations.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this page. We encourage you to review this policy periodically.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at:

**Email**: support@ishtec.com
**Website**: www.ishtec.com
