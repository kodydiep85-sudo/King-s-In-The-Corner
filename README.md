# Kings Corner

The classic Kings in the Corner card game. Play with friends on their own phones and computers using a 4-letter game code, or play against the computer.

Everything is in `index.html`. No build step and no packages to install.

## Put it on GitHub Pages

1. Create a new **public** repository on GitHub.
2. Click **Add file → Upload files** and drag in **all the files in this folder**, not the folder itself. `index.html` must be at the top level of the repository.
   - Hidden files like `.nojekyll` may not show up when you drag; that's fine.
3. Click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
5. Wait 1–2 minutes and refresh. The site link appears at the top of that page, like `https://yourname.github.io/kings-corner/`.

## Put it on Render

First push these files to a GitHub repository (steps 1–3 above). Then use **one** of these:

**Option A: Static Site (recommended, free)**
1. In Render, click **New → Static Site** and pick your repository.
2. **Build Command:** leave empty (or `echo done`).
3. **Publish Directory:** `.`
4. Click **Create Static Site**.

**Option B: Web Service**
1. In Render, click **New → Web Service** and pick your repository.
2. **Runtime:** Node
3. **Build Command:** `npm install`
4. **Start Command:** `npm start`
5. Click **Create Web Service**.

## Playing with friends

1. Everyone opens the site link.
2. One person types their name and taps **Host a game** to get a code.
3. Friends type their name and the code, then tap **Join**.
4. The host taps **Start game** (2–4 players) and keeps the page open until the game ends.

If a friend drops out, the game plays for them until they rejoin with the same code on the same device. On some strict school or work networks, devices can't connect directly; switching to mobile data fixes it.
