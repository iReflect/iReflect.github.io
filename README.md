# iReflect.github.io
Organisation Information Site

## Setup Instructions
1. Open Terminal.

2. Check whether you have Ruby 2.1.0 or higher installed:
    ```
    $ruby --version
    ruby 2.X.X
    ```
3. If you don't have Ruby installed, [install Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/downloads/).

4. Install Bundler:
    ```
    $ gem install bundler
    # Installs the Bundler gem
    ```
5. Install Jekyll and other dependencies from the GitHub Pages gem:
    ```
    $ bundle install
    Fetching gem metadata from https://rubygems.org/............
    Fetching version metadata from https://rubygems.org/...
    Fetching dependency metadata from https://rubygems.org/..
    Resolving dependencies...
    ```
6. Navigate into the root directory of your local Jekyll site repository.
7. Run your Jekyll site locally:
    ```
    $ bundle exec jekyll serve
    Configuration file: /Users/octocat/my-site/_config.yml
               Source: /Users/octocat/my-site
          Destination: /Users/octocat/my-site/_site
    Incremental build: disabled. Enable with --incremental
         Generating...
                       done in 0.309 seconds.
    Auto-regeneration: enabled for '/Users/octocat/my-site'
    Configuration file: /Users/octocat/my-site/_config.yml
       Server address: http://127.0.0.1:4000/
     Server running... press ctrl-c to stop.
    ```
8. Preview your local Jekyll site in your web browser at `http://localhost:4000`.
