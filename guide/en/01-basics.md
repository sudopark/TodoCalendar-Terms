# 1. The basics

[← Contents](./README.md)

---

## The calendar

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Calendar" width="280">

The month grid is the home screen. Swipe left and right to move between months, tap a day to open its event list underneath.

- Each day shows a colored bar per event, plus a **+N** marker when the day has more events than the row can show.
- The day list is ordered: untimed to-dos → timed to-dos → schedules → holidays → external calendar events.
- Tap the header to jump to any date, or use **Move date** to pick one directly.

How much each day shows is up to you — the amount of detail per event, text size, colors, holiday names, and the lunar calendar. [Personalization](./05-personalization.md) covers each setting by name.

---

## To-dos and schedules

The app has two kinds of events, and the difference is whether it's something you check off.

| | To-do | Schedule |
|---|---|---|
| Time | Optional | Required |
| Completion | Yes — check it off | No |
| Without a time | Stays in **Current to-dos** until you finish it | Not possible |

A **to-do without a time** is for something you need to do soon but haven't scheduled. It sits at the top of the calendar and in the Current to-dos widget until it's done.

You can convert either way at any time — **Convert to schedule** / **Convert to to-do** from the event's more menu. Converting a to-do to a schedule requires a time.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Event detail" width="280">

Every event can carry a **location** — with a map preview, and one tap to open it in your preferred maps app — plus a **link** with its own preview, and a **memo**.

---

## Adding events

Three ways to add an event, depending on how much you want to type:

- **Quick add** — the input field at the bottom of the day list. Type a name, press return, and the to-do is created.
- **Full detail** — tap **+** to open the editor with time, repeat, reminders, event type, location, link and memo.
- **AI quick input** — describe it in plain language and let the app build the event. See [AI quick input](./02-ai-input.md).

A to-do needs only a name. A schedule needs a name and a time.

---

## Repeating events

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Repeat options" width="240">

Instead of making you build a repeat rule out of dropdowns, the app reads the date you picked and offers ready-made options for it. Choose a Thursday and the list offers **Every Thursday** and **The third Thursday of every month**.

**Common intervals**

- Every day
- Every Week · Every 2 Weeks · Every 3 Weeks · Every 4 Weeks — on the same weekday as the event
- Every Month — on the same date each month
- Every Year
- Every year (lunar calendar) — for birthdays and anniversaries kept on the lunar calendar

**By position in the month**

- Every Weekday — Monday through Friday. Offered when the event starts on a weekday
- All days of the last week of every month
- The first / second / third / fourth / last *day of the week* of every month — for things like "the last Friday of the month"

**Repeat Ends**

Once you pick a repeat, choose how it stops: **Never**, **On** a specific date, or **After** a number of occurrences.

Repeating to-dos behave differently from repeating schedules:

- An uncompleted repeat stays visible on today's calendar even after its time passes — it doesn't move on to the next occurrence by itself.
- Completing it moves that occurrence to Completed to-dos and creates the next one.
- **Skip this to-do** moves you to the next occurrence without marking it done.
- When the repeat has an end condition and there is no next occurrence, the series finishes.

When you edit or delete an occurrence of a repeating event, you choose the scope: **only this time**, **from this time on**, or **all events**.

For events on a connected external calendar, the lunar option isn't offered — external calendars have no way to store a lunar repeat rule.

---

## Event types and colors

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Event types" width="280">

Event types are your categories, and they carry the color an event shows on the calendar. Create as many as you like, each with its own color.

- Toggle a type off to hide every event of that type from the calendar — useful for muting a busy work calendar without disconnecting it.
- Deleting a type lets you keep or delete the events attached to it.
- Set a **default event type** so new events land in the right place without picking every time.

Holidays and connected external calendars get their own types, so you can hide those independently too.

---

## Reminders

Set as many reminders per event as you need.

- **Timed events** — at the event time, or 1 / 5 / 10 / 15 / 30 minutes, 1 / 2 hours, 1 / 2 / 7 days before.
- **All-day events** — 9 a.m. or noon on the day, or 9 a.m. 1 / 2 / 7 days before.
- **Custom** — pick any offset you want.

Defaults for timed and all-day events are set separately in Settings, so new events already have their reminders set. Reminders need notification permission; the app points you to iOS Settings if it's off.

---

## Foremost event

Pin the one thing you cannot miss. The foremost event stays at the top of the calendar no matter what date you're looking at, and it has its own widget.

To-dos and non-repeating schedules can be set as foremost. Repeating schedules cannot.

---

## Uncompleted to-dos

To-dos whose time has already passed without being completed are collected in an **Uncompleted to-dos** section at the top of the calendar, so a missed to-do doesn't stay buried on a past date.

Untimed to-dos and future to-dos are not counted as uncompleted — they're simply not due yet. You can hide the section entirely in Settings if you'd rather not see it.

---

## Completed to-dos

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Completed to-dos" width="280">

Everything you check off is kept, grouped by when you finished it — today, yesterday, this month, then by month and year.

- Undo a completion to bring the to-do back.
- Clean up in bulk: delete everything, or everything older than 1 / 3 / 6 months or a year.

---

## Sharing

Share **a day, a week, or a month** as text or as an image card.

Before sharing you can filter which event types to include and choose whether type names appear, so you can send someone your week without exposing everything on it.

---

[← Contents](./README.md) · [Next: AI quick input →](./02-ai-input.md)
