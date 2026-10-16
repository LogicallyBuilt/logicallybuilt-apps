# Logically Built — GitHub Pages website

A responsive static website for the three Logically Built apps:
- Shift Planner
- College Attendance Tracker
- Day Calculator

The site links to the existing Blogger app pages for current downloads and full details. It does **not** host APKs.

## 1. Create your GitHub account

1. Go to https://github.com and create an account using an email address you control.
2. Choose a username that is professional and close to `logicallybuilt` if available. If it is taken, choose a consistent variation such as `logicallybuilt-apps` or `logicallybuilt-dev`.
3. Verify your email and enable two-factor authentication.
4. Use a profile name such as **Logically Built** and a short bio such as **Building useful Android apps | Shift Planner · College Attendance · Day Calculator**.
5. Add your Blogger homepage as your website link: https://logicallybuilt.blogspot.com/p/logically-built.html

## 2. Publish this site with GitHub Pages

1. Download and extract the ZIP.
2. On GitHub, create a **public** repository named `logicallybuilt-apps` (or another available name).
3. Upload the *contents* of this folder into the repository root. Make sure `index.html`, `assets/`, and `apps/` are at the top level, not inside an extra nested folder.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then save.
7. Wait for the deployment to finish. Your site will usually be at:
   `https://YOUR-GITHUB-USERNAME.github.io/logicallybuilt-apps/`
   Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username.

## 3. Keep the links up to date

The app pages currently point to:
- Shift Planner: https://logicallybuilt.blogspot.com/p/shift-planner-app.html
- College Attendance: https://logicallybuilt.blogspot.com/p/college-attendance-app.html
- Day Calculator: https://logicallybuilt.blogspot.com/p/day-calculator-iq-test-exam-preparation.html

When you update a page, edit the relevant HTML file and commit the change. Keep download links, store availability, versions, and privacy information accurate.

## 4. Suggested profile setup

**Name:** Logically Built  
**Bio:** Turning ideas into useful apps. Building, improving, and shipping practical Android tools.  
**Website:** https://logicallybuilt.blogspot.com/p/logically-built.html

Keep personal secrets, app signing keys, keystores, API keys, passwords, and private user data out of public repositories. A public website repository is appropriate for this static promotional site.

## Notes

- This is a static HTML/CSS/JS site; no build tools are needed.
- The GitHub Pages URL is not live until you publish it in your own GitHub account.
- You can later connect a custom domain, but you do not need to do that to start.
- The Blogger site remains your main source for current app downloads and policy pages.
