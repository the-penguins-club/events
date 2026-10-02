---
name: "📅 New Community Event (Markdown / Frontmatter)"
about: "Template for creating an event issue using YAML frontmatter and markdown sections"
title: "[Event]: "
labels: ["event", "upcoming"]
---

```yaml
title: "Touch Grass: The Unplugged Linux Gathering & Nature Unconference"
slug: "touch-grass"
trackTag: "SUPER EVENT • OUTDOOR HACKER PICNIC & KEY-SIGNING"
dateBadge: "07 November 2026 • 13:30 BST"
startDateIso: "2026-11-07T13:30:00+06:00"
endDateIso: "2026-11-07T18:00:00+06:00"
timeString: "Saturday • 13:30 - 18:00 BST (Sunset)"
location: "Ramna Park Lake Amphitheatre & Banyan Green, Dhaka"
venueName: "Ramna Park Green Space (Near Lake Steps)"
venueAddress: "Moulana Bhashani Rd, Ramna, Dhaka 1000, Bangladesh"
venueType: "outdoor" # outdoor | in-person | hybrid | virtual
theme: "grass" # grass | hacktoberfest | linux | git | selfhost
isSuper: true
superBadge: "SUPER EVENT 🌿"
cost: "100% Free • Open to All"
capacity: "Unlimited • Open Lawn"
registrationUrl: "https://t.me/penguinsclubnetwork"
image: "/images/meetups/meetup-touch-grass.svg"
```

## Short Summary
An unplugged, open-air super gathering! Step away from backlit screens, power down the daemons, and touch actual grass with fellow Linux and FOSS enthusiasts. Featuring solar-powered LoRa mesh radios, an open-air GPG key-signing party, an offline Kiwix knowledge mirror, acoustic lightning talks, frisbee, and lawn snacks.

## Full Overview
In a world dominated by endless CI/CD runs, flickering terminal windows, and hyper-connected screens, we often forget the raw physical reality beneath our feet. "Touch Grass" is The Penguins Club's signature super unconference: a deliberate return to nature, fresh oxygen, and unplugged peer-to-peer connection.

Leave your AC server rooms behind. Bring a picnic blanket, your portable solar packs, your favorite offline hardware projects, and your physical presence. We will gather under the historic trees of Ramna Park for an afternoon of peer-to-peer mesh networking, Web-of-Trust cryptographic signing, community tea, and real-world conversations with people who cherish software freedom.

Zero Wi-Fi dependencies. Zero cloud servers. Just pure offline software freedom, decentralized mesh radios, and open-air solidarity.

## Key Highlights & Activities
- 🌿 100% Certified Grass-Touching: Reconnect with sunlight, trees, and your fellow humans without notifications.
- 📡 Solar & Battery LoRa Mesh Lab: Deploying Meshtastic & Briar peer-to-peer off-grid communication nodes across the park perimeter.
- 🔑 Sunlight GPG Key-Signing Protocol: Cross-sign public keys in person to strengthen our community Web of Trust (bring printed fingerprints!).
- 🎒 Offline Digital Ark with Kiwix: Experience entire offline mirrors of Wikipedia, ArchWiki, and OpenStreetMap running on low-power Raspberry Pi single-board computers.
- ⚡ Unplugged Lightning Talks: Zero projector slides! 5-minute talks with handheld mini-whiteboards, paper sketches, and genuine acoustic voice projection.
- 🍉 Lawn Picnic & Frisbee Tournament: Fresh seasonal fruits, hot tea, samosas, and open-air games as the sun dips below Dhaka's skyline.

## Agenda & Timeline
```yaml
- time: "13:30 - 14:00"
  title: "Check-In, Picnic Mat Circle & Fingerprint Verification"
  speaker: "TPC Welcome Crew"
  description: "Find our circle under the giant banyan tree by the lake, lay out mats, grab your badge, and verify GPG fingerprint sheets."
- time: "14:00 - 14:40"
  title: "Opening Circle: Digital Ecology & The Art of Disconnecting"
  speaker: "The Penguins Club Core"
  description: "A grounded conversation on developer burnout, open-source sustainability, local resilience, and mindful computing."
- time: "14:40 - 15:30"
  title: "Hands-On Lab: Deploying Off-Grid LoRa & Meshtastic Networks"
  speaker: "Hardware & Radio SIG"
  description: "Flashing ESP32 and nRF52 LoRa boards, configuring repeaters, and testing encrypted text packets."
- time: "15:30 - 16:30"
  title: "Acoustic Unplugged Lightning Talks & FOSS Demos"
  speaker: "Community Open Floor"
  description: "Five-minute talks with paper index cards, chalkboards, and working offline gadgets."
- time: "16:30 - 17:15"
  title: "Open-Air GPG Key-Signing Party"
  speaker: "Security & Web of Trust WG"
  description: "Structured peer verification of public keys and fingerprint hashes as the sun drops."
- time: "17:15 - 18:00"
  title: "Sunset Frisbee, Tea & Closing Reflection"
  speaker: "All Participants"
  description: "Hot spiced tea, fresh fruit, samosas, frisbee toss, and sunset community photo."
```

## Prerequisites
- Basic curiosity about GNU/Linux, self-hosting, and software freedom.
- No prior radio or hardware experience required — everyone from first-time Linux users to seasoned sysadmins is welcome.
- If participating in the GPG key-signing party: generate your key beforehand and bring at least 15 printed fingerprint slips.

## What to Bring
- A picnic blanket, mat, or lightweight folding stool.
- Reusable water bottle and personal tea mug (we observe strict zero single-use plastic).
- Solar power bank or fully charged USB battery pack.
- Your offline gadgets: PinePhone, Raspberry Pi, LoRa radio, or retro e-reader.
- Printed GPG fingerprint strips (if joining the key-signing circle).

## Facilitators & Speakers
```yaml
- name: "Fahim Rahman"
  role: "Hardware SIG Lead & Mesh Tinkerer"
  github: "fahim-radio"
  bio: "Amateur radio operator (HAM) and builder of solar-powered packet repeaters."
- name: "Nafis Sadik"
  role: "Cryptography & Privacy Steward"
  github: "sadik-crypto"
  bio: "Security researcher focusing on GPG Web-of-Trust, reproducible builds, and Linux kernel signing."
- name: "Sumaiya Tasnim"
  role: "TPC Community Host & Education Coordinator"
  github: "sumaiya-foss"
  bio: "Open source documentation writer and advocate for women in systems programming."
```

## Frequently Asked Questions
```yaml
- question: "Is there any ticket or registration fee?"
  answer: "Absolutely not. All Penguins Club events are 100% free and open to everyone, funded entirely by community volunteers."
- question: "What if it rains on the day?"
  answer: "If heavy rain occurs, we will relocate to the covered amphitheatre arcade on Moulana Bhashani Road. Instant updates will be posted to Telegram."
- question: "Can I bring my laptop?"
  answer: "Yes, but remember there are no wall outlets in the park! Make sure your battery is charged or bring a power bank. Offline projects are encouraged."
- question: "Are children and families welcome?"
  answer: "Yes! Ramna Park is a public, family-friendly green space. Feel free to bring family and friends to enjoy the outdoors."
```
