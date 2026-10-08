# 𓆩 𝐆ᴏᴅ 𝐙xʏɴ 𓆪 — Hosting Bot

## Railway deployment

1. Upload/push all files to GitHub.
2. Create a Railway project and deploy the repository.
3. Add these Variables in Railway:
   - `BOT_TOKEN` = your Telegram bot token
   - `BOT_USERNAME` = your bot username (optional)
   - `UPDATE_CHANNEL` = `@codezxyns`
   - `UPDATE_GROUP` = `@codezxyns` (change if you have a separate group)
4. Railway uses `Procfile` / `railway.json` to start `python hosts.py`.

## Included
- `hosts.py` — main bot
- `requirements.txt` — Python dependencies
- `Procfile` — Railway start command
- `railway.json` — Railway deployment config
- `.env.example` — required environment variables
- `.gitignore` — runtime data protection

### Security
Never commit a Telegram bot token to GitHub. If an old token was exposed, revoke it with BotFather and generate a new one before deployment.
