# Slow Build

A guided beginner workout app. Three full-body sessions a week, jog/walk intervals,
and weights and cardio that step up each week based on how you did.

Everything is saved on your own phone. No account, no cost.

## Put it on your phone (free website, installable)

1. In this repo, open **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Open the **Actions** tab. Wait for **Publish website** to show a green check
   (if it did not start, open it and press **Run workflow**).
4. Your link is `https://YOUR-USERNAME.github.io/REPO-NAME/`.
5. Open that link in Chrome on your phone, open the menu, tap **Install app**
   (or **Add to Home screen**).

## Get a real Android app (APK), also free

1. Open the **Actions** tab → **Build Android app** → **Run workflow**.
2. Wait about 5 to 10 minutes for the green check.
3. Open the **Releases** page of this repo and download **SlowBuild.apk** on your phone.
4. Tap the file. Android will ask to allow installs from your browser. Allow it, then install.

If the build shows a red X, open the run, copy the red error text, and send it to Claude.

## Updating the app

Edit `web/index.html` (or ask Claude to), commit, and the website updates by itself.
Run **Build Android app** again for a new APK.

## Backups

Your progress lives in the phone's storage. In the app, **My gym → Save backup** makes a file
you can restore later. Do this every few weeks.
