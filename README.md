## AI + ML + Robots Jekyll static website source code

Website: [https://ai-ml-robots.github.io](https://ai-ml-robots.github.io)

## Resources

- Using Jekyll on GitHub: https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages
- GitHub MarkDown variant: https://kramdown.gettalong.org/quickref.html
- Jekyll "moonwalk" theme: https://github.com/abhinavs/moonwalk

## Installation: Mac OS X
```
brew install node ruby
```
... then follow **Installation: Common** notes below

## Installation: Ubuntu
```
sudo apt-get install ruby-full build-essential zlib1g-dev
echo 'export GEM_HOME="$HOME/gems"'       >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```
... then follow **Installation: Common** notes below

## Installation: Common for both Mac OS X and Ubuntu
```
gem install rubygems-update
gem install bundler jekyll
jekyll new ai-ml-robots.github.io
cd ai-ml-robots.github.io
```

## Development
```
cd ai-ml-robots.github.io
# Edit web-site source code files
bundle exec jekyll serve --watch  # Re-run only if "_config.yml" changed

firefox http://127.0.0.1:4000     # Refresh when files are changed
```
