# Resonance

Resonance is an original, free, installable music-practice web app. It includes a microphone tuner with needle, smiley, and harmonic-overtone displays, metronome with tap tempo and saved presets, a playable reference keyboard with sustained drone, and local practice recordings. It defaults to trumpet in B♭. Settings and recordings stay in this browser on this device.

## Run it

Microphone access on iPhone requires a secure HTTPS website. To install it for free with GitHub Pages:

1. Create a **public** GitHub repository and upload the contents of this folder to its root.
2. In the repository, open **Settings → Pages** and set publishing to the `main` branch and `/(root)` folder.
3. When GitHub shows the site URL, open it in Safari on the iPhone and choose **Share → Add to Home Screen**.

GitHub Pages is available for public repositories on GitHub Free, so the app itself does not need a paid service. For local development, run any static web server in this folder; microphone APIs generally work on `localhost`.

The app shell works offline after the first visit. Microphone tuner and recording need permission and a secure origin. It does not use a server, account, paid API, or third-party tracking.

## Included

- Chromatic tuner from C0 to C8 with adjustable A4 reference, instrument transposition, note-name mode, cents display, waveform and spectrum views, harmonic levels for the fundamental and first seven overtones, a trumpet B♭ reference, and open-string targets for guitar, bass, violin, viola, cello, and ukulele.
- Tempo control from 30–300 BPM, tap tempo, 2–12 beat meter, subdivisions, and local presets.
- Reference tone keyboard with sine, triangle, square, and sawtooth tones, plus a sustained drone.
- Microphone recording, local playback, download, and delete.
- Responsive iPhone layout, Home Screen install metadata, and offline app-shell cache.

This is an independent project and is not affiliated with or a reproduction of TonalEnergy. Web browsers do not provide all native app integrations (for example Apple Watch remote, MIDI/Audiobus routing, external video output, or full audio editing/time-stretch).
