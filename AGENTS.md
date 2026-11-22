# Project instructions

- Preserve the current screenshot OCR behavior and settings. Tesseract OCR calls are serialized, and the per-pass timeout defaults to 60 seconds. Do not change these settings or their implementation unless the user explicitly asks.
- Keep credentials and machine-specific values in local environment configuration; never add `.env` or secret values to Git.
