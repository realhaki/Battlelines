# Battlelines — A History Quiz

A small, responsive browser quiz about the people, places, and ideas that shaped history. It is built with plain HTML, CSS, and JavaScript, so it runs directly in a browser and can be hosted on GitHub Pages.

## Run locally

Open `index.html` in a browser. No install or build step is required.

## Publish with GitHub Pages

1. Create a GitHub repository named `history-quiz` (or choose another name).
2. Add these project files and push them to the repository's `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub Pages will publish the app at `https://<your-username>.github.io/<repository-name>/`.

## Customize

Add or edit quiz entries in the `questions` array in `app.js`. Each entry has a category (`people`, `places`, or `ideas`), an era, four answers, the correct answer index, and a short historical note. Add a `source` URL to show a source link with the answer explanation.

The quiz has 165 questions, including source-linked questions on the Napoleonic Wars, World War I, World War II, and 39 additional conflicts. Use the **All topics** menu to choose a specific conflict. The supplied Latin American wars link is a disambiguation page, so its three questions cover the Haitian Revolution, Spanish American wars of independence, and Brazilian War of Independence listed there. The Congo and Afghanistan links are set-index pages, so their questions cover the First and Second Congo Wars and the 2001–2021 Afghanistan War, respectively.
