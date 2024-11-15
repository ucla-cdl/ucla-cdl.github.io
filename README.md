# ucla-cdl.github.io
Code for lab website.

## For development
Note: use ```dev``` branch
1. [Install Ruby](https://jekyllrb.com/docs/installation/macos/)

2. [Install Jekyll]((https://jekyllrb.com/docs/))

3. Serve website locally: ``bundle exec jekyll serve``

4. Edit

5. See updates 

6. Repeat steps 4 and 5 until satisfied and push changes


## For production
Note: use ```gh-pages``` branch
1. To build and generate files for hosting on Github pages: 
``bundle exec jekyll build``

2. Add Google Fonts to every HTML page's header: 
```HTML
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">

<style> @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap'); </style>
```

3. Add Google Analytics to every HTML page's header: 
```HTML
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-ZBTHQG17YC"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-ZBTHQG17YC');
</script>
```

4. Move the files in ```_site``` in ```dev``` branch into main/top level of ```gh-pages``` branch. 

5. Git add, commit, push

6. Check live!