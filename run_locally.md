# Run Locally

As this codebase is a current version of [tech.gsa.gov](https://tech.gsa.gov/), if you wanted to run locally, it is possible by following these directions.

## Tech at GSA website

This is the website for the GSA Office of the Chief Technology Officer.

## Architecture

This is a [Jekyll-based](http://jekyllrb.com/) website designed to be published on the
[Federalist](https://federalist.18f.gov/) platform.

The website utilizes the [US Web Design Standards](https://standards.usa.gov/).

## Setup

### Prerequisites

#### Ruby

Since this is a Jekyll-based website, you will need [Ruby](https://www.ruby-lang.org/en/). The best way to get
Ruby is to install it via [rbenv](https://github.com/rbenv/rbenv). See the
[rbenv installation instructions](https://github.com/rbenv/rbenv#installation)
to set it up on your system.

#### Node.js and npm

We use [`npm`](https://www.npmjs.com/) along with [`gulp`](http://gulpjs.com/) to manage front-end dependencies. In order to get `npm`, install [Node.js](https://nodejs.org/). You do not strictly need `npm` to work on the website. You only need it if you plan to update the [vendor assets](/assets/vendor/).

To update the vendor assets, run `npm run assets`.

### Building and Previewing

First, install Ruby gem dependencies:

```
bundle install
```

Then you can run the site locally with live reloading:

```
rake serve
```

You should now be able to preview the site on your local machine at [http://localhost:4000/](http://localhost:4000/).
