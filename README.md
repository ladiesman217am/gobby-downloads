# Gobby for Windows

Gobby is private, local voice dictation for Windows. Hold a hotkey, speak
naturally, and Gobby types the cleaned transcript into the app you are using.

## Download

**[Download the latest Gobby for Windows](https://github.com/ladiesman217am/gobby-downloads/releases/latest/download/Gobby-Windows-x64-latest.zip)**

You can also view the version number, release notes, and checksum on the
[latest release page](https://github.com/ladiesman217am/gobby-downloads/releases/latest).

## Install

1. Download the ZIP using the link above.
2. Extract the ZIP.
3. Double-click **Install Gobby.cmd**.
4. Follow the prompts.
5. Restart Windows when requested.

Windows may show a SmartScreen warning because this private staff build is not
yet code-signed. Choose **More info**, then **Run anyway**, only when the file
came from this official download page.

Requirements: 64-bit Windows 10 22H2 or Windows 11, an internet connection for
the first installation, and approximately 8–12 GB of free disk space.

## Controls

- Hold `F8` to record; release it to transcribe and type.
- Double-tap `F8` to start hands-free dictation.
- Press `F8` again to finish hands-free dictation.
- Use the Gobby icon near the Windows clock to open the dictionary or settings.

## Privacy

- Speech recognition and transcript cleanup run locally on the Windows PC.
- Gobby does not require an OpenAI API key.
- Recordings and transcripts are not sent to the OpenAI API.
- Temporary recordings are deleted after transcription.
- Each installation starts with an empty private dictionary.
- The release contains no owner dictionary, transcript history, recordings,
  account credentials, or API keys.

## Updates

This page always points to the newest published Gobby release. The current
application does not update silently; install the latest ZIP when your
organisation announces a new version. Installing over an older version
preserves that Windows user's dictionary and settings.

## Support

Use the repository's **Issues** page to report a problem. Include the Gobby
version and Windows version, but never paste private transcripts, recordings,
dictionary entries, or personal information into an issue.

The Gobby source code is maintained separately in a private repository. This
public repository contains download information and compiled release files only.
