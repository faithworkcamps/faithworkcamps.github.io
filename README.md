# Faith Workcamps Home Page

This is the code for the [Faith Workcamps Home Page](https://www.faithworkcamps.com).

![Faith Workcamps Home Page Screenshot](/assets/img/screenshots/faithworkcamps-homepage-screenshot.png)




## Docker quick start

1. If not already present, install docker and docker-compose:
Ubuntu example:
```
sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add –
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu  $(lsb_release -cs)  stable" 
sudo apt-get update
sudo apt-get install docker-ce
sudo usermod -aG docker ${USER}
sudo curl -L "https://github.com/docker/compose/releases/download/1.25.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/bin/docker-compose
sudo chmod +x /usr/bin/docker-compose
sudo reboot
```
2. `git clone` this repo and navigate to it
3. Generate a new [personal access token](https://github.com/settings/tokens/new). Select only the scope repo/public_repo. Copy the generated key.
4. In your repo folder create a new file called .env (`nano .env`) with the following content: JEKYLL_GITHUB_TOKEN=KEY_COPIED_IN_STEP_3
5. `docker-compose up`
6. To test: `http://SERVER_IPADDRESS:4000`




## Ruby and Jekyll quick start

An alternative to using docker is to install Ruby and Jekyll.

1. Install [RVM: Ruby Version Manager](https://rvm.io/rvm/install).
Ubuntu example: 
```
sudo apt-get install software-properties-common git
sudo apt-add-repository -y ppa:rael-gc/rvm
sudo apt-get update
sudo apt-get install rvm
sudo reboot
```
2. Install Ruby: `rvm install ruby`
3. Install Bundler: `gem install bundler`
4. `git clone` this repo and navigate to it
5. Just the first time: `bundle install`
6. To build the site and serve it: `bundle exec jekyll serve -H 0.0.0.0 -P 4000`
7. To test: `http://SERVER_IPADDRESS:4000`

See the [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
documentation for more info.




## Technologies

1. Built with [Jekyll](http://jekyllrb.com/). This website is completely static and exclusively uses Markdown or basic HTML.
1. Hosted on [GitHub Pages](https://pages.github.com/). We're using the [GitHub Pages Gem](https://help.github.com/articles/using-jekyll-with-pages/) and only Jekyll plugins that are [available on GitHub Pages](https://help.github.com/articles/repository-metadata-on-github-pages/).
1. Free SSL and CDN provided by [Cloudflare](https://www.cloudflare.com/).
1. Using [Basscss](http://www.basscss.com/), [Sass](http://sass-lang.com/), [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/icons/), [Hint.css](http://kushagragour.in/lab/hint/), and [Google Fonts](https://www.google.com/fonts) for styling.
1. Using [jQuery](https://jquery.com/), [lazySizes](http://afarkas.github.io/lazysizes/), and [responsive-nav.js](http://responsive-nav.com/) for behavior.
1. Using [Thumbsup](https://github.com/thumbsup/thumbsup) and [our theme](https://github.com/faithworkcamps/theme-cards) for photo gallery generation.
1. Using [Staticman](https://staticman.net/) for comments.
1. Using [UptimeRobot](http://uptimerobot.com/) and [Google Analytics](http://www.google.com/analytics/) for monitoring and metrics.
1. Using [Starefossen's Alpine Docker Image](https://github.com/Starefossen/docker-github-pages) for the docker install.



## License

This code is released under the MIT License. See LICENSE.txt.
