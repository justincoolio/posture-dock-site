# Privacy Policy for Posture-Dock

June 15, 2026

Posture-Dock ("the App") is an iOS application that uses motion data from supported AirPods to help you understand changes in your head and neck alignment. This Privacy Policy explains how the App handles information.

## Summary

Posture-Dock is designed to process posture information on your device. The App does not operate an account system or developer-controlled server and does not include advertising, tracking, analytics, or third-party data-collection SDKs.

## AirPods Motion Data

With your permission, Posture-Dock uses Apple's CoreMotion framework and `CMHeadphoneMotionManager` to access motion data from supported AirPods. This data can include head orientation, rotation, acceleration, and timestamps.

The App uses this data to:

- Confirm that supported AirPods motion is available.
- Calibrate a neutral head position.
- Compare live head movement with that calibrated position.
- Provide posture status, sound, and haptic feedback.
- Calculate session statistics.

Raw AirPods motion samples are processed on your device. They are not transmitted to the developer or third parties and are not saved in your session history.

## Posture Calibration Data

During calibration, the App temporarily processes motion samples to calculate a neutral head-position baseline and stability measurements. Calibration samples and the resulting baseline are held in memory for the active experience. They are not uploaded, shared, or written to persistent session history.

The App estimates head and neck alignment from AirPods motion. It does not use a camera and does not directly measure your back or provide a medical diagnosis.

## Session History

When a posture session ends, the App stores a summary locally on your device using Apple's SwiftData framework. A session record may contain:

- A randomly generated session identifier.
- Start and end dates.
- Session duration.
- An average posture score.
- Time classified as good, warning/transition, or bad posture.
- The number of posture reminders.

Session history does not contain raw AirPods motion samples or calibration baseline values. It is not synchronized to a developer server or CloudKit. You can delete session records from the Session History screen. You can also remove the App and its local app-container data through iOS.

## App Preferences

Posture-Dock stores settings on your device using `UserDefaults`, including posture sensitivity, reminder delay, sound and haptic choices, onboarding completion, and local counters used to decide when to request an App Store review.

## Network Activity and Third-Party Services

The App does not make developer-authored web API requests and does not include third-party analytics, advertising, tracking, cloud-storage, crash-reporting, Firebase, or RevenueCat SDKs.

Posture-Dock uses Apple system services for the App Store review prompt. Apple may process your interaction with the App Store under Apple's own privacy policy. Posture-Dock does not receive the content of an App Store review through the App.

## Feedback and Email

If you choose "Send Feedback," the App opens an email composer or your default mail application. Nothing is sent unless you choose to send the email. Your email address, message, and any attachments you add will be processed by your email provider, the recipient's email provider, and the App's support recipient.

Support messages may be retained as reasonably necessary to respond, troubleshoot issues, maintain support records, or comply with legal obligations. Do not include sensitive personal, health, or confidential information that is not needed for your request.

## Permissions

Posture-Dock requests Motion & Fitness access so it can receive headphone-motion data from supported AirPods. You can deny or later change this permission in iOS Settings. Without motion access, AirPods posture tracking and calibration will not function.

The App does not request access to your camera, microphone recording, photos, contacts, location, HealthKit data, Bluetooth scanning, or tracking permission.

## Diagnostics

The App writes limited technical events to Apple's unified logging system, such as posture-state transition times, alert cue names, audio route types, and playback errors. The App does not intentionally log raw AirPods motion values, calibration baseline values, session-history records, email content, or user identifiers. The App does not transmit these logs to a developer-controlled server.

## Data Sharing and Sale

Posture-Dock does not sell personal information. It does not share motion, calibration, or session-history data with advertisers, data brokers, analytics providers, or other third parties. Information is disclosed only when you choose to send feedback, when Apple provides an operating-system or App Store service, or when disclosure is required by law.

## Data Retention and Deletion

Raw motion and calibration data are used transiently in memory. Session summaries and preferences remain on your device until you delete applicable session records, reset or change settings, or remove the App.

Feedback emails may remain with the involved mail providers and support recipient according to their retention practices. To request deletion of a support message, contact us using the information below and provide enough detail to locate the message.

## Security

Posture-Dock relies on iOS app-container protections for locally stored data. No method of storage or transmission is completely secure, but the App minimizes risk by keeping motion analysis and session history on the device and by not operating a remote user-data service.

## Children's Privacy

Posture-Dock is not directed to children under 13, and the developer does not knowingly collect personal information from children through the App. Because the App does not provide accounts or automatically transmit user data, its core posture features remain on the device. If you believe a child has sent personal information through a support email, contact us so the request can be reviewed and the information deleted where appropriate.

## Changes to This Privacy Policy

This Privacy Policy may be updated when the App's features, data practices, or legal obligations change. The revised policy will be posted at the App's Privacy Policy URL with a new effective date. Material changes will be communicated as required by applicable law.

## Contact Information

Developer or legal entity: Justin Eiskamp 
Privacy contact email: justincodes@icloud.com

