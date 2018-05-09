# opendatakit.org

This site is powered by [Jekyll](https://jekyllrb.com) and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Developing locally
1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/). 
1. `gem install bundler`
1. `bundle install`
1. `bundle exec jekyll serve`

The local site will update as changes are made.

## Contributing

One quick way to contribute is to review the [staging website](http://staging.opendatakit.org) and [file issues](https://github.com/opendatakit/website/issues) documenting the problems you see. If you would like to help fix those issues, see [the contribution guide](CONTRIBUTING.md).

##Tourbleshooting

While running `bundle install` if you get error like:
	`Gem::Ext::BuildError: ERROR: Failed to build gem native extension.`
Run the command `sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev` and try again.

