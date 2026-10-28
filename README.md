# Practice Research Group website

A fictional four-page website for learning GitHub. It uses plain HTML and CSS: no packages, build step, accounts, or API keys are needed to run it.

## Files you can edit

| File | What it controls |
| --- | --- |
| `index.html` | Home page and news |
| `people.html` | Group members |
| `research.html` | Research topics |
| `publications.html` | Publication entries |
| `style.css` | Colours, spacing, and layout |
| `SKILL.md` | Your growing requirements for an AI assistant |

Look for `EDIT` comments in the files. Keep the HTML tags (such as `<p>` and `</p>`) and change the text between them.

## First exercise: edit on your computer

1. Download this repository using GitHub’s **Code → Download ZIP**, then unzip it. Alternatively, clone it using GitHub Desktop; cloning makes it easier to send changes back to GitHub.
2. Open `index.html` in your browser.
3. Open the same file in a text editor, such as VS Code. Change “Our first website!” to your own news headline and save.
4. Refresh the browser to see your change.
5. Try changing a name in `people.html`. Then change `--accent` in `style.css` from `#245b57` to `#704080`.

Double-clicking the HTML files works. If you have Python installed, you can instead run `python3 -m http.server 8000 --bind 127.0.0.1` from this folder and view it locally. Stop the server with Ctrl+C.

## Save changes with GitHub Desktop

1. Sign in to GitHub Desktop and choose **File → Clone Repository**, selecting this repository.
2. Use **Open in external editor**, make an edit, and save the file.
3. Return to GitHub Desktop and inspect the highlighted changes.
4. Write a short summary such as “Update practice news” and click **Commit**. A commit is a saved checkpoint on your computer.
5. Click **Push origin** to send your commits to GitHub. Use **Fetch origin / Pull origin** before starting future edits to get others’ changes.

If you used a ZIP, those files are a separate copy; edits do not automatically go back to GitHub. Clone with Desktop and copy your edited files into that checkout to upload them.

## Try an edit directly on GitHub

Once these files are pushed to GitHub, open `people.html`, choose the pencil icon, change a fictional name, and commit the change. Pull that change in GitHub Desktop before editing locally again.

## Publish the practice site with GitHub Pages

After these files are pushed, open the repository’s **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose the branch containing these files and **/ (root)**, then save. GitHub will show the website address when deployment completes. Availability depends on the repository visibility and your GitHub plan.

Pushing files and publishing the website are separate steps. This mockup does not require Jekyll. Relative links let it work under a GitHub Pages repository URL.

## Collaborators

Invite each person’s GitHub account under repository **Settings → Collaborators**. For shared editing, use a separate branch and a pull request (a proposed change others can review) before merging. A GitHub organization can provide longer-term group ownership later.

## Your requirements file

Edit `SKILL.md` over time and keep a copy on your computer. Tell your AI assistant to read it when working on the site. Automatic skill discovery depends on your application; merely having this file does not activate it in every AI tool. Do not put passwords or private personal data in it.
