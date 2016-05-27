# jquery-palette-color-picker-rails

jquery-palette-color-picker-rails wraps the [JQuery Palette Color Picker](https://github.com/carloscabo/jquery-palette-color-picker) in a Rails engine for simple use with the asset pipeline provided by Rails 3.1 and higher. The gem includes the development (non-minified) source for ease of exploration. The asset pipeline will minify in production.

## Usage

Add the following to your gemfile:

```
gem 'jquery-palette-color-picker-rails'
```

Add the following directive to your Javascript manifest file (application.js):

```
//= palette-color-picker
```

Add the following directive to your CSS manifest (application.css) file depending on which theme you wish to use:

```
*= palette-color-picker
```

## Versioning

jquery-palette-color-picker-rails 1.0.0 == JQuery Palette Color Picker 1.0.0

Every attempt is made to mirror the currently shipping JQuery Palette Color Picker library version number wherever possible. The major, minor, and patch version numbers will always represent the JQuery Palette Color Picker library version. Should a gem bug be discovered, a 4th version identifier will be added and incremented.
