

#### 1. Gem-based Theme Installation

Replace the contents of your `_config.yml` file with the sample [\_config.yml](https://raw.githubusercontent.com/raviriley/agency-jekyll-theme-starter/master/_config.yml).

Install the gem with:

```sh
$ bundle add jekyll-agency
```

Or manually.

1. Add this line to your Jekyll site's `Gemfile`:
   ```ruby
   gem "jekyll-agency"
   ```
2. Then execute:
   ```sh
   $ bundle install
   ```

#### 2. Using the [Starter Template][template]

This is the fastest and easiest way to get up and running on GitHub Pages.

Simply generate your own repository by clicking the button below. Then replace the sample content with your own and configure for your needs.

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)][generate]

</div>
    
#### 3. Remote Theme Installation

Replace your `_config.yml` file with the starter [\_config.yml](https://raw.githubusercontent.com/raviriley/agency-jekyll-theme-starter/master/_config.yml).

Replace your `Gemfile` with the starter [Gemfile](https://raw.githubusercontent.com/raviriley/agency-jekyll-theme-starter/master/Gemfile).

Then install gems.

```sh
$ bundle install
```

<!--
## Documentation and Usage

**TODO:** Write usage instructions here. Describe available layouts, includes, or assets.

navheader is used only for the home page. nav is used everywhere else.

Layouts:

Includes:

-->

## Contributing

This project is intended to be a welcoming space for collaboration. If you have an idea, suggestion, feature request, etc., feel free to open an issue or pull request.

For bug reports, follow the provided template.

#### Improvements - Up for Grabs

- [ ] multiple language support (~~Spanish~~, Chinese, Arabic, etc.)
- [ ] customizable background coloring for each section
- [x] ~~custom background images~~

## Development

To set up your environment to develop this theme, clone this repo or your fork.

```sh
$ git clone https://github.com/raviriley/agency-jekyll-theme.git
$ cd agency-jekyll-theme
```

Then run:

```sh
$ bundle install
```

To test the theme, run this. (Using the `--trace` flag for verbose errors.)

```sh
$ bundle exec jekyll serve --trace
```

Then open your browser at:

- http://localhost:4000

Add pages, documents, data, etc. like normal to test the theme's contents. As you make modifications, your site will regenerate and you should see the changes in the browser after a refresh.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

<!--

## Example Implementations

- [CV Enterprises](https://cventerprises.org)
- [Mortazavi Lab at UC Irvine](https://mortazavilab.github.io/)

-->

[demo-page]: https://raviriley.github.io/agency-jekyll-theme-starter/
[template]: https://github.com/raviriley/agency-jekyll-theme-starter
[generate]: https://github.com/raviriley/agency-jekyll-theme-starter/generate
