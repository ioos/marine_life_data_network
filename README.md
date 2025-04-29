# Marine Life Data Network Recommendations

Guidance for Marine Life Data Network Data and File Formatting.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15304225.svg)](https://doi.org/10.5281/zenodo.15304225)
Biddle, M., Brenskelle, L., & Canonico, G. (2025). Marine Life Data Network Recommendations (v1.0.1). Zenodo. https://doi.org/10.5281/zenodo.15304225

## Contributing to the documentation
See [CONTRIBUTING](CONTRIBUTING.md).

## Deploying site locally
Requirements:
* bundle
* Jekyll

See [IOOS How To: Local Development with Jekyll](https://ioos.github.io/ioos-documentation-jekyll-skeleton/howto.html#local-development-with-jekyll).

Clone this repository:
```commandline
git clone https://github.com/ioos/mbon-docs.git
```
To build the site, in the `mbon-docs/` directory run:
```commandline
bundle exec jekyll serve --config _config.yml --watch --verbose --incremental
```
This will deploy a website at: http://127.0.0.1:4000/mbon-docs/

Make edits to the appropriate markdown files in `_docs/`. 

If changing headers and menus, stop the running server by entering `ctrl-c` in the terminal. Then run:
```commandline
bundle exec jekyll clean
```
Then build the site again.
```commandline
bundle exec jekyll serve --config _config.yml --watch --verbose --incremental
```
And review at http://127.0.0.1:4000/mbon-docs/
