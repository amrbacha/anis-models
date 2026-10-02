# anis-models

ملفات النماذج التي يحمّلها تطبيق **أنيس – طُرَق الهداية** عند الحاجة. الكود ليس هنا.

## whisper-base-ar-quran (q8_0)
- النموذج الأصلي: [tarteel-ai/whisper-base-ar-quran](https://huggingface.co/tarteel-ai/whisper-base-ar-quran) من Tarteel AI، بترخيص Apache 2.0.
- حُوّل إلى صيغة whisper.cpp (ggml) وضُغط إلى q8_0 (نحو 82 MB). الأوزان لم تُعدَّل. أُعيد نشره من [AliShafqat12455/quranlocker-hifz-model](https://huggingface.co/AliShafqat12455/quranlocker-hifz-model).
- الملف: `ggml-whisper-base-ar-quran-q8_0.bin` (81,768,585 بايت)
- SHA-256: `72194195f7d280adebec57acf2c6e01e209484322ec1cec21c275a3c0b1e3d77`

## الترخيص
Apache License 2.0. انظر `LICENSE` و`NOTICE`.
