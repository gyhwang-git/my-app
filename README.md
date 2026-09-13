# my-app

A minimal static website prepared for deployment with Cloudflare Pages.

## What it displays

- Title: `Hello World!`
- Text: `I'm Jae Seung Lee`

## Project structure

```text
my-app/
├── dist/
│   └── index.html     # The complete website page and its styles
├── .openai/
│   └── hosting.json   # Cloudflare Pages-compatible static output setting
└── README.md
```

## Edit the page

1. Open `dist/index.html`.
2. Change the text inside `<h1>` or `<p>` to update the visible message.
3. Adjust the CSS in the `<style>` section to change colors, spacing, or typography.
4. Open `dist/index.html` in a browser to review the change locally.

The file includes comments explaining each main section to make later updates straightforward.

## Deploy with Cloudflare Pages

1. In Cloudflare, open **Compute** and choose **Create application**.
2. Select **Pages**, then **Connect to Git**.
3. Choose the GitHub `my-app` repository.
4. For a static HTML site, set the build output directory to `dist`.
5. Save and deploy.

Every future commit to the selected branch can trigger a new Pages deployment.
