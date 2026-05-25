The repo Gnerdy/gstream.github.io

# Copy the 7 website files from the project


Start fresh


1. Go to [](https://github.com/Gnerdy/gstream.github.io)<https://github.com/Gnerdy/gstream.github.io>
2. Click __Settings__ → scroll to bottom → __Delete this repository__ (you'll need to confirm)
3. Create a new repo:

```bash
gh repo create gstream.github.io --public
```


git config user.email "support@gstream.com"
git config user.name "GStream"

git commit -m "GStream landing page v1.0.0"
git push -f origin main


After that, enable GitHub Pages:

1. Go to [](https://github.com/Gnerdy/gstream.github.io)<https://github.com/Gnerdy/gstream.github.io>
2. Click __Settings__ → __Pages__ (left sidebar)
3. Under "Branch", select __main__ → __/ (root)__ → __Save__
4. Wait ~2 minutes, then your site is live at `https://gnerdy.github.io/gstream.github.io/`



__To set up `gstream.app/tv`:__

- Buy the domain `gstream.app` from a registrar (like Namecheap, GoDaddy, etc.)
- Create a CNAME record: `tv` → `gnerdy.github.io`
- Or use a URL redirect: `gstream.app/tv` → `https://gnerdy.github.io`
