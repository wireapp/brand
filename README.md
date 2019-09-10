# Wire — Brand Elements

**Wire** brand assets — logo, symbol, color, text, and typography guidelines.

Published via [GitHub Pages][1] & [Jekyll][2] to [brand.wire.com][3].

## Purpose

- Used by marketing and sales to create presentation slides based on Wire's corporate identity
- Used by customer success when onboarding new team members to introduce them to Wire's look & feel
- Reference by product when working with external designers to create a consistent Wire user experience

## Suggesting changes

- If you find a typo or would like to suggest a new topic for the [writing guidelines][4], you can [create an issue][5].

- If you know how to fix the issue yourself, [submit a pull request][6] with the proposed changes.

---

### Technical details

<details>
<summary>Setting up a local testing environment and formatting code</summary>

## Setting up a local testing environment

The `brand` microsite can be set up to run locally on your computer so you can preview your changes before submitting a pull request.

The instructions below assume you're on a Mac with [Homebrew][7] installed.

1.  Install the latest Ruby version via Homebrew:

    ```sh
    brew install ruby
    ```

2.  Install [Bundler][8]:

    ```sh
    gem install bundler
    ```

3.  Install the GitHub Pages gem and bundled dependencies:

    ```sh
    bundle install
    ```

4.  Run [Jekyll][9]:

    ```sh
    bundle exec jekyll serve
    ```

This runs the site locally, so you can view your local clone of the `brand` microsite at [http://127.0.0.1:4000/][10].

At this stage, what you see there should be identical to the production version of the site at [brand.wire.com][3].

**Note:** For more details, see [Setting up your GitHub Pages site locally with Jekyll][11].

## Formatting code with Prettier

The `brand` microsite uses [Prettier][12] to automatically format code and enforce consistency across the project.

The [prettier-setup][13] installs Prettier and various dependencies, configures formatting rules and sets up commit hooks to ensure files are formatted correctly before commiting.

1.  Install the [yarn][14] JavaScript package manager via Homebrew:

    ```sh
    brew install yarn
    ```

2.  Run `yarn` to install Prettier and dependencies:

    ```sh
    yarn
    ```

Now when you edit any of the JSON, Markdown, Sass, or YAML files in the project, they will be automatically reformatted when you stage your changes in Git.

**Tip:** You can also run Prettier manually via the `yarn fix` command to verify the results before committing.

</details>

[1]: https://pages.github.com
[2]: https://jekyllrb.com
[3]: https://brand.wire.com
[4]: https://brand.wire.com/text/
[5]: https://github.com/wireapp/brand/issues/new
[6]: https://help.github.com/articles/using-pull-requests/
[7]: https://brew.sh
[8]: https://bundler.io
[9]: https://jekyllrb.com
[10]: http://127.0.0.1:4000/
[11]: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
[12]: https://prettier.io
[13]: https://github.com/lipis/prettier-setup
[14]: https://yarnpkg.com
