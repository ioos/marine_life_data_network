# Contributing

## How this repo is organized
`_docs/` - directory containing documentation pages (in markdown). 

`_data/` - configuration files for the website. Only edit `/_data/sidebars/sidebar_ioos.yml`

`theme/` - **Do not edit** - the Jekyll theme files containing the look and feel and functionality of the site - sourced from the 
[ioos/documentation-theme-jekyll](https://github.com/ioos/documentation-theme-jekyll) repo.

## How to Contribute
The easiest way to get started is to file an issue to tell us about a spelling mistake, some awkward wording,
or a factual error. This is a good way to introduce yourself and to meet some of our community members.

1. If you have a [GitHub][github] account, or are willing to [create one][github-join], but do not know how to use Git,
you can report problems or suggest improvements by [creating an issue][issues]. This allows us to assign the item 
to someone and to respond to it in a threaded discussion.

2. If you are comfortable with Git, and would like to add or change material, you can submit a pull request (PR).
Instructions for doing this are [included below](#using-github).

## Where to Contribute
Contribute your documentation to the `_docs/` directory.

1. Update an existing page.
2. Create a new page.

## Using GitHub

If you choose to contribute via GitHub, you may want to look at [How to Contribute to an Open Source Project on 
GitHub][how-contribute]. To manage changes, we follow [GitHub flow][github-flow]. To use the web interface for 
contributing to a file:

1. Fork the originating repository to your GitHub profile.
2. Within your version of the forked repository, move to the `gh-pages` branch.
3. Navigate to the file(s) you wish to change within the branch and make revisions as required.
4. Commit all changed files within the appropriate branch.
5. Create pull requests from your changed branch to the `gh-pages` branch within the originating 
repository.
6. If you receive feedback, make changes using your issue-specific branches of the forked repository and the pull 
requests will update automatically.
7. Repeat as needed until all feedback has been addressed.

When starting work, please make sure your clone of the originating `gh-pages` branch is up-to-date before creating your own 
revision-specific branch(es) from there.

[github]: https://github.com
[github-flow]: https://guides.github.com/introduction/flow/
[github-join]: https://github.com/join
[how-contribute]: https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github
[issues]: https://guides.github.com/features/issues/