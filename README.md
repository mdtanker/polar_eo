# Guide to Polar Earth Observation

A guide for scientists interested in polar earth observation; what types of data are available, how can you access them, and how can they be used.

## Usage

### Building the book

If you'd like to develop and/or build the Guide to Polar Earth Observation book, you should:

1. Clone this repository
2. Install the necessary dependencies
    - its recommended to install into a virtual environment, for example with `mamba env create --file environment.yml --name polar_eo` and then `mamba activate polar_eo`
3. (Optional) Edit the books source files located in the `book/` directory
4. Run `jupyter-book clean polar_eo/` to remove any existing builds
5. Run `jupyter-book build polar_eo/`

A fully-rendered HTML version of the book will be built in `book/_build/html/`.

If your contributions require a new dependency, add it to `environment.yml` and use `mamba env update --prune --file environment.yml` to install it into your environment.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/mdtanker/polar_eo/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
