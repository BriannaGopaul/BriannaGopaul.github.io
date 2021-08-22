## New blog post
Change `POST-NAME` and `URL-NAME`
Run in powershell
```bash
cd ~/Documents/BriannaGopaul.github.io; pandoc .\md-blog\POST-NAME.md -o .\blog\URL-NAME.html --template=pandoc/templates/post.html -c ..\styles\page.css --mathjax
```

## Update blog archive
```bash
cd ~/Documents/BriannaGopaul.github.io; pandoc .\md-pages\blog.md -o blog.html --template=pandoc/templates/top.html -c ./styles\page.css
```