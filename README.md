# Playground Sounds AI

Experimental mobile-first playground sound effects web app.

## Deploy

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then Save.
4. Visit https://acidian.github.io/playground-sounds/ after GitHub Pages finishes publishing.

## Test

Open the site over HTTPS on your phone, tap **Start camera**, and point it at a colourful play dashboard. Yellow circles show likely controls and green dots show tracked fingertips. Touch the sound buttons to verify audio. Keep the phone steady.

## Limitations

This MVP uses colour heuristics to find candidate controls and MediaPipe Hands to estimate fingertip proximity. It does **not** semantically recognise buttons or reliably detect physical contact. Sounds are assigned by candidate detection order. It uses a CDN to load MediaPipe and processes camera images locally in the browser. Avoid recording or sharing images of children without appropriate consent.
