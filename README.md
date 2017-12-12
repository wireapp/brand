# Wire — Brand Elements

**Wire** brand assets — logo, symbol, color, text, and typography guidelines.

Published via [GitHub Pages][1] & [Jekyll][2] to [brand.wire.com][3].

## Setting up a local testing environment

We recommend you set up the `brand` microsite to run locally on your computer to verify your changes before pushing them to the live site.

The instructions below assume you're on a Mac with [Homebrew][4] installed.

1. Install the latest Ruby version via Homebrew:

   ```sh
   brew install ruby
   ```

2. Install [Bundler][5]:

   ```sh
   gem install bundler
   ```

3. Install the GitHub Pages gem and bundled dependencies:

   ```sh
   bundle install
   ```

4. Run [Jekyll][6]:

   ```sh
   bundle exec jekyll serve
   ```

This runs the site locally, so you can view your local clone of the `brand` microsite at [http://127.0.0.1:4000/][7].

At this stage, what you see there should be identical to the production version of the site at [brand.wire.com][3].

**Note:** For more details, see [Setting up your GitHub Pages site locally with Jekyll][8].

## Formatting code with Prettier

The `brand` microsite uses [Prettier][9] to automatically format code and enforce consistency across the project.

The [prettier-setup][10] installs Prettier and various dependencies, configures formatting rules and sets up commit hooks to ensure files are formatted correctly before commiting.

1. Install the [yarn][11] JavaScript package manager via Homebrew:

   ```sh
   brew install yarn
   ```

2. Run `yarn` to install Prettier and dependencies:

   ```sh
   yarn
   ```

Now when you edit any of the JSON, Markdown or Sass files in the project, they will be automatically reformatted when you stage your changes in Git.

**Tip:** You can also run Prettier manually via the `yarn fix` command to verify the results before committing.

[1]: https://pages.github.com
[2]: https://jekyllrb.com
[3]: https://brand.wire.com
[4]: http://brew.sh
[5]: http://bundler.io
[6]: http://jekyllrb.com
[7]: http://127.0.0.1:4000/
[8]: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
[9]: https://prettier.io
[10]: https://github.com/lipis/prettier-setup
[11]: https://yarnpkg.com
