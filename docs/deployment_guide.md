# How to Publish Your Snake Game

Since your game is a single HTML file (`snake_game.html`), publishing it is very easy! Here are the best free options:

## Option 1: GitHub Pages (Recommended)
If you have a GitHub account, this is the standard way to host.

1.  **Create a Repository**:
    *   Go to GitHub and create a new public repository (e.g., `neon-snake`).
2.  **Upload File**:
    *   Rename your file from `snake_game.html` to `index.html` (this is important so it loads automatically).
    *   Upload `index.html` to the repository.
3.  **Enable Pages**:
    *   Go to **Settings** > **Pages**.
    *   Under "Source", select `main` branch.
    *   Click **Save**.
4.  **Play**:
    *   Your game will be live at `https://<your-username>.github.io/neon-snake/`.

## Option 2: Netlify Drop (Easiest)
No account required initially.

1.  **Prepare Folder**:
    *   Create a folder named `site`.
    *   Move `snake_game.html` into it and rename it to `index.html`.
2.  **Upload**:
    *   Go to [app.netlify.com/drop](https://app.netlify.com/drop).
    *   Drag and drop the `site` folder onto the page.
3.  **Play**:
    *   Netlify will give you a random URL (e.g., `fluffy-unicorn-123456.netlify.app`) where your game is live immediately.

## Option 3: Vercel
Great if you want a custom domain later.

1.  **Install CLI** (if you have Node.js):
    *   Run `npm i -g vercel`.
    *   Run `vercel deploy` in the folder containing your game.
2.  **Or via Web**:
    *   Go to Vercel.com, import your GitHub repository, and it will auto-deploy.

## Pre-Deployment Checklist
- [ ] **Rename file**: Change `snake_game.html` to `index.html` for easier hosting.
- [ ] **Title**: Ensure `<title>` tag is what you want users to see in the tab.
- [ ] **Favicon**: Consider adding a favicon link if you want a custom icon.
