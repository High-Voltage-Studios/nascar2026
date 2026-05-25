# Update
**NASCAR Panel — v1.4**

https://high-voltage-studios.github.io/nascar2026/
**New Features**

Hub — All Roles — Every role now has a Hub button in their topbar. Opens as a full-screen overlay above any role's screen. Tabs: Schedule, Rulebook, Commentary, Team Radio, Polls, and Rulings. All roles can send Team Radio messages from the Hub.

Driver Polls — Race Control can post live polls from the Polls tab. All roles vote from their Hub with real-time vote bars. RC can restrict votes to racers only, and can close a poll at any time. Result announced in the radio feed on close.

Steward Decisions — RC posts formal rulings from the Rulings tab. Each decision shows as a highlighted card in every role's Hub, creates an entry in the incident feed, and appears on the public page.

Public Race Page — A no-login summary page viewable by anyone. Shows current flag, points standings, recent incidents (non-critical, 1-min delay), and steward decisions. Auto-refreshes every 30 seconds. Open via the Public button in the Hub header.

# Changes

Network Administration — All system settings are now managed here: all passwords, sub-role passwords, role access control, lockout mode, TV code, and a broadcast tool to push a full-screen alert to any role or all users at once.

RC Admin — Now contains operational quick settings only. System configuration has moved to Net Admin.
Announcements — Broadcast messages from RC and Net Admin now reach Marshals, Spectators, and Scorers in addition to Racers.

# Bug Fixes

Hub overlay was rendering behind the Spectator and Scorer screens

Hub Polls and Rulings tabs were not switching correctly

Logout did not close the Hub overlay or Public page

Net Admin settings were not pre-populated when opening the panel

Login buttons were unresponsive on mobile and other devices due to a tap event handling
