# yaoyao-liu.github.io

[![LICENSE](https://img.shields.io/github/license/yaoyao-liu/minimal-light?style=flat-square&logo=creative-commons&color=EF9421)](https://github.com/yaoyao-liu/yaoyao-liu.github.io/blob/main/LICENSE)

This is the latest version of my homepage's source code. Feel free to use and share.
<br />
For more details, please refer to <https://github.com/yaoyao-liu/minimal-light>.

### Project Architecture

```
.
├── .github/workflows            #  the GitHub workflow setting for the Google Scholar crawler
├── _layouts                  
|   └── homepage.html            #  the html template for the homepage 
├── _sass                     
|   └── minimal-light.scss       #  this file will be compiled into a CSS file to control the style of the page
├── google_scholar_crawler       #  Google Scholar crawler files
├── assets                       #  some JavaScript files and images
├── .gitignore                   #  this file specifies intentionally untracked files that Git should ignore
├── 404.html                     #  404 not found page
├── CNAME                        #  the custom domain, will be used by GitHub page sevice
├── Gemfile                      #  a RubyGems related file
├── LICENSE                      #  the license file
├── README.md                    #  the readme file
├── _config.yml                  #  the Jekyll configuration file, including some options of the page  
├── google2c82924758ed6ef9.html  #  the Google Search Console validation file
├── index.md                     #  the content of the index page, using Markdown
├── minimal-light.gemspec        #  another RubyGems related file
├── robots.txt                   #  this file tells search engine crawlers which URLs the crawler can access
└── sitemap.xml                  #  this file is used to inform search engines about URLs on a website that are available for crawling
```
### Google Scholar Crawler

The instructions for the Google Scholar crawler can be found [here](https://github.com/RayeRen/acad-homepage.github.io).
<br>
Before using that, you need to change the Google Scholar ID in the following file:
https://github.com/yaoyao-liu/yaoyao-liu.github.io/blob/7d16d828a229580815428782fb74d937710eb50e/google_scholar_crawler/main.py#L7

### Using Locally with Jekyll

You need to install [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/) fisrt.

Install and run:

```bash
bundle install
bundle exec jekyll server
```
View the live page using `localhost`:
<http://localhost:4000>. You can get the html files in `_site` folder.


### Acknowledgements

This project uses the source code from the following repositories:

* [pages-themes/minimal](https://github.com/pages-themes/minimal)

* [orderedlist/minimal](https://github.com/orderedlist/minimal)

* [al-folio](https://github.com/alshedivat/al-folio)

* [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)
