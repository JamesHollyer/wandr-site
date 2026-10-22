# Wandr alpha: tester guide

Thanks for trying Wandr. It is early software built by one person for one festival. It works, it has rough edges, and your feedback decides what gets fixed first.

## What it does

Wandr connects to your Meshtastic radio and gives your friend group a compass that points at each other, a festival map with everyone's dots, stage timelines, and chat. Setup is one tap: make a group, friends join, and Wandr configures every radio to match.

## What you need

- An Android phone, or an iPhone (TestFlight link). Both have the same features.
- A Meshtastic radio with GPS on firmware 2.7 or newer. Tested on the Seeed Wio Tracker L1 Pro and the SenseCAP T1000-E; others should work.
- Bluetooth on the radio, and the official Meshtastic app **disconnected** from it. A radio accepts one app at a time.

## What Wandr changes on your radio

Be aware before you join a group:

- adds the group's private channel;
- switches the radio speed and frequency slot to the group's settings (for Seven Stars: MediumFast, slot 45, hops 3);
- turns **position sharing off on your other channels** so the radio sends exact positions only to the group;
- sets position timing (every 60 s on a private mesh; the 5-minute etiquette on the Seven Stars mesh).

Wandr saves your original settings first. **Radio tab → Restore radio settings** puts everything back and stops Wandr touching the radio. Leaving a group offers the same.

## Setup

1. Install from the Play internal-test link you were sent.
2. **Crew tab**: create an account (email + password, nothing is emailed), pick a handle.
3. **Radio tab**: Scan for radios, tap yours, enter the PIN (on screen, or `123456` for screenless boards).
4. **Crew tab**: search a friend's handle and add them, or create a group and share its invite code. Under **Advanced** pick **Seven Stars 2026** if you're going.
5. Watch the dots in the group turn green: that radio is set up.
6. **Radio tab → Start tracking** if you want stage timelines. Allow location "all the time".

Friends appear on the **Find** tab within a minute or so of a position arriving.

## Known limits

- Accounts have no email verification and no password reset yet. Don't reuse an important password.
- Positions from radios are only as good as the radio's GPS: expect 10 m outdoors, worse indoors.
- The festival map needs a pack: either download a shared one (Map tab → Browse shared packs) or make your own by photographing the map and pinning three landmarks on site.

## Reporting problems

Radio tab → Debug log shows what the app is doing. Screenshots of that, plus what you expected, are the most useful thing you can send. Export JSON on the same tab produces a file with everything the app heard; send it if asked.
