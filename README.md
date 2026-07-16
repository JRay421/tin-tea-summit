# Economic Mobility Partner Logo Carousel

This repository contains a responsive logo carousel designed for embedding in Google Sites through GitHub Pages.

## 1. Add the logo files

Place your 12 logo image files inside the `images` folder using these exact filenames:

- `creeed.png`
- `e2e-partners.png`
- `e3-alliance.png`
- `education-partnership-permian-basin.png`
- `good-reason-houston.png`
- `prosper-waco.png`
- `rev-partnership.png`
- `rgv-focus.png`
- `t3-partnership.png`
- `commit-partnership.png`
- `up-partnership.png`
- `workforce-solutions-wct.png`

PNG files with transparent backgrounds work best.

## 2. Upload the project to GitHub

1. Sign in to GitHub.
2. Create a new repository.
3. Name it `economic-mobility-carousel`.
4. Choose **Public**.
5. Upload the contents of this folder.
6. Commit the files.

## 3. Turn on GitHub Pages

1. Open the repository.
2. Go to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/root` folder.
6. Click **Save**.

Your site URL will usually be:

`https://YOUR-USERNAME.github.io/economic-mobility-carousel/`

It may take a few minutes to become available.

## 4. Add it to Google Sites

1. Open your Google Site.
2. Select **Insert**.
3. Choose **Embed**.
4. Select **By URL**.
5. Paste the GitHub Pages URL.
6. Resize the embed box as needed.

## Customizing the carousel

### Change the heading

In `index.html`, replace:

`Our Partners`

### Change the speed

In `style.css`, change:

`animation: logo-scroll 50s linear infinite;`

A larger number is slower. A smaller number is faster.

### Remove the cards

In `style.css`, remove the background, border, border-radius, and box-shadow properties from `.logo-item`.
