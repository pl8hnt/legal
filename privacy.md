---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for PL8HNT

**Last Updated: May 23, 2026**

PL8HNT is operated by Brian Buck as an individual developer. This Privacy Policy describes how PL8HNT ("we," "us," or "our") collects, uses, and discloses information when you use our mobile application (the "App"). We are committed to protecting your privacy and ensuring you have a positive experience on our App.

## INFORMATION WE COLLECT

### Location Information
- **Proximity Data**: Our App uses your device's location services to detect proximity to jurisdiction boundaries within the United States, Canada, and Mexico, solely for the purpose of creating in-app scores and enhancing your gameplay experience.
- **Important Note**: Your location data is processed locally on your device. We do not store your location information on our servers, and your location data is not transmitted to us or any third parties.

### User Content
- **Username and Avatar**: On first launch, the App generates a random identifier and stores it locally on your device. This identifier is used to seed a quirky generated username (e.g. "Funky Chicken") and a small generated pixel avatar. The username and avatar seed are stored locally on your device. Avatar image bytes are never transmitted off your device; other devices in a shared trip regenerate the avatar from the same seed on their own.

### Shared Trip Information (Optional)

If — and only if — you choose to create or join a shared road trip, the following information is sent to our backend (hosted on Supabase) so that other devices in the same trip can see updates in real time:

- **Device identifier**: a random UUID generated on your device. No personally identifiable information.
- **Generated display name**: the quirky username (e.g. "Funky Chicken") chosen on first run. We do not collect your real name; the display name is randomly generated from a public word list.
- **Trip name**: the trip title chosen by whoever created the trip (e.g. "Memorial Day 2026").
- **Tap events**: which jurisdiction (US state, Canadian province, or Mexican state) was tapped, the score awarded for that tap, and timestamps. **No location data is included** — only the jurisdiction code, computed locally on your device.

We do **not** collect or transmit:
- Your real name, email, phone number, or any other contact information
- Your location coordinates (these stay on your device, used only to compute the score that rides with each tap event)
- Avatar image bytes (each device regenerates the avatar from the random seed)
- Photos, contacts, or any other content from your device

**Authentication**: When you create or join a shared trip, the App signs you in to our backend anonymously. We do not ask for or store an email, password, or other login credential. The anonymous session is bound to a random identifier and exists only to authorize your device's reads and writes against the shared-trip data.

**Automatic Deletion**: Shared trip data is automatically deleted **30 days after the last activity on the trip**, with a hard cap of **90 days from the trip's creation date**. After deletion, the trip and all its events no longer exist on our backend. Your personal local tap counts (stored only on your device) are unaffected and remain on your device as long as the App is installed.

You can leave a shared trip at any time. Doing so removes you from that trip's membership server-side; your local tap counts remain on your device.

## HOW WE USE YOUR INFORMATION

We use the information we collect to:
- Provide, maintain, and improve our App
- Calculate scores based on proximity to jurisdiction boundaries
- Synchronize tap events between devices on the same shared trip (when you opt in to sharing)

## DATA SHARING AND DISCLOSURE

### Third-Party Service Providers

- **Sentry** — error tracking and crash reporting. Information shared with Sentry is limited to technical data about app crashes and performance issues, and does not include your location data, avatar, or any personally identifiable information.
- **Supabase** — backend hosting for the optional shared-trip feature. Only the data described in the "Shared Trip Information" section above is sent to Supabase, and only when you opt in to creating or joining a shared trip.

### Legal Requirements
We may disclose your information if required to do so by law or in response to valid requests by public authorities (e.g., a court or government agency).

## DATA SECURITY

We implement appropriate technical and organizational measures to protect the information we collect and maintain. Shared trip data is transmitted over HTTPS and is gated by Postgres row-level security policies so that participants can only see data for trips they have been approved to join. However, no method of transmission over the Internet or electronic storage is 100% secure, so we cannot guarantee absolute security.

## CHILDREN'S PRIVACY

PL8HNT is intended for users of all ages. We do not knowingly collect personally identifiable information from children under 13. The App does not require an email or account login. Shared trips use only the device's random identifier and a randomly generated username; no real-name information is requested or stored. If you are a parent or guardian and you believe we have collected information from your child, please contact us so that we can take necessary actions.

## INTERNATIONAL USERS

The App is intended for users located in the United States, Canada, and Mexico. If you are accessing our App from outside these countries, please be aware that your information may be processed in a manner consistent with this Privacy Policy.

## YOUR CHOICES

### Location Permissions
You can control location permissions through your device settings. Please note that certain features of our App require location services to function properly. If you disable location permissions, these features may not work as intended.

### Camera Permissions
The App requests camera access only to scan QR codes for joining shared trips. If you don't use the shared-trip feature, you can deny camera access without affecting any other part of the App.

### Shared Trip Data
You can leave a shared trip at any time from the in-app members screen. Leaving removes you from that trip's membership server-side; your local tap counts remain on your device. To delete a shared trip you created, use the trip-card delete action — this removes your participation server-side and deletes the local trip.

### Device Storage
User data stored locally on your device can be removed by uninstalling the App.

## CHANGES TO THIS PRIVACY POLICY

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date at the top of this page. You are advised to review this Privacy Policy periodically for any changes.

## CONTACT US

If you have any questions about this Privacy Policy, please contact us at:
pl8hnt@gmail.com

## APP STORE COMPLIANCE

### Apple App Store
This Privacy Policy complies with the Apple App Store Review Guidelines, including requirements for apps that use location services and apps that allow anonymous account creation.

### Google Play Store
This Privacy Policy complies with the Google Play Developer Program Policies, including requirements for apps that use location services and apps that handle user-generated content via shared trips.