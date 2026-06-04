# Group Handbook

A Handbook for SCI-Hy Group at USU.

## Table of Contents

**Part 1: Graduate Student Resources**
- [New arrival information](group_handbook/part1/arrival.md)
- [Degree program](group_handbook/part1/program.md)
- [Course information](group_handbook/part1/course.md)
- [Student funding opportunities](group_handbook/part1/funding.md)
- [Professional conferences](group_handbook/part1/conference.md)
- [Career advice](group_handbook/part1/advice.md)

**Part 2: Computational Resources**
- [Programming basics](group_handbook/part2/programming_basic.md)
- [Software and tools](group_handbook/part2/tool.md)

**Part 3: How-tos**
- [How to do literature review](group_handbook/part3/literature_review.md)
- [How to read and organize papers](group_handbook/part3/reading_paper.md)
- [How to write a scientific paper](group_handbook/part3/writing_paper.md)
- [Miscellaneous](group_handbook/part3/miscellaneous.md)

## Usage

### Building the book

If you'd like to develop and/or build the Group Handbook book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `group_handbook/` directory
4. Run `jupyter-book clean group_handbook/` to remove any existing builds
5. Run `jupyter-book build group_handbook/`

A fully-rendered HTML version of the book will be built in `group_handbook/_build/html/`.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/pinshuai/group_handbook/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
