# Capital Framework Sandbox
## A place to play and edit Capital Framework components.

**Description**: The static sandbox used to test changes to Capital Framework. Includes all existing components.

**Technology stack**:
- Ruby - For installing Jekyll.
- Jekyll - Static site server.
- Node - For managing front-end dependencies.

## Installation

This site is powered by Jekyll a Ruby based static site generator. For front-end tooling and asset management we use Node and Gulp. Before running the site locally you will need these dependencies. We use [homebrew](http://brew.sh/) on Mac OSX to manage installation of software. To install the project dependencies using homebrew enter the following:

```shell
$ brew install ruby
$ brew install node
$ gem install bundler
$ npm install --global gulp-cli
```


To install the site's dependencies, navigate to the project directory and run:

```shell
$ bundle install
$ npm install
```

To launch the site, enter:

```shell
$ npm start
```

This will start the Jekyll server and the Gulp watch task. BrowserSync should launch a new browser window displaying the site at http://localhost:3000.

If you'd prefer to see the site without BrowserSync's live reload, you can access it at http://localhost:4000.

## Troubleshooting

**Deny/Allow connections.** If you encounter the following message:

> Do you want the application “node” to accept incoming network connections?

Hit `Deny` to close the dialog box.

## Getting help

If you encounter issues with the Sandbox, please post an issue in this repo [issue tracker](https://github.com/jimmynotjim/capital-framework-sandbox/issues/). If you encounter issues with Capital Framework components themselves, please post an issue in the [Capital Framework issue tracker](https://github.com/cfpb/capital-framework/issues/).

**Example**

A live demo can be viewed [here](http://jimmynotjim.github.io/capital-framework-sandbox).
For local installation, the local live is at `http://localhost:3000` (see installation instructions).

## Getting involved

We welcome contributions to the Capital Framework and the sandbox itself. If interested, please read through our [contributing page](http://cfpb.github.io/capital-framework/contributing/) on the demo site.

----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)
