# Faith Workcamps Home Page

This is the code for the [Faith Workcamps Home Page](http://www.faithworkcamps.com).

![Faith Workcamps Home Page Screenshot](/assets/img/screenshots/faithworkcamps-homepage-screenshot.png)

Forks and pull requests are welcome!




## Quick start

1. Use Git to clone this repo.
2. Install [RVM: Ruby Version Manager](https://rvm.io/rvm/install).
Ubuntu example: 
```
sudo apt-get install software-properties-common
sudo apt-add-repository -y ppa:rael-gc/rvm
sudo apt-get update
sudo apt-get install rvm
```
3. Install Ruby. `bundle install`
4. Install Bundler. `gem install bundler`
5. Just the first time: `bundle install`
6. To build the site and serve it: `bundle exec jekyll serve -H 0.0.0.0 -P 4000`
7. To test: `http://SERVER_IPADDRESS:4000`

See the [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
documentation for more info.




## Docker quick start

As an alternative to installing Ruby and Jekyll, if you're a user of
[Docker](https://www.docker.com/) and [Docker
Compose](https://docs.docker.com/compose/), you can run a Docker image that has all the dependencies already setup for you.

1. `git clone` this repo
1. `docker-compose up`
1. To test: `http://SERVER_IPADDRESS:4000`




## Technologies

1. Built with [Jekyll](http://jekyllrb.com/). This website is completely static
   and exclusively uses Markdown or basic HTML.
1. Hosted on [GitHub Pages](https://pages.github.com/). We're using the
   [GitHub Pages Gem](https://help.github.com/articles/using-jekyll-with-pages/)
   and only Jekyll plugins that are
   [available on GitHub Pages](https://help.github.com/articles/repository-metadata-on-github-pages/).
1. Using [Basscss](http://www.basscss.com/), [Sass](http://sass-lang.com/),
   [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/icons/),
   [Hint.css](http://kushagragour.in/lab/hint/),and
   [Google Fonts](https://www.google.com/fonts) for styling.
1. Using [jQuery](https://jquery.com/), [lazySizes](http://afarkas.github.io/lazysizes/),
   and [responsive-nav.js](http://responsive-nav.com/) for behavior.
1. Using [Disqus](https://disqus.com/websites/) as a commenting system.
1. Using [UptimeRobot](http://uptimerobot.com/) and
   [Google Analytics](http://www.google.com/analytics/) for monitoring and
   metrics.




## License

This code is released under the MIT License. See LICENSE.txt.
