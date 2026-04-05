# Psychologist-Assistant-Workflow (n8n)

This workflow provides a Telegram-based mental health assistant that delivers practical and structured advice using AI.

Users send their problems through Telegram. The system processes the message using an AI model and returns clear, step-by-step solutions in Persian. The responses are designed to be simple, direct, and actionable, without emotional or unnecessary language.

If the user sends the start command, the bot provides instructions on how to use the service. Otherwise, every message is treated as a request for guidance and is answered accordingly.

The assistant also follows basic safety rules and provides practical steps if serious mental health risks are detected.

Requirements include n8n, Telegram Bot API, and Google Gemini API.
