# Privacy Policy for Traceless

*Last Updated: September 12, 2026*

**Traceless** ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how our application handles your data.

Traceless removes hidden metadata — location, camera serials, timestamps, and AI provenance tags — from your photos and videos. It is built so that this work never needs to leave your device.

## 1. No Data Collection

Traceless is a fully offline application. We do not collect, store, transmit, or sell any of your personal data, photos, videos, or usage statistics.

* We do not require you to create an account.
* We do not use third-party analytics (such as Google Analytics, Firebase, or Mixpanel).
* We do not use tracking cookies, advertising identifiers, or attribution SDKs.
* The application contains no networking code. It does not have the ability to upload your media.

## 2. Photos and Files Access

To clean your media, Traceless needs permission to read the photos and videos you select.

* **What we read:** Only the specific files you choose in the system picker. Traceless never browses your library on its own.
* **How it works:** Files are copied into the app's own private storage, cleaned there using Apple's ImageIO and AVFoundation frameworks, and written out as new files.
* **Your originals are never modified.** Traceless only ever creates cleaned copies. The original file in your library is left exactly as it was.
* **Saving:** If you choose to save a cleaned copy back to your photo library, Traceless requests add-only permission. It cannot read or delete your existing photos with that permission.

## 3. On-Device Processing

All metadata inspection and removal happens locally on your device using Apple's system frameworks. Your photos and videos are never uploaded to our servers, because we do not operate any servers.

## 4. Local Data Storage

The following is stored locally on your device and never transmitted:

* **Your settings** — the cleaning profile you have chosen and your re-encode quality preference, stored using `UserDefaults`.
* **Your activity history** — a record of files you have cleaned, stored in the app's private container.

Your activity history deliberately stores **counts only**. It records how many metadata fields were removed and from which categories. It never stores the metadata values themselves, so the history cannot leak the location, serial number, or timestamps that were removed. It does not store your photos or videos.

* **Cleaned copies** are written to the app's temporary storage so you can save or share them. They are removed when you clear the list, and the system may purge them at any time.
* If you delete the app, all of this data is removed with it.

## 5. Subscriptions and In-App Purchases

Traceless offers unlimited cleaning through an auto-renewing monthly subscription.

* **Payment Processing:** All payments are processed entirely and securely by Apple through your Apple Account. We do not collect, process, receive, or have any access to your credit card information, billing address, or other financial details.
* **Purchase Validation:** We receive only an anonymous entitlement from Apple's StoreKit framework confirming whether a subscription is active. This is used solely to unlock unlimited cleaning locally on your device. It contains no personal information and is not sent anywhere by us.

## 6. Children's Privacy

Traceless does not collect personal information from anyone, including children under the age of 13.

## 7. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with a revised "Last Updated" date.

## 8. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

**Email:** yadubhati19@gmail.com
