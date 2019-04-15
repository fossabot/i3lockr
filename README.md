# i3lockr

Distort a screenshot and run `i3lock`.

## Quick Start [[Documentation]](USAGE.md)

```bash
git clone --depth=1 git://github.com/owenthewizard/i3lockr.git && cd i3lockr
cargo install --path .
i3lockr --invert -- --nofork --noempty
```
Remeber to strip the binary!

## Screenshots

Without `--invert`
![screenshot without --invert](.github/no-invert.png)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fowenthewizard%2Fi3lockr.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fowenthewizard%2Fi3lockr?ref=badge_shield)

With `--invert`
![screenshot with --invert](.github/invert.png)

With the default options on a 1080p monitor, `i3lockr` takes less than half a second to run!

## Important Notes

The exit status of `i3lockr` is not reliable!
That means that `i3lockr && systemctl suspend` may not lock the screen if there was an error.

### Coding Style

Obey `rustfmt` and Rust 2018 conventions.

## Contributing

Pull requests are always welcome. See [TODO](TODO.md).

## Versioning

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Changes are documented in the [Changelog](CHANGELOG.md).

See the [tags on this repository](https://github.com/owenthewizard/i3lockr/tags) for available releases.

## Authors

See [the list of contributors](https://github.com/owenthewizard/i3lockr/contributors).

## License

`i3lockr` is primarily distributed under the terms of both the MIT license and the Apache License (Version 2.0).

See [LICENSE-APACHE](LICENSE-APACHE.md) and [LICENSE-MIT](LICENSE-MIT.md) for details.


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fowenthewizard%2Fi3lockr.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fowenthewizard%2Fi3lockr?ref=badge_large)

## Acknowledgments

* [i3lock-fancy](https://github.com/meskarune/i3lock-fancy) by Dolores Portalatin for inspiration.
* [Padlock Icon](padlock.svg) made by [Chanut](https://www.flaticon.com/authors/chanut) from [Flaticon](https://www.flaticon.com) is licensed by [CC 3.0 BY](https://creativecommons.org/licenses/by/3.0/).