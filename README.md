# Documentation
https://docs.github.com/en/pages
https://jekyllrb.com/docs/
https://github.com/jekyll/minima/tree/master

# Ruby

## Setup

```
# Add this to .zshrc
eval "$(rbenv init - --no-rehash bash)"

# Install Ruby
brew install rbenv
rbenv install 3.4.2
rbenv global 3.4.2
```

## Maintenance

```
# Gemfile declares the dependencies and versions
# Bump them up for MV upgrades

# ~Patch versions in Gemfile.lock get upgraded by bundler
# Commit these changes to the repo
bundle update

# Download/install the gems for the project
bundle install
```

# Render and serve Jekyll locally

```
bundle exec jekyll serve
```
