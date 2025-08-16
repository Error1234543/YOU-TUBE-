# SH File Parser Bot

This is a Telegram Bot that extracts video (m3u8) and PDF links from uploaded `.sh` files and returns them as `output.txt`.

## Deployment on Render
1. Create a new Web Service in Render.
2. Upload this repo as ZIP.
3. Add an environment variable in Render:
   - KEY = BOT_TOKEN
   - VALUE = Your BotFather token
4. Deploy 🚀