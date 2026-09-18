---
layout: default
title: Privacy Policy
---

# Privacy Policy — Radio Silence

**Last updated: 17 September 2026**

Radio Silence is a cooperative party game published by Adam B. This policy
explains what the app collects, why, and how long it keeps it. It covers the
Android and iOS apps with the identifier `com.adambm.radiosilence`.

Contact: **RadioSilenceGame1@gmail.com**

## The short version

There are no accounts. The game never asks for your name, email, phone number,
contacts or location. What it does store is a display name you type in, a room
code, and the state of the game you are playing — and it deletes all of it
within days.

The parts that do collect data about you are the advertising and payment
services the app uses, both run by Google. Those are described below.

## What the game itself stores

To let several phones play the same game at the same time, the app stores the
following in Google Firebase (Firestore):

- **An anonymous user ID.** A random string Firebase generates the first time
  you open the app. It is not linked to an email, a phone number or a Google
  account, and it tells us nothing about who you are. It exists so the server
  can tell one player at the table from another, and so that only you can read
  your own hand of cards.
- **A display name.** Whatever you type when you create or join a room. This is
  free text and it is shown to the other players in your room. If you type your
  real name, your real name is what the other players see — so type whatever
  you like.
- **The room and its game state.** A five-character room code, which players
  are in the room, how many cards each is holding, the cards that have been
  played, lives remaining, and the game settings the host chose.
- **Your hand of cards**, stored separately and readable only by you. Hidden
  information is the whole point of the game, so the server enforces this
  rather than trusting the app.

No advertising identifier, device identifier, IP address or location is stored
by the game itself.

## How long it is kept

Automatically deleted, by a job that runs every six hours:

- **Finished games: 6 hours** after the run ends.
- **Abandoned rooms: 48 hours** after the last activity — a lobby nobody
  started, or a game someone walked away from.

After that the room and every hand in it are gone. Nothing is archived.

The anonymous user ID lives on your device until you uninstall the app or clear
its data. It is not useful to anyone on its own.

## Advertising

The app shows an advertisement from **Google AdMob** after a run ends, and not
during play. Buying the supporter purchase described below removes them
permanently.

AdMob is operated by Google and collects data of its own to select and measure
ads — typically your device's advertising ID, IP address, general device
information and interactions with the ads it shows. This happens inside
Google's SDK; the data goes to Google, not to us, and we never see your identity.

- Google's policy: https://policies.google.com/technologies/ads
- How Google uses data from apps that use its services:
  https://policies.google.com/technologies/partner-sites

**Your choices.** You can reset or delete your advertising ID at any time in
your device settings (Android: Settings → Google → Ads; iOS: Settings →
Privacy & Security → Tracking). If you are in the EEA, the UK or Switzerland,
the app asks for your consent before showing personalised ads and you can
change that choice later from the Settings screen in the game. On iOS the app
also asks before tracking you across other companies' apps, and declining does
not stop you from playing.

## Purchases

The app offers an optional one-time purchase that supports development and
removes the ads. It is processed by **Google Play Billing** (Android) or the
**App Store** (iOS). Your payment details go to Google or Apple and are never
seen by, or sent to, this app. We receive only confirmation that a purchase was
made, which is stored on your device so the app knows to stop showing ads.

## Children

Radio Silence is not directed at children and is not intended for anyone under
13. We do not knowingly collect information from children. If you believe a
child has provided information through this app, email the address above and it
will be deleted.

## Where the data goes

Firebase and AdMob are operated by Google LLC, and data may be processed on
servers outside your country, including in the United States. Google's
infrastructure and safeguards are described at
https://firebase.google.com/support/privacy

## Your rights

Because there are no accounts, there is no login to identify you by. To have
data associated with you removed:

- **Uninstall the app**, or clear its data. Your anonymous ID goes with it, and
  any room you were in is deleted within 48 hours anyway.
- Or **email the address above** with your room code, if a game is still in
  progress and you want it removed sooner.

If you are in the EEA or the UK, the lawful basis for processing the game data
above is the legitimate interest of making a multiplayer game work; for
personalised advertising it is your consent, which you may withdraw at any time.

## Changes

If this policy changes in a way that affects what is collected, the "last
updated" date above changes and the new version is published at this same
address before the change takes effect.
