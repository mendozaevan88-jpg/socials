# Evan's portfolio

A one-page personal site with a liquid glass look: floating, draggable windows over a blurred photo background. It has my social links and my guitar cover of *Creep*.

Everything is in one file, `index.html`. The photos are built into it, so there are no image files to upload and no build step.

## Run it

Open `index.html` in a browser. The fonts (Bricolage Grotesque and Figtree) load from Google Fonts, so you need an internet connection.

## Put it online with GitHub Pages

1. Make sure the file in your repository is named exactly `index.html` and sits in the main folder, not inside another folder.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. Wait a few minutes. Your site appears at `https://<your-username>.github.io/<repo-name>/`.

If you still see an old version, do a hard refresh (Ctrl+Shift+R, or Cmd+Shift+R on a Mac) and check the **Actions** tab for a finished "pages build and deployment" run.

## Make it yours

- **Text:** edit the `hello.txt` window in `index.html`.
- **Links:** edit the `href` addresses in the socials window.
- **Guitar cover:** change the TikTok link in the `guitar-cover` window and the title under the picture.
- **Glass style:** edit the `.glass` rule in the CSS.
- **Photos:** the pictures are stored as long `data:image/jpeg;base64,...` text near the bottom of the file, in the `I` list in the script. To use your own, convert a photo to base64 and replace one of those entries. Or change the `I` list to plain file names like `"photo1.jpg"` and upload the images next to `index.html`.

## License

The code is under the [MIT License](LICENSE).

The photos inside `index.html` are personal and are **not** covered by the MIT License. All rights reserved. If you reuse this template, replace them with your own.
