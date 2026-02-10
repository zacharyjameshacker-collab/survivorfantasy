# Survivor 50 Fantasy Game 🔥

A zero-backend fantasy game for Survivor Season 50. One person (you) scores episodes; everyone sees the live standings.

## Setup (5 minutes)

1. **Create a GitHub repo** — go to github.com → New Repository → name it `survivor-fantasy` (or whatever) → **Public** → Create
2. **Upload both files** — click "Add file" → "Upload files" → drag in `index.html` and `data.json` → Commit
3. **Enable GitHub Pages** — go to Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `root` → Save
4. **Wait ~60 seconds**, then visit: `https://YOUR-USERNAME.github.io/survivor-fantasy/`
5. **Share that link** with your friends!

## How It Works

| You (admin) | Your friends |
|---|---|
| Visit the link with `?admin=1` at the end | Visit the normal link |
| See all tabs including Score Ep, Winner, Settings | See Scores, Drafts, History, Rules |
| Score episodes → downloads updated `data.json` | Refresh page to see latest scores |

### Weekly Flow

1. **Before the episode**: Collect everyone's vote predictions (text/group chat)
2. **After the episode**: Go to your site with `?admin=1`
3. **Score the episode** using the 5-step wizard (challenges → events → voted out → vote points → review)
4. **Click Submit** → a new `data.json` downloads automatically
5. **Upload it to GitHub**: go to your repo → click `data.json` → pencil icon (edit) → paste the new contents (or delete & re-upload) → Commit
6. Your friends refresh the page and see updated scores!

### Updating Winner Picks

If anyone wants to change their Sole Survivor pick between episodes, do it from the Winner tab in admin mode, then upload the new `data.json`.

## Tips

- Bookmark `yoursite.github.io/survivor-fantasy/?admin=1` on your phone
- The admin URL is not secret — it's just a convenience toggle. Your friends could technically use it too.
- GitHub Pages updates take 30-60 seconds after committing
- All game state lives in `data.json` — you can always edit it manually if needed
