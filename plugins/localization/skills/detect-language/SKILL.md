---
description: Detect the source language of a piece of text before translating, returning an ISO 639-1 code and a confidence score
name: detect-language
---

Given a piece of text, identify its source language before any translation step. Return the ISO 639-1 code (e.g. `en`, `es`, `ja`) plus a confidence score in [0,1]. When the text is too short or mixed-language, say so explicitly rather than guessing. For mixed-language text, report the dominant language plus the mixture. Never translate here — detection only.
