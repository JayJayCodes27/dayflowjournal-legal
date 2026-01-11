Privacy Policy for DayflowJournal
Effective Date: January 11, 2026
Last Updated: January 11, 2026
**Version:** 1.22
Our Core Privacy Commitment
DayflowJournal is built on one fundamental principle: your journal is private by design.
DayflowJournal is designed so that your journal entries, photos, voice recordings, handwriting, mood data, and reflections are stored locally on your device and are not accessible to us under normal operation. We do not require accounts, do not operate cloud storage for journal content, and do not intentionally collect or transmit personal journal data to our servers.
1. Information We Collect
1.1 Data Stored Locally on Your Device
The following data is stored locally on your iOS device using Apple’s SwiftData framework and iOS system storage. This data is intended to remain on your device unless you choose to back it up or export it.
Journal Content
Text journal entries (typed, handwritten, or transcribed)
Handwriting data created using Apple Pencil (PKDrawing format)
Voice recordings (M4A audio files with timestamps and duration)
Voice transcriptions generated using Apple’s Speech framework
Photos attached to entries (JPEG/PNG)
Basic metadata such as date and dimensions
Location (EXIF GPS) data is not extracted or stored by the app
Mood & Reflection Data
Daily ratings and emotional tags
Day descriptors and color associations
Anticipation and outlook ratings
Organizational Data
Tags, favorites, draft status
Prompt identifiers and prompt text
App Settings (Stored via UserDefaults)
Visual preferences (themes, fonts, colors)
Journaling mode preferences
Audio and notification preferences
Privacy and security settings (biometric lock, timeouts)
Backup configuration flags
Onboarding and app version state
1.2 Data We Do Not Intentionally Collect
DayflowJournal is designed so that we do not intentionally collect, access, or store:
Names, email addresses, phone numbers, or account credentials
Journal content or attachments
Location or GPS data
Advertising identifiers (IDFA)
Device identifiers (UDID)
Analytics or usage tracking data
Crash reports or diagnostics
Behavioral tracking or profiling data
Social media or third-party integration data
1.3 Biometric Authentication

**Face ID / Touch ID:** When you enable biometric authentication to lock your journal:

- Biometric authentication is handled entirely by iOS LocalAuthentication framework
- Your fingerprint or facial scan **never leaves your device** and is never accessed by our app
- We only receive a success/failure result from iOS
- Biometric data is stored in the Secure Enclave and managed by Apple
- We cannot access, store, or transmit biometric data
- Enabling biometric lock is **optional** and can be disabled at any time
2. How Your Data Is Used
2.1 On-Device Processing
DayflowJournal's features are designed to operate using on-device processing where supported by iOS and device capabilities.
This includes:
• Text analysis and sentiment insights
• Prompt personalization
• Mood trend calculations
• Search indexing
• Handwriting recognition (OCR)
• Voice transcription
• Voice emotion analysis
• Writing pattern analysis

**Important Note on Apple Framework Processing:**

Where supported by iOS and device capabilities, speech recognition, handwriting recognition, and natural language processing are performed on-device. However, in limited cases determined by Apple (such as language availability, system configuration, or network conditions), processing may be performed by Apple on its servers in accordance with Apple's Privacy Policy.

**We do not receive, access, or store any data processed by Apple.** This processing is entirely controlled by Apple's system frameworks and is subject to Apple's privacy protections, not ours.

