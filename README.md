# SJ Shop

## Bot token + /start

1. Put token in `bot_config.json` → `"token": "123:ABC"` **or** env `BOT_TOKEN`
2. Put live HTTPS URL in `bot_config.json` → `"shop_url"` **or** env `SHOP_URL`
3. Run web: `uvicorn app:app --host 0.0.0.0 --port $PORT`
4. Run bot: `python bot.py`
5. Telegram → your bot → `/start` → **Open SJ Shop**

Admin TG id: `5427735251` — use `/grant <id>` for users.

No proxy required. See `BOT_SETUP.txt`.
