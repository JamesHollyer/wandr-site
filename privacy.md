# Wandr privacy policy

_Last updated 22 October 2026._

Wandr is a festival companion app that talks to Meshtastic radios. This page explains what the app collects, where it goes, and what you can turn off. Wandr is operated by James Hollyer. Contact: wandr.festival@gmail.com.

The short version: your location history stays on your phone, your friends see you only inside groups you joined, and we do not sell anything to anybody.

## What stays on your phone

- **Your GPS track.** Wandr records your position while tracking is on, so it can show which stages you visited. This log never leaves your phone unless you export it yourself.
- **Positions heard over the radio.** Positions, battery levels and messages from your friends' radios are stored on your phone only.
- **Your radio's original settings.** Saved so they can be restored.

## What goes over the radio

While you are in a group, your radio broadcasts your position on the group's private, encrypted channel. Only radios with the group key can read it. Messages you send in a chat room go to everyone on that room's channel; a public room is readable by anyone on the same mesh, including people who are not using Wandr.

Radio traffic travels through other people's radios to reach your friends. That is how a mesh works. Encrypted channel contents stay private, but the fact that a radio is transmitting, and its node number, are visible to anyone listening nearby.

## What is stored on our server

Wandr uses a hosted database (Supabase) for accounts, groups and the pack directory. It stores:

- your email address and a password hash, used only to sign you in;
- your handle, display name and chosen emoji;
- your radio's node number, so your friends' apps can tell which radio is yours;
- your friendships and group memberships, and each group's channel key;
- festival packs and mesh profiles you publish, which are public to anyone using the app;
- festivals you create (name, dates, place) and which festival each of your crews is registered for;
- a camp marker, if you set one: its coordinates and name, shared with the crews you are in;
- totems you register: name, emoji, photo and the totem radio's node number. People at the same festival may be shown the name and photo as a landmark hint; only your crew sees where it is.

**Your live GPS position is not sent to the server.** The only coordinates stored there are ones you place on purpose: your camp marker and a festival's location.

## Usage statistics

Wandr currently sends no usage statistics, analytics or crash reports to anyone. If a future version adds them, this page and the app will say so first, and you will be able to turn them off.

## What we do not do

No advertising. No third-party advertising or tracking SDKs. No selling, renting, or sharing of your personal information with third parties, other than the hosting providers that run the database and store the usage statistics described above on our behalf.

## Permissions

- **Bluetooth**: to connect to your Meshtastic radio.
- **Location, including in the background**: to point you toward friends, to share your position with your group through the radio, and to record stage visits while the app is in the background. You can stop this at any time with "Stop tracking".
- **Camera**: to scan channel QR codes.
- **Photos and camera**: to pick a festival map image, and to photograph a totem you register. Totem photos are stored on our server and shown to people at the same festival.

## Children

Wandr is not intended for children. You must be at least 16 to create an account, and we do not knowingly collect information from anyone under 13. If you believe a child has created an account, email us and we will delete it.

## Your choices and rights

- **See or correct your data**: most of it is visible in the app; email us for the rest.
- **Delete your phone data**: sign out and uninstall.
- **Delete your account and server data**: email the address below from the account's email address and it will be removed within 30 days. Packs you published may remain available to people who already downloaded them.
- **Turn off usage statistics**: Settings, at any time.
- **Residents of California, the EU, the UK, and other places with data-protection laws** have additional rights to access, correct, delete, and port their information, and to object to its processing. Email us and we will honour them. We do not sell personal information or share it for cross-context behavioural advertising.

## Retention

Account and group records are kept while your account exists. Usage statistics are kept for at most 24 months. Published packs and mesh profiles remain until you or we remove them.

## Changes

Wandr is beta software and this policy will change as it grows. If a change is significant we will say so in the app and update the date above.

## Contact

wandr.festival@gmail.com
