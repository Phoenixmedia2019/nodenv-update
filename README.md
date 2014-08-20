# nodenv-update

A [nodenv](https://github.com/OiNutter/nodenv) plugin that provides the
`nodenv update` command to update nodenv as well as all installed nodenv plugins.

## Installation

To install nodenv-update, clone this repository into your `~/.nodenv/plugins` directory
(you'll need a recent version of nodenv that supports plugin bundles).

    $ mkdir -p "$(nodenv root)"/plugins
    $ git clone https://github.com/charlesbjohnson/nodenv-update.git "$(nodenv root)"/plugins/nodenv-update

## Usage

    nodenv update

## Credits

Copied from [rbenv-update](https://github.com/rkh/rbenv-update) and modified to work for node.
Idea and style inspired by [nodenv](https://github.com/OiNutter/nodenv).

### Version History

**0.1.0** (August 20, 2014)

* Initial public release. Copied from [rbenv-update](https://github.com/rkh/rbenv-update).

## License

© 2014 Charles B Johnson. Released under the MIT license. See `LICENSE.md` for details.