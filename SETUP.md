# Publishing this on GitHub Pages

You need: a free GitHub account. No terminal, no build tools, no command line.

## 1. Create the repository
1. Go to github.com → **+** (top right) → **New repository**
2. Name it `receptek`
3. Set it **Public** (Pages is free on public repos; private needs a paid plan)
4. Tick **Add a README file** → **Create repository**

## 2. Upload the files
1. In the repo, click **Add file** → **Upload files**
2. Drag in `index.html` (and `README.md` if you want it)
3. Under "Commit changes", write something like `first version`
4. Click **Commit changes**

## 3. Turn on Pages
1. Repo → **Settings** → **Pages** (left sidebar)
2. Under "Build and deployment", Source = **Deploy from a branch**
3. Branch = **main**, folder = **/ (root)** → **Save**
4. Wait ~1 minute. The URL appears at the top of that page:
   `https://<your-username>.github.io/receptek/`

That URL works on your phone. Add it to your home screen and it behaves
like an app (Safari: Share → Add to Home Screen; Chrome: ⋮ → Add to Home screen).

## 4. Updating it later
- **Small text fix:** open `index.html` in the repo, click the pencil ✏️,
  edit, commit. Pages redeploys in about a minute.
- **New version from a chat:** Add file → Upload files → drop the new
  `index.html` → it overwrites the old one. Every commit is a restore point,
  so you can always roll back under the repo's **History**.

## 5. Your edits vs. the published file
Two separate things:
- **The file** (recipes, matrix data) — lives in the repo, changes via commits.
- **Your edits** (tags you fixed, recipe text you typed, menus, ✦ ticks) —
  live in your browser's localStorage, per device.

So: editing on your phone does **not** change what your laptop sees.
To move edits between devices, use **export backup** on the Menü tab, then
**import backup** on the other device.

To make an edit permanent for everyone/every device, export the backup and
commit `izmatrix-state.json` to the repo — then it's version-controlled too.
