# The Penguins Club — Events Registry 🐧📅

Welcome to the official events repository for [The Penguins Club](https://thepenguins.club).

This repository serves as the public, version-controlled event board for The Penguins Club meetups, workshops, hackathons, and unconferences. Events submitted here as GitHub Issues are automatically fetched and rendered on the official website at [thepenguins.club/events](https://thepenguins.club/events) and published as an iCalendar (`.ics`) subscription feed.

---

## 🚀 Proposing a New Event

1. Go to the [**Issues** tab](https://github.com/the-penguins-club/events/issues) in this repository.
2. Click **[New Issue](https://github.com/the-penguins-club/events/issues/new/choose)**.
3. Select **📅 New Community Event** (Interactive Form or Markdown).
4. Fill in the event details:
   - **Title**: Official public name of the event.
   - **Date & Time**: ISO 8601 timestamps (e.g. `2026-11-07T13:30:00+06:00` for BST/Dhaka).
   - **Location**: Venue name, address, and venue type (`in-person`, `outdoor`, `virtual`, or `hybrid`).
   - **Agenda & Speakers**: Structured breakdown of the session timeline and facilitators.
   - **Prerequisites & What to Bring**: Guidance for attendees.
5. Click **Submit new issue**.

---

## 🏷️ Issue Labels & Statuses

- `event` (Required): Identifies the issue as an active event for the website engine.
- `upcoming`: The event is scheduled in the future and open for registrations.
- `completed`: The event has concluded.
- `cancelled`: The event has been called off.

---

## 🌐 Website & Calendar Integration

- **Live Website**: [thepenguins.club/events](https://thepenguins.club/events)
- **Universal iCalendar Feed**: `https://thepenguins.club/events.ics`
- **Main Website Codebase**: [The-Penguins-Club/web](https://github.com/The-Penguins-Club/web)

---

## 💬 Community & Discussion

- **Telegram**: [@penguinsclubnetwork](https://t.me/penguinsclubnetwork)
- **Code of Conduct**: Be welcoming, respectful, and encouraging to all open-source explorers.
