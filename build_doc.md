# Pre-reqs to use jekyll

- [Linking A Custom Domain To Github Pages](https://richpauloo.github.io/2019-11-17-Linking-a-Custom-Domain-to-Github-Pages/)

```console
brew install chruby ruby-install xz
```

```console
ruby-install ruby 3.1.3
```

```console
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.1.3" >> ~/.zshrc # run 'chruby' to see actual version
```
Quick test

```console
ruby -v
```

```console
gem install jekyll
```
# Using Jekyll

[Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)

# Local test

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

```console
cd docs
bundle install
bundle exec jekyll serve
```

Navigate your browser to --> `http://127.0.0.1:4000/website/`

