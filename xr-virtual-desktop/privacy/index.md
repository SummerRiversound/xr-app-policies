---
---

# Deskloom privacy policy

Effective date: 2026-11-22

Deskloom shows a Mac's screens in Android XR glasses or a headset. It has two parts: the Deskloom app on the
glasses and the Deskloom companion program on the Mac. Deskloom is made and published on Google Play by SummerRiversound ("the developer"). This policy
covers both parts.

**In short: Deskloom has no servers and no accounts. What it sends goes only between your glasses and your own
Mac on your local network. The developer receives nothing.**

## What the app sends, and to whom

Everything below travels only between the glasses and the Mac you paired them with, over your local network.
Deskloom refuses connections from addresses outside private and local network ranges and uses no relay or
internet server.

| What | From → to | Why |
|---|---|---|
| A random ID that the app makes when first used, and the glasses' model name | Glasses → your Mac | So the Mac knows which glasses it paired with and can show their name |
| Pairing messages derived from the 6-digit code shown on the Mac | Both ways | To set up a shared key without sending the code itself |
| The local network addresses of both devices | Both ways | So the video connection can be made directly between them |
| The picture of the Mac's screens | Mac → glasses | This is what the app shows. It is encrypted (DTLS-SRTP), shown and not recorded |
| Timing messages | Both ways | To keep the connection alive and show the delay on screen |

The screen picture is always encrypted. The other messages in the table (ID, model name, pairing exchange,
addresses, timing) are not encrypted: the stream start is checked with the pairing key, so no other device can
pose as your Mac or your glasses, but another device on the same local network could read those messages. The
pairing exchange is built so that reading it does not reveal the code or the key.

The app does not use the camera, microphone, location, contacts, files, or any advertising or analytics service.
It does not send keyboard or mouse input to the Mac.

## What is stored

- **On the glasses**, in the app's private storage: the random ID, the paired Mac's ID, name and last address,
  the pairing key (encrypted with a key held in the device's Android Keystore), and the panel size you chose.
  None of this is backed up or carried to a new device.
- **On the Mac**, in `~/Library/Application Support/Deskloom/paired.properties` (readable only by your user
  account): the Mac's own ID, and for each pair of glasses its random ID, name and pairing key.
- Screen pictures are not stored on either device.

## Deleting your data

- Glasses: uninstall Deskloom, or clear its storage in the system settings.
- Mac: start the companion with `--forget` to forget all paired glasses, or delete the folder
  `~/Library/Application Support/Deskloom`.

Because the developer never receives any of this data, there is nothing held by the developer to delete.

## Children

Deskloom is not directed at children.

## Changes

Changes to this policy will be posted at this address with a new effective date.

## Contact

Questions about this policy or your data: SummerRiversound, summer.riversound@gmail.com
