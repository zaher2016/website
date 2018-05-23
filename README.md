# ODK Website

![Platform](https://img.shields.io/badge/platform-Jekyll-blue.svg) [![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/) [![Build status](https://circleci.com/gh/opendatakit/website.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/opendatakit/website/) [![Slack status](http://slack.opendatakit.org/badge.svg)](http://slack.opendatakit.org/)

## Developing locally
1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/). 
1. `gem install bundler`
1. `bundle install`
1. `bundle exec jekyll serve`

The local site will update as changes are made.

## Contributing

One quick way to contribute is to review the [staging website](http://staging.opendatakit.org) and [file issues](https://github.com/opendatakit/website/issues) documenting the problems you see. If you would like to help fix those issues, see [the contribution guide](CONTRIBUTING.md).

## Troubleshooting

Nokogiri (鋸) is a Rubygem providing HTML, XML, SAX, and Reader parsers with XPath and CSS selector support.
Command `bundle install` tries to install `nokogiri`

If you face following error:
	`Gem::Ext::BuildError: ERROR: Failed to build gem native extension.`

You can fix it as follows:

For Ubuntu/Debian OS:
Run the command `sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev` and try again.

If you are using any other OS, you can follow the instructions mentioned here:
http://www.nokogiri.org/tutorials/installing_nokogiri.html
