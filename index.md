# Voice Portal Privacy Policy

Effective date: 2026-11-16

This policy covers "Voice Portal – Transcribe & Dictate" and its optional "Voice Portal Pro" add-on (together, "Voice Portal"), a Windows 11 app from the Microsoft Store.

## The short version

- Speech recognition runs on your PC. Your voice, recordings and transcripts are never sent to us or to anyone else.
- There is no account, and there is no telemetry.
- The only network use is downloading models (when you choose to) and the Microsoft Store checking your license.
- Your library can be encrypted on disk.

## What we collect

Nothing. Voice Portal does not send us, or any third party, your audio, your text, your files, your settings, usage statistics or crash reports. We do not run servers that receive data from the app. There is no telemetry at launch. If we ever add an opt-in option such as crash reports, it will be off until you turn it on, it will say exactly what it sends, and this policy will be updated first.

## What stays on your PC

Voice Portal stores the following in its local app data folder on your PC:

- Your library: transcripts, edits, timestamps and any recordings you chose to keep.
- Your settings, custom vocabulary, per-app modes and blocklist.
- Downloaded speech models.
- Recent dictations, so text is not lost if an app refuses it.

Dictation audio is not kept unless you turn on audio retention. Files you transcribe are read from where they are. Voice Portal does not change, move or upload them. The exception is a file you send to Voice Portal with the Share menu: a copy is placed in the Imports folder of your library, and the original is left alone.

**Encryption.** Pro can encrypt your library on disk using Windows data protection, tied to your Windows account. Backups can be protected with a password you choose. We cannot recover a lost password, because we never hold it.

You control this data. "Back up library" exports your library as a zip file to a place you choose. Deleted items go to a bin and are removed for good after 30 days, or sooner if you empty the bin. Uninstalling the app removes its local data folder, but not backups or exports you saved elsewhere.

## Permissions the app asks for

**Microphone.** Used only while you are dictating (the hotkey is held or toggled on) or while you have started a recording or meeting capture. A visible indicator shows when the microphone is in use. Audio is processed on your PC.

**Full trust (runFullTrust).** Windows uses this label for a desktop app that is not confined to a sandbox. Voice Portal needs it to register a hotkey that works in every app, to show its small overlay, and to place dictated text into the app you are using. It is not used to read your files or collect information. The app only opens the files you pick.

## How dictated text is inserted

Voice Portal tries to insert text directly into the focused text box. If that is not possible it briefly uses the clipboard, then restores what was on it before. The text is marked so that it stays out of Windows clipboard history and cloud clipboard. Voice Portal refuses to insert into password fields and into elevated (administrator) or secure-desktop windows, and it never types into apps on your blocklist.

## Network use

Voice Portal connects to the internet only for these reasons:

1. **Model downloads.** A starter speech model is included in the app and needs no download. Other speech models, the optional on-device text model (used for smart cleanup and rewrite modes) and the optional speaker model (used for speaker labels) are downloaded only when you start the download yourself. The app fetches each one over HTTPS from a pinned upstream address on Hugging Face and checks it against a SHA-256 fingerprint stored in the app. Only the model file is downloaded. No executable code is downloaded. The download is an ordinary web request, so the host can see your IP address, as with any download. The app sends nothing about you or your audio. Hugging Face has its own privacy policy.
2. **Microsoft Store licensing.** The app asks the Microsoft Store whether you own Pro or are in the trial. Windows and the Store handle this under Microsoft's privacy statement. A cached result lets the app work offline.

Voice Portal works with the network switched off. Online features are not part of the launch version. If any are added later, they will be opt-in and off by default.

## Children

Voice Portal is a general-purpose tool and is not directed at children under 13. We do not knowingly collect information from anyone, including children, because the app collects none.

## Recording and consent

Meeting capture records audio on your PC only. No one else is notified. You are responsible for following the laws and rules that apply to recording other people, including getting consent.

## Changes to this policy

If this policy changes, we will update the date above and describe the change in the app's release notes. Any change that adds data collection will require your opt-in.

## Contact

Questions about privacy: email [mindthaapp@gmail.com](mailto:mindthaapp@gmail.com)
