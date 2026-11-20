# Tinnitus Companion

A single-file, browser-based prototype for a tinnitus self-management companion designed with adults age 55 and older in mind.

It provides a calm, large-text interface for a daily check-in, low-volume synthetic sound options, short coping lessons, safety prompts, and a printable clinician-summary screen.

## Important safety notice

This is an educational prototype, **not a medical device, diagnosis tool, or treatment**. It does not cure tinnitus and should not replace care from an ENT clinician, audiologist, mental-health professional, or primary-care clinician.

Do not rely on the app alone for sudden hearing loss, rapidly worsening hearing, a new heartbeat-like sound, one-sided tinnitus, new neurologic symptoms, severe dizziness, or a mental-health crisis. Seek appropriate clinical or emergency help.

## Features

- Large-text, high-contrast interface designed for older adults
- Daily tinnitus-impact and sleep check-in
- Safety-screen prompt for urgent symptoms
- Three synthetic audio options:
  - **Soft fan:** airy texture with a gentle motor rhythm
  - **Gentle rain:** soft noise with irregular droplet texture
  - **Warm noise:** deep, hum-free brown-noise texture
- Separate **Play** and **Stop** buttons
- Short coping-plan lessons
- Printable clinician-summary screen
- No frameworks, build tools, accounts, analytics, or network connection required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge, Firefox, or Safari.
3. Select **Calm sounds**, choose a sound, and press **Play**.

The synthetic sounds are generated entirely in the browser. Keep the volume low and stop playback if it is uncomfortable.

## Upload to GitHub

### GitHub website method

1. Sign in to GitHub and choose **New repository**.
2. Name it `tinnitus-companion`.
3. Choose **Public** or **Private**.
4. Do **not** initialize it with a README, because this project already has one.
5. Click **Create repository**.
6. Choose **uploading an existing file**.
7. Upload the contents of this folder:

   - `index.html`
   - `README.md`
   - `.gitignore`

8. Enter a commit message such as `Initial Tinnitus Companion prototype`, then click **Commit changes**.

### Publish it with GitHub Pages (optional)

1. Open the repository on GitHub.
2. Choose **Settings** → **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`.
5. Click **Save**.

After GitHub finishes publishing, it will show the public project URL on the Pages screen.

## Privacy

This prototype stores no user information on a server and sends no data across the network. Do not add real patient health information to a public repository.

## Before public release

Before presenting this as a clinical product, obtain review from qualified clinicians, accessibility specialists, privacy/security professionals, and regulatory experts. Use licensed or original audio assets if you replace the synthetic sounds with recorded sound files.

## License

No license has been selected yet. Before making the repository public for reuse by others, choose a suitable open-source or proprietary license.
