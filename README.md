# hexo-pug-generated-static-site

1. `npm install hexo-cli -g`
2. clone this repository to your computer
3. CD your way into your projects folder (you will end up with `projects/hexo-pug-generated-static-site`)
2. `npm install` (to expand the package dependancies)
3. Now you need to install the latest "Artemis" theme from within your new project folder: `git clone https://github.com/Dreyer/hexo-theme-artemis.git themes/artemis`
3. Now we can generate our site by running `hexo generate` (to create all the static files)
4. Then you can run the hexo server by running `hexo server`
5. Browse to http://localhost:4000 to see your new site!

If you want to add a page, or post, or any other template file you can do that using the hexo CLI also.

`hexo new post "my blog post"`
`hexo new page "about us"`
`hexo new {scaffolds file} "title of that page"`
