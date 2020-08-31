# Middleman Boilerplate
A simple way to build static pages with a Rails feel.

## Using

- [Middleman](https://middlemanapp.com)
- [Yarn](https://yarnpkg.com)
- [webpack](https://webpack.js.org) with [Babel](https://babeljs.org)
- [Sass](https://sass-lang.com)

## Init a new project
1. Clone the repository <br>
`git clone git@github.com:dmbf29/middleman-boilerplate.git` `NAME_OF_YOUR_PROJECT`
2. Remove template git <br>
`git remote remove origin`
3. Start a new git repo <br>
`git init`
4. Create repo on Github <br>
`hub create`

### Installation
*Only if you don't have bundler or yarn*
```
gem install bundler
brew install yarn
```

```
bundle install
yarn install
```

## Run a server
- `middleman`

## Deploy
1. `rake publish`
2. Go to your Github repository > settings > github pages (Options) and select your build branch
3. Website is deployed !

## Meta Tags
To use the gem `middlman-metaman`, [follow these setup instructions](https://github.com/cacheventures/middleman-metaman/)

## Preinstalled
- Bootstrap CSS
- Font Awesome CDN
- Webpack

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
