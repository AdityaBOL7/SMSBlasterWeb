# SMS Blaster Web

Marketing site for **SMS Blaster**: bulk SMS and RCS messaging from Android, with privacy policy and account deletion pages.

Static files: `index.html`, `styles.css`, `script.js`.

## GitHub Pages

After pushing to `main`, enable **Settings → Pages → Deploy from branch `main` / root** to publish the site.

## First-time push

1. Create an **empty** repository on GitHub (no README) named `SMSBlasterWeb` under the account that owns your SSH key.
2. From this folder: `git push -u origin main`

If push says **Repository not found**, your SSH key is tied to a different GitHub user than the repo owner. Fix one of these:

- Add this computer’s SSH public key to the **same** GitHub account that owns `AdityaBOL7/SMSBlasterWeb`, or  
- Change the remote to your own fork:  
  `git remote set-url origin git@github.com:YOUR_USERNAME/SMSBlasterWeb.git`

Check which account SSH uses: `ssh -T git@github.com`
