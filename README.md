This is a template DREU project site. You can start with this and modify it in any way you like, so long as it is still hosted in a git repository.

Some pointers to tips:
- [Github pointers](https://help.github.com/en/github/getting-started-with-github)
- [Github pages](https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site#creating-your-site)
- [Markdown](https://www.markdownguide.org/basic-syntax#links)
- [Jekyll](https://jekyllrb.com)
- [Jekyll tips](https://devhints.io/jekyll)

This site is based on [Jekyll Now](https://github.com/barryclark/jekyll-now).

## Quick Start

### Step 1) Fork this site to your User Repository

Fork this repo, then rename the repository to yourgithubusername.github.io:
- Sign into your github account, or make a github account.
- From this repo, click the "Fork" button.
- Once you have forked the repo to your account, in github, go into Settings and edit the name.

Your Jekyll blog will often be viewable immediately at <https://yourgithubusername.github.io> (if it's not, you can often force it to build by completing step 2)

### Step 2) Customize and view your site

Enter your site name, description, avatar and many other options by editing the _config.yml file. 

Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <https://yourgithubusername.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon

> There are 3 different ways that you can make changes to your blog's files:

> 1. Edit files within your new username.github.io repository in the browser at GitHub.com (shown below).
> 2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
> 3. Clone down your repository and make updates locally, then push them to your GitHub repository.

### Step 3) Publish your first blog post

Edit `/_posts/2020-06-01-week1.md` to publish your first blog post. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

> You can add additional posts in the browser on GitHub.com too! Just hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

### Optional Step 4) Modify the style

You can modify the look and feel of your site by modifying style.scss.

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

