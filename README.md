# Gobby

Gobby is private, local voice dictation for Mac and Windows. Hold a hotkey,
speak naturally, and Gobby types the cleaned transcript into the app you are
using.

## Download

### Mac

**[Download the latest Gobby for Mac](https://github.com/ladiesman217am/gobby-downloads/releases/latest/download/Gobby-Mac-latest.zip)**

Version 1.4.0 · macOS 13.3 or newer · Apple Silicon and Intel

### Windows

**[Download the latest Gobby for Windows](https://github.com/ladiesman217am/gobby-downloads/releases/latest/download/Gobby-Windows-x64-latest.zip)**

Version 1.1.0 · 64-bit Windows 10 22H2 or Windows 11

The [latest release page](https://github.com/ladiesman217am/gobby-downloads/releases/latest)
contains versioned packages, release notes, and SHA-256 checksums.

## Install on Mac

1. Download and extract `Gobby-Mac-latest.zip`.
2. Right-click **Gobby Setup.app** and choose **Open**.
3. Confirm **Open** if macOS warns that the file came from the internet.
4. Enter your name, choose a talk key, and click **Set up Gobby**.
5. Leave the setup window open while the private speech model downloads.
6. Allow Microphone and Accessibility when macOS requests them.

The entire installation happens in one graphical window. It does not require
Terminal, Homebrew, Xcode, or an administrator password. The first installation
requires internet and approximately 2 GB of free disk space.

This private staff build is not notarised through the Apple Developer Program,
so right-clicking the installer and choosing Open is required.

### Mac controls

- Hold the talk key selected during setup, speak, then release to transcribe and type.
- Double-tap that key for hands-free dictation; tap it once to finish.
- Use the Gobby menu-bar icon to open the dashboard and Preferences.

## Install on Windows

1. Download and extract `Gobby-Windows-x64-latest.zip`.
2. Double-click **Gobby Setup.vbs** (usually displayed as **Gobby Setup**).
3. Enter your name, choose a talk key, and click **Set up Gobby**.
4. Leave the graphical setup window open until it says you are ready.

Windows may show a SmartScreen warning because this private staff build is not
yet code-signed. Choose **More info**, then **Run anyway**, only when the file
came from this official download page.

The first installation requires an internet connection and approximately
8–12 GB of free disk space.

### Windows controls

- Hold the talk key selected during setup; release it to transcribe and type.
- Double-tap that key for hands-free dictation; press it again to finish.
- Use the Gobby icon near the Windows clock to open the dictionary or settings.

## Privacy

- Speech recognition and transcript cleanup run locally on the user's computer.
- Gobby does not require an OpenAI API key.
- Recordings and transcripts are not sent to the OpenAI API.
- Temporary recordings are deleted after transcription.
- Every new installation starts with an empty private dictionary.
- Release packages contain no owner dictionary, transcript history, recordings,
  model data, account credentials, source code, or API keys.

## Updates

The two download buttons always point to the newest published release. Gobby
does not currently update silently; install the latest ZIP when your
organisation announces a new version. Installing over an older version
preserves that user's dictionary and settings.

## Support

Use the repository's **Issues** page to report a problem. Include the platform,
Gobby version, and operating-system version, but never paste private
transcripts, recordings, dictionary entries, or personal information.

Gobby's Mac and Windows source code is maintained in separate private
repositories. This public repository contains download information and compiled
release files only.
