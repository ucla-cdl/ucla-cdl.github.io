# ucla-cdl.github.io
Code for lab website.

## For development
1. [Install Ruby](https://jekyllrb.com/docs/installation/macos/)

2. Install dependencies:
```sh
bundle install
```

3. Serve website locally:
```sh
bundle exec jekyll serve
```

4. Edit

5. See updates 

6. Repeat steps 4 and 5 until satisfied and push changes


## For production
GitHub Actions builds the site and deploys the generated `_site` artifact to GitHub Pages.

1. In the repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions**.
2. Push changes to `main`.
3. Check the **Actions** tab for the `Build and deploy site` workflow.
4. Check the live site after the workflow finishes.

This site uses `jekyll-scholar`, which is not supported by GitHub Pages' default Jekyll builder. The Actions workflow runs the full Bundler/Jekyll build, then deploys the generated static site to Pages.
