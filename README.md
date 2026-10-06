# Publishing a website with GitHub Pages

## 1. Create a repository

1. Sign in to GitHub and click **New**.
2. Name your repository `hello-world`.
3. Select **Public** and add a **README**.
4. Click **Create repository**.

## 2. Add a Hello World page

1. Open your repository.
2. Click **Add file → Create new file**.
3. Name the file `index.html`.
4. Paste this code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hello World</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
```

5. Click **Commit changes…** and confirm **Commit changes** to save the file to `main`.

Make sure `index.html` is in the repository's root folder.

## 3. Enable GitHub Pages

1. Open your repository's **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Source**, select **Deploy from a branch**.
4. Select the branch **main** and folder **/ (root)**.
5. Click **Save**.

## 4. Open your website

1. Wait a few minutes for publishing to finish.
2. Refresh **Settings → Pages**.
3. Click **Visit site**.
4. Check that your website displays **Hello World!**
5. Add your website link to this README.

Your website address will look like this:

https://YOUR-USERNAME.github.io/hello-world/

Replace `YOUR-USERNAME` with your GitHub username.

To update your website, edit your files and commit the changes to `main`.
GitHub Pages will publish the changes automatically.