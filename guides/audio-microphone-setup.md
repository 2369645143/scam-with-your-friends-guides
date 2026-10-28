---
title: "Speech Settings: Microphone & Backend 0.1.95"
description: "Check Scam With Your Friends 0.1.95 speech recognition, language-specific voices and Official Backend, then troubleshoot input and silent replies."
category: "Audio & Input"
badge: "SOURCE CHECK · 0.1.95"
readingTime: "3 min read"
publishDate: "2026-10-10"
updatedDate: "2026-10-28"
icon: "headset"
lang: "en"
---

## Check your version and the failing stage
This guide follows the official **0.1.95** notes; no game build was playtested. Record your installed version and distinguish microphone input, recognition, text dialogue, spoken output and backend connection. A failure in one stage does not prove that every stage failed.

## Settings > Speech: recognition and voices
- Recognition offers Whisper Small, Whisper Base and Moonshine; Whisper Small is the default. Check language availability and loading messages.
- Enable, disable and reorder supported Pocket TTS, MOSS TTS Nano and Qwen3 TTS voices per language. Preferences are saved separately for each language on your computer.
- Disabling every voice model keeps replies as text. Check this before treating silent replies as a broken installation.

## Do older OpenRouter or Gladia instructions still apply?
Version 0.1.95 removes these optional integrations from standard builds. Existing OpenRouter selections revert to **Official Backend**, now an option for hosts. Do not follow an older guide that requires their API keys. Earlier store text and the 0.1.92 announcement do not describe the current settings.

## Troubleshoot by symptom — editorial checklist
1. **No microphone input:** check system permission, selected device and current game binding. Try one short input in a quiet room.
2. **Input recognized incorrectly:** check language, model and loading status. Compare the same short phrase while changing one setting at a time.
3. **Text reply but no voice:** inspect output device, volume and enabled models for the current language.
4. **Waiting or service error:** record the exact message and build. Check the host's backend and network, and note whether everyone is affected.

Follow the current interface for push-to-talk and text input. No fixed latency, shift length, proximity-audio behavior or guaranteed best setting is claimed here.

## Microphone meter moves, but the phone does not recognize speech
1. Compare typed input in the same call. If typing also fails to produce a reply, record the call/backend state before focusing only on microphone settings.
2. If text works but speech fails, check the recognition language, selected model and loading message. Retry one short phrase, changing one setting at a time.
3. If recognized text is correct but replies are silent, check whether all voices for that language are disabled, then inspect output device and volume.
4. A friend hearing you does not establish phone recognition: multiplayer chat, speech recognition and reply playback are different stages.

For a report, open the General session log, search around the reproduction time and include the build and model names. Review conversation content before posting logs. [Community comments from October 15–16](https://steamcommunity.com/app/4954910/eventcomments/706660083369654372/) describe similar symptoms; they do not establish the same bug in 0.1.95. This comparison is diagnostic advice, not a guaranteed fix.

## Reporting the problem
The update adds a searchable session log under General settings. Record reproduction steps, version, language, recognition model and error. Review logs for private information before sharing them; credentials are not needed for this guide.

[Online play and platforms](/guides/online-play-platforms/) · [Requirements and network](/guides/system-requirements/)

## Source
[Official updates: 0.1.95](https://steamcommunity.com/app/4954910/allnews/), checked October 28, 2026. The old community-tested label and precise latency claims lacked reproducible evidence and have been removed.
