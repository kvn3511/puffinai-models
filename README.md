# Puffin AI

Puffin AI is a private AI that runs on your Android phone. It uses small language models that run directly on your device, so there is no account, no cloud, and your content never leaves your phone.

## Download

**[Download Puffin AI 1.0.0 (app-release.apk, 105 MB)](https://github.com/kvn3511/puffinai-models/releases/download/app-v1.0.0/puffinai-v1.0.0.apk)**

You can also find it on the [app-v1.0.0 release page](https://github.com/kvn3511/puffinai-models/releases/tag/app-v1.0.0), listed under Assets.

**Requirements:** Android 8.0 or newer. Use Wi-Fi for the first launch, because the app downloads an AI model that can be over 1 GB.

## Install

Puffin AI isn't on the Play Store yet, so Android asks for permission before installing it. This is normal for apps downloaded outside the store.

1. Open the download link above on your Android phone and let the file finish downloading.
2. Open the file. If Android blocks the install, tap **Settings** in the prompt and turn on **Allow from this source** for your browser.
3. Go back and tap **Install**.
4. Open Puffin AI and follow the setup. It checks your phone and downloads the right model.

You can turn off "Allow from this source" again after the app is installed.

## What it does

Puffin picks a model that fits your phone.

**On most phones (lightweight model)**
- Sorts your notifications by urgency, in the background
- Identifies the language of any text you share to it

**On more powerful phones (advanced model)**
- Everything above, plus:
- Chatbot
- Drafting emails
- Creating calendar events
- Turning voice notes into bullet points
- Rewriting, shortening, summarizing, and fixing grammar in any text

To use Puffin on text in any app, highlight the text, tap **Share**, and choose **Puffin AI**.

## How it works

Puffin runs small language models (SLMs) on your phone's own processor. After setup, it works without an internet connection, including in airplane mode. During setup, the app checks what your phone can handle and downloads the matching model.

Small models make mistakes, especially with facts, names, and dates. Check anything important before relying on it. Calendar events and email drafts always open in your own calendar or email app for you to review, and nothing is saved or sent without your action.

## The model files in this repository

This repository also hosts the model files the app downloads during setup, under the [v1.0.0 release](https://github.com/kvn3511/puffinai-models/releases/tag/v1.0.0). **You don't need to download them yourself.** The app fetches the ones it needs.

## Privacy

- Your messages, notes, recordings, and AI responses never leave your device. There are no accounts and no servers that store your content.
- Puffin collects anonymous usage data, such as how long sessions last and which screens are used, to improve the app. You can turn this off at any time in **Settings > Privacy**.

## Troubleshooting

- **"App not installed" or the install is blocked:** make sure "Allow from this source" is turned on for the browser or file manager you used to open the file.
- **The first launch is slow or stuck on downloading:** the model is large. Stay on Wi-Fi and keep the app open until it finishes.
- **The app doesn't see my notifications:** open **Settings** in Puffin and turn on notification access.
- **Voice notes don't record:** open **Settings** in Puffin and check that microphone access is on.

## Known limitations

- Android only.
- Phones with limited memory use the lightweight model and don't get chat or the Agent features.
- Updates are manual for now. To update, download the newest release and install it over the existing app.
