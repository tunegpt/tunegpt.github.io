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
gem install jekyll -v 3.9.3
```
# Using Jekyll

[Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)

```console
$ mkdir docs
# Creates a new folder called docs
$ cd docs
$ jekyll new --skip-bundle .
# Creates a Jekyll site in the current directory
```


# Local test

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

```console
mkdir docs
cd docs
```

Edit Gemfile by editing these lines

```
url: "http://tunegpt.ai"
gem "github-pages", "~> 228", group: :jekyll_plugins
```

```console
bundle install
bundle exec jekyll serve
```

Navigate your browser to --> `http://127.0.0.1:4000`


# Customized

https://stackoverflow.com/questions/43670690/suppress-blog-footer-in-jekyll-kramdown

```console
(base) ➜  docs git:(main) ✗ bundle show minima
/Users/borisdev/.gem/ruby/3.1.3/gems/minima-2.5.1
(base) ➜  docs git:(main) ✗ cp -r /Users/borisdev/.gem/ruby/3.1.3/gems/minima-2.5.1/_includes .
```
