# SMS Blaster Web

Marketing site for **SMS Blaster**: bulk SMS and RCS messaging from Android, with privacy policy and account deletion pages.

Static files: `index.html`, `styles.css`, `script.js`.

---

## Path A: Repo under **AdityaBOL7** (this project’s remote)

Do these in order in the browser, then push from your PC.

### 1. Create the empty repo

1. Sign in to GitHub as **AdityaBOL7**.
2. **New repository** → name: **`SMSBlasterWeb`** (exact spelling).
3. **Public** or **Private** (your choice).
4. **Do not** add a README, .gitignore, or license (keep it empty).
5. Click **Create repository**.

### 2. Fix SSH access (this machine currently authenticates as **uniaakash**)

GitHub will only accept your push if the SSH key on this PC is allowed to write to **AdityaBOL7/SMSBlasterWeb**. Pick **one**:

**Option A – Collaborator (fastest if uniaakash should keep pushing)**  
- As **AdityaBOL7**: repo **Settings → Collaborators** → add **`uniaakash`** with **Write** access → accept the invite on **uniaakash**.

**Option B – Same account as the repo**  
- As **AdityaBOL7**: **Settings → SSH and GPG keys** → add this PC’s **public** SSH key.  
- If that key is already on **uniaakash**, remove it there first (one key → one account).

**Option C – HTTPS instead of SSH**  
- As **AdityaBOL7**: create a **Personal Access Token** (repo scope).  
- In this folder run:

  `git remote set-url origin https://github.com/AdityaBOL7/SMSBlasterWeb.git`  
  `git push -u origin main`  

  Use **AdityaBOL7** as username and the **token** as the password when prompted.

### 3. Push from this folder

```powershell
cd C:\Users\BOL7_HP\Desktop\SMSBlasterWebsite
git push -u origin main
```

Check SSH identity: `ssh -T git@github.com` (should match an account that can push to the repo).

---

## GitHub Pages

After a successful push: repo **Settings → Pages** → **Deploy from branch** → **`main`** → **`/ (root)`**.
