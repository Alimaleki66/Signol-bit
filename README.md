services:
  - type: web
    name: signal-bot
    env: python
    buildCommand: pip install -r requirements.txt
    startCommand: python app.py
    envVars:
      - key: TELEGRAM_TOKEN
        value: 7570055560:AAFrkQ5itLJID07Kc...
      - key: TELEGRAM_CHAT_ID
        value: 123456789
