# Charles Ahuose Misheal — Portfolio Website

This folder is a simple website (plain HTML and CSS, no build step). When it is published, it will be available at:

**https://charlesmisheal.github.io**

You do not need to use the command line or Git. Follow the steps below on the GitHub website.

## Before you start

1. Unzip `charlesmisheal.github.io.zip` on your computer.
2. Open the unzipped folder and confirm you can see `index.html`, `style.css`, `projects.html`, `principles.html`, `reflections.html`, `growth.html`, and this `README.md` in the same place (not buried inside another folder).
3. Sign in to [GitHub](https://github.com) with the account **CharlesMisheal**.

## 1. Create the repository

The site only works if the repository name is exactly `charlesmisheal.github.io` (all lowercase).

1. In the upper-right corner of any GitHub page, select the **+** menu, then click **New repository**.
2. Use the **Owner** dropdown to select your **CharlesMisheal** account.
3. For **Repository name**, type exactly: `charlesmisheal.github.io`
4. Choose **Public** visibility. (On GitHub Free, a user site must be public.)
5. Leave **Add a README** turned **off**, and do not add a `.gitignore` or license. You will upload the files in this folder, including this README.
6. Click **Create repository**.

## 2. Upload the website files

1. On the main page of the new repository, above the file list, select the **Add file** dropdown menu and click **Upload files**. (You can also drag and drop files into the browser.)
2. Drag and drop the unzipped files, or click **choose your files** and select them. Upload the files themselves so that `index.html` is at the **root** of the repository, not inside a subfolder. If you accidentally upload a folder (for example `portfolio-site` or `charlesmisheal.github.io`), GitHub Pages will not find `index.html` and the site will show “page not found.”
3. In the **Commit message** field, type a short message such as `Add portfolio site`.
4. Leave the option to commit directly to the **main** branch selected. Do not create a new branch.
5. Click **Commit changes**. (Depending on the page, the button may also say **Propose changes**. Choose the option that commits to **main**.)

## 3. Turn on GitHub Pages

1. Under your repository name, click **Settings**. If you cannot see the Settings tab, open the extra menu next to the tabs, then click **Settings**.
2. In the **Code, planning, and automation** section of the sidebar, click **Pages**.
3. Under **Build and deployment**, under **Source**, select **Deploy from a branch**.
4. Use the branch dropdown to select **main**, and use the folder dropdown to select **/ (root)**.
5. Click **Save**.

## 4. View the site

GitHub can take up to 10 minutes to publish the site after you save these settings or upload changes.

1. Stay on the **Pages** settings screen, or return to **Settings → Pages**.
2. Under **GitHub Pages**, click **Visit site**.
3. The address should be **https://charlesmisheal.github.io**.

If the site does not appear after about 10 minutes, refresh the page, confirm that `index.html` is at the root of the `main` branch, and confirm that Pages is set to deploy from **main** and **/ (root)**.

## Pages in this site

| File | Page |
| --- | --- |
| `index.html` | Home / About |
| `projects.html` | Projects |
| `principles.html` | Guiding Principles (IT 497 Week 3) |
| `reflections.html` | Faith and Technology Reflections |
| `growth.html` | Mentorship and Growth |
| `style.css` | Shared styles (navy and white) |

## Optional later updates

- On the Home page, the LinkedIn and Résumé links are placeholders (`#`). In `index.html`, replace those `href="#"` values and remove the nearby `TODO` comments when you have the real URLs.
- To change the site later, open the repository, choose **Add file → Upload files** again, and upload only the files you edited (this will replace the old versions). Commit to **main**.

These steps follow GitHub’s current documentation for [creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site), [adding a file to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository), and [configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
