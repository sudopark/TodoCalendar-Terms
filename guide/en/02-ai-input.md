# 2. AI quick input

[← Contents](./README.md)

---

Describe what you want in plain language and the app builds it for you — "lunch with Sara Friday at noon", "move the dentist to next Tuesday", "mark the laundry done". No forms, no picking a date from a wheel.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-input.png" alt="AI quick input" width="280">

AI quick input requires a signed-in account. Everything else in the app works without one.

---

## What it can do

- Create to-dos and schedules, with time, repeat and event type inferred from what you said
- Change an existing event — move it, rename it, retime it
- Complete a to-do, or undo a completion
- Delete an event
- Handle several things in one request ("add gym Monday, Wednesday and Friday at 7am")

---

## Ways to send a request

### In the app

Tap the AI button on the calendar screen. The input sheet opens with two modes you can switch between at any time:

- **Voice** — speak and watch the transcription appear live. Needs microphone and speech recognition permission; if either is denied the app offers to open iOS Settings or to switch to the keyboard instead.
- **Keyboard** — type it. Useful when you're somewhere you can't talk.

### From an image

**Read from image** turns a picture into events. Take a photo or pick one from your library; the app reads the text on it — a class timetable, an event poster, a screenshot of a message — and shows you what it found so you can fix anything that came out wrong before sending.

You can attach an instruction to steer the result, like "add these as to-dos". If there's no readable text in the image, the app tells you rather than sending an empty request.

### Siri

Say **"Add with AI in To-do Calendar"** — or "Add a schedule in To-do Calendar" / "Add a to-do in To-do Calendar". Siri asks what you'd like to add, and the request runs **in the background without opening the app**. Siri replies "Got it. I'll notify you when it's done," and you get a notification when the result is ready.

### Action button

Map the Action button to the **Add with AI** shortcut. One press, say the thing, done — the app never has to come to the foreground.

### Widget and Control Center

- **Add with AI widget** — a Home Screen or Lock Screen widget that opens the AI input screen with one tap.
- **Control Center** (iOS 18 and later) — add the same control to Control Center for a swipe-down entry point.

### Share sheet

Share **text or an image from any other app** straight to To-do Calendar's AI. Reading a message with the details of a meetup, or looking at a poster in Photos — hit share, pick To-do Calendar, optionally add an instruction, and send.

The share sheet request runs in the background too. You'll get a confirmation that it was sent, and you check the result in the app.

---

## How a request runs

1. **Sent** — your request goes off. If it came from Siri, the Action button or the share sheet, you don't need to keep the app open.
2. **Processing** — the app shows progress. You can **stop** a request while it's running, though stopping discards the work in progress and it can't be resumed.
3. **Confirmation, when needed** — if the request would change something significant, the app asks you to approve it first and shows exactly what it's about to do. There's a countdown; if it expires you just ask again.
4. **Done** — the result lands on your calendar immediately, with a summary of what changed.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-result.png" alt="AI result" width="280">

Only one request runs at a time. If you send another while one is still waiting for your approval, the app tells you to deal with the first one.

---

## Credits

Each AI request spends **credits**, and your credits refill every day. How many you have left is shown at the top of the AI input screen, so you know before you send.

When you run out, AI quick input waits until the next day's refill. Everything else in the app keeps working.

---

## Permissions it may ask for

| Permission | Used for |
|---|---|
| Microphone + Speech Recognition | Voice input |
| Camera | Taking a photo for **Read from image** |
| Photo Library | Picking an existing image |
| Notifications | Telling you the result of a background request |

Each one is asked for only when you first use the feature that needs it, and the app keeps working without it — voice input falls back to the keyboard, image input to typing.

---

[← Contents](./README.md) · [Next: Widgets and Lock Screen →](./03-widgets.md)
