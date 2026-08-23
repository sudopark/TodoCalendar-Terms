# Google Calendar Integration & Data Policy

**Effective date: 2026-08-23**

This page explains what To-do Calendar ("the Service", "we", "us") does with your Google Calendar data. How we handle every other kind of personal data is described in the [Privacy Policy](./privacy.md).

---

## 1. What the Service is for

To-do Calendar is a personal productivity application that combines a calendar view with a to-do list, so that you can add and organise your tasks and appointments in one place.

---

## 2. Connecting Google Calendar is optional

If you want a single view of everything you have planned, you can connect your Google Calendar and see its events alongside the to-dos and schedules you keep in the Service.

The connection is entirely optional. Every core feature works without it, and you can disconnect the account at any time.

---

## 3. Scope and use of the data

**What we request, and when.** We ask for access in two steps, so that you are never asked for more than the app currently needs.

- **When you connect an account**, we ask only for read access to the events in the Google calendars you choose (`https://www.googleapis.com/auth/calendar.readonly`).
- **The first time you save or delete a Google Calendar event inside the app**, we ask you to sign in again to grant write access (`https://www.googleapis.com/auth/calendar`). If you never edit an event, we never ask for it. If you decline — or if the account belongs to an organisation that does not allow write access — the change is not made and the app tells you so.

**Why we request it.** Your Google Calendar events are shown in the Service's calendar views, event lists and widgets, giving you one screen that covers your whole schedule. Where you edit or delete such an event inside the app, we apply that change to your Google Calendar on your behalf.

**What we never do.** We do not create, change or delete anything in your Google Calendar unless you ask us to from within the app. We do not use the data for advertising, and we do not use it to train generalised artificial-intelligence models.

**Our use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.**

---

## 4. How the data is handled and stored

**It does not reach our servers.** Your Google Calendar events are never transmitted to, stored on, or retained by our servers, databases or cloud storage. The Service talks to Google directly from your device.

**It stays on your device.** Events are held in the app's local database so that they can be displayed, and they are processed there. They are removed when you disconnect the calendar account or delete the app.

**It is not shared.** We never sell your Google Calendar data, and we never share or disclose it to third parties.

Events may carry details about other people — organisers and attendees, including their names, email addresses and response status. Please keep that in mind when sharing your device.

---

## 5. Withdrawing access

You can revoke this access at any time by disconnecting the account in the app's settings, or from your [Google Account permissions page](https://myaccount.google.com/permissions). Disconnecting removes the calendar data held on your device.

---

## 6. Privacy Policy

For the full picture of how the Service handles user data, and for our security practices, see the [Privacy Policy](./privacy.md).

If you have questions, contact us at **todocalendar.help@gmail.com**.
