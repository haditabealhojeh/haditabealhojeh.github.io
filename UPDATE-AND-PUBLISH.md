# Update and publish the website

This archive contains the personalized website source, not the old `.git` history or installed `node_modules`. That is intentional: the GitHub repository was empty, and the previous local history repeatedly failed during GitHub's unpack step.

## Recommended fresh push (preserves your old folder as a backup)

1. Extract this archive somewhere convenient.
2. Keep your current website folder as a backup; do not delete it.
3. In the extracted `haditabealhojeh.github.io` folder, open a terminal and run:

```bash
git init -b main
git add .
git commit -m "Create personalized academic website"
git remote add origin https://github.com/haditabealhojeh/haditabealhojeh.github.io.git
git push -u origin main
```

Because the remote repository is empty, a fresh local history is appropriate. This does not require `--force`.

If Git asks for a password, use a GitHub personal access token instead of your account password. Never share token-bearing HTTP debug logs.

## Local preview

Install Ruby/Bundler and Node.js/npm if they are not already installed. Then run:

```bash
bundle install
npm install
bundle exec jekyll serve
```

Open http://localhost:4000.

## Personal details still intentionally omitted

- A personal email address: none was provided, so no placeholder or invented address is published.
- A personal headshot: the site currently uses an HT monogram avatar in `assets/img/profile.svg`. Replace it with a professional headshot when ready.
- Unverified awards, citation counts, and unpublished manuscript status: not added.