For complete details on Apple's data handling:
- Speech Framework: https://www.apple.com/privacy/
- Vision Framework: https://www.apple.com/privacy/
- Natural Language Framework: https://www.apple.com/privacy/
2.2 Premium Subscription Verification
Premium purchases are processed by Apple via the App Store.
Payment information is handled exclusively by Apple
We do not receive credit card or billing details
Subscription status is verified locally using Apple’s StoreKit framework
Apple may collect purchase-related data as part of App Store transactions, which is not accessible to us
2.3 Notifications
If enabled, DayflowJournal uses local notifications only:
Notifications are generated and scheduled on your device
No remote push notifications are used
Notification content never includes journal entries
3. Data Storage and Security
3.1 Local Storage
Journal data is stored in an encrypted database on your device
App data is protected by iOS sandboxing and file protection
Access is restricted to DayflowJournal only
3.2 Security Features
iOS file-level encryption
Optional biometric app lock
Optional preview hiding in the app switcher
No network transmission of journal content
3.3 Backups
DayflowJournal does not operate its own backup servers.
iCloud backups (if enabled) are managed by Apple
Finder/iTunes backups may include app data
Manual export is available and controlled by you
4. Third-Party Services
DayflowJournal uses only Apple-provided system frameworks, such as:
StoreKit
LocalAuthentication
UserNotifications
Speech
Vision
NaturalLanguage
SwiftData
PencilKit
AVFoundation
We do not use analytics SDKs, advertising SDKs, crash reporting tools, or third-party AI services.
5. Data Retention and Deletion
5.1 Free Tier
Free tier users retain the most recent 7 days of journal entries.
By using the free tier of DayflowJournal, you acknowledge and agree that journal entries older than seven (7) days will be automatically deleted from your device.
Deletion occurs locally and automatically.
5.2 Premium Tier
Premium users retain all entries indefinitely unless manually deleted or the app is uninstalled.
5.3 Deletion Controls
You may delete:
Individual entries within the app
All data via in-app reset
All data by uninstalling the app
Deleted data cannot be recovered unless restored from a device backup.
6. Children’s Privacy
DayflowJournal is intended for users aged 13 and over.
We do not knowingly collect personal data from children. Because data remains on-device, parental supervision is handled at the device level via iOS parental controls.
7. Your Privacy Rights
7.1 GDPR / UK GDPR
Limited Role as Data Controller:
DayflowJournal’s role as a data controller is strictly limited to determining the on-device processing required to provide app functionality. We do not receive, access, or store personal data on our own systems.
You may exercise your rights by:
Viewing or exporting your data
Editing or deleting entries
Uninstalling the app
7.2 CCPA & Other Laws
We do not sell personal information. We do not share personal data with third parties for advertising or profiling purposes.
8. International Transfers
DayflowJournal does not transfer journal data internationally.
Apple may process payment data internationally as part of App Store transactions, in accordance with Apple’s Privacy Policy.
9. Changes to This Policy
We may update this policy to reflect changes in the app or legal requirements.
Material changes will:
Be announced in-app
Be published before taking effect
Require consent where legally required
10. Contact Information
Legal Entity:
DayflowJournal
Operated by: [Your Full Legal Name or Company Name]
Registered Address: [Business or Registered Office Address]
Country: United Kingdom
Privacy & Support Contact:
Email: privacy@dayflowjournal.app
Website: https://dayflowjournal.app
11. App Store Privacy Disclosure

When downloading DayflowJournal from the Apple App Store, you'll see:

**Privacy Nutrition Label:**

| Category | DayflowJournal |
|----------|----------------|
| **Data Linked to You** | None |
| **Data Used to Track You** | None |
| **Data Not Linked to You** | None |
| **Data Collected** | None |

**We collect zero data. This is verifiable in App Store Connect.**

**Apple's Data Collection:**
Apple may collect purchase-related data (transaction IDs, subscription status) for App Store transactions. This data is collected by Apple, not by us, and we do not have access to it. Refer to Apple's Privacy Policy for details on their data handling practices.
12. Permissions Requested

DayflowJournal may request the following iOS permissions:

| Permission | Purpose | Required? |
|------------|---------|----------|
| **Photos** | To attach images to journal entries | Optional |
| **Microphone** | To record voice journal entries | Optional |
| **Camera** | To take photos directly in the app | Optional |
| **Face ID/Touch ID** | To lock journal with biometrics | Optional |
| **Notifications** | For daily journaling reminders | Optional |

**All permissions are optional.** You can deny all permissions and still use core journaling features (typing, handwriting).

---

## 13. Commitment to Privacy

**Our Promise to You:**

### We Will NEVER:
- ❌ Collect your journal content
- ❌ Track your usage behavior
- ❌ Sell your data to third parties
- ❌ Use your data for advertising
- ❌ Train AI models on your writing
- ❌ Require account creation
- ❌ Store data on our servers

### We Will ALWAYS:
- ✅ Process data on-device only
- ✅ Give you full control over your data
- ✅ Be transparent about any changes
- ✅ Respect your privacy rights
- ✅ Use privacy-respecting Apple frameworks
- ✅ Keep your journal private

---

**Thank you for trusting DayflowJournal with your thoughts and reflections. Your privacy is the foundation of everything we build.**

---

**This Privacy Policy is effective as of January 11, 2026.**

**Last Reviewed:** January 11, 2026  
**Next Scheduled Review:** July 11, 2026

---

**Document ID:** PRIVACY-POLICY-v1.2  
**Compliance:** GDPR, CCPA, COPPA, UK GDPR, Apple App Store Guidelines