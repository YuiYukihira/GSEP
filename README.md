# GSEP

## Getting Started

### 1. Install node

You can download node [here](https://nodejs.org/en/), or from your package manager if on linux.
Make sure you have added it to your path and can run it from the command line.

(I think windows does this for you automatically.)

### 2. Install yarn

Yarn is a package manager for node, it'll let you download all dependencies for the project easily.

You can get it from [here](https://classic.yarnpkg.com/en/docs/install), also available from your package manager in linux.

### 3. Clone The repo

Either use [Gitkraken](https://www.gitkraken.com/) (I recommend this, it'll make things easier for you), [Github for desktop](https://desktop.github.com/) or the Git CLI to clone the repo.

### 4. Install the dependencies

Open a terminal in the directory of the repo, and then run `yarn install` this will install all your dependencies.

You now should've finished setting up the repo.

## Contributing

We are using pull requests to manage the code base, this is so we can review each other's code and work together more easily. The basic process goes like this:

1. Raise an issue on github of what you are doing to let everyone know.

2. Create a new branch off of the tip of `master` branch.

3. Work on your feature/fix on that branch.

4. Once finished push the branch to github.

5. Raise a pull request on github to the `master` branch and assign the person you believe most fit to, to review your code.

6. Once your pull request is reviewed and accepted, it can be merged back into master.

## Notes

- We are using husky and lint-staged to ensure coding style is consistant, if you cannot commit your code check your styling.

- Use the "commit early, commit often" practice. You can read about that and other best pratices with git [here](https://sethrobertson.github.io/GitBestPractices/).

- When writing commit messages write it as the ending to this sentance: "This commit will...", always start with a capital letter and keep them to 72 characters maximum. If you need longer consider making a commit description in a new paragraph.