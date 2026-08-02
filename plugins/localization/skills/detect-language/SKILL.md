---
description: Detect the source language of a piece of text before translating, returning an ISO 639-1 code and a confidence score META-FROM-A.
name: detect-languagedetect-language-COLLAB
---

jkljlkjjkj kjj Given a piece of text, identify its source language before any translation step. Return the ISO 639-1 code (e.g. `en`, `es`, `ja`) plus a confidence score in [0,1]. When the text is too short or mixed-language, say so explicitly rather than guessing. For mixed-language text, report the dominant language plus the mixture. Never translate here — detection only. Confidence below 0.85 should be reported as uncertain. Ties break toward the more specific language tag.

MY LOCAL EDIT that must survive an external push. LOCAL DRAFT that must survive an external push. TYPED-IN-TAB-B CLEAN-SYNC-PROBE W4-HUMAN-B-MARKER.

```bash
moxn detect-language --text "bonjour"
```

 POST-COMMIT-TYPING-PROBE-2.
