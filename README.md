# GitHub Workshop

This is a practical workshop consisting of common GitHub-related actions.

First of all, clone the [repository](https://github.com/rosedu/workshop-github):

```console
git clone https://github.com/rosedu/workshop-github
cd workshop-github/
```

And let's get going! 🚀

## View GitHub Repositories

Take a look at the following repositories:

- [`unikraft/unikraft`](https://github.com/unikraft/unikraft)
- [`microsoft/openvmm`](https://github.com/microsoft/openvmm)
- [`nodejs/node`](https://github.com/nodejs/node)

Do a tour of as much information as possible about them:

- See statistics about the programming languages used.
- See information about contributors.
- See number of stars and number of forks.
- Take a quick look at the issues and pull requests.

### View Projects

Take a look at the [GitHub projects for the `unikraft` organization](https://github.com/orgs/unikraft/projects).
Browse the projects.

Look at the [`Release - Next` GitHub project](https://github.com/orgs/unikraft/projects/47).
Browse the items in the list.
Browse different views (tabs) in the projects.

### View Pull Requests

Take a look at [pull requests in the `unikraft` repository](https://github.com/unikraft/unikraft/pulls).
Select 3 pull requests and check them out.
Look at the discussions, changes, checks for each pull request.

Identify a pull request that is connected to an issue.

Select pull requests that have been authored by `michpappas`.

Select pull requests that are to be reviewed by `michpappas`.

Select pull requests that use the `area/plat` label.

## Set Up GitHub

Let's set up GitHub for proper use.

### Add Your Public SSH Key

If you haven't already, add your public SSH key to your GitHub account.
Follow the instructions [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

### Create a Personal Access Token

Create a personal access token to use as an authentication mechanism for GitHub.
Follow the instructions [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic).
Add all permissions to the personal access token.

## Set Up GitHub CLI

Follow the instruction [here](https://cli.github.com/) and install GitHub CLI.

Authenticate to GitHub:

```console
gh auth login
```

Use the username and the personal access token above to authenticate.

### Use GitHub CLI

Then clone the three repositories above:

```console
git clone https://github.com/unikraft/unikraft
git clone https://github.com/microsoft/openvmm
git clone https://github.com/nodejs/node
```

For each repository, use the GitHub CLi tool to:

- List repository issues.
- List repository pull requests.
- List repository pull requests whose state is `closed`.
- View details about a pull request.

## Work with Pull Requests

### Review and Merge Pull Requests

Create repository and pull requests automatically.

Review and merge pull requests.

Reset and repeat.

### Create Pull Requests

Create commit and branches.

Push

Create pull request.

Review end merge.

Reset and repeat.

## Collaborate with GitHub

Submit PR to a repository of someone else - use a fork.

## Your Own Repository

Work in pairs.

Create repository, fill all items, tabs.
Create initial commits.
Create issues.

Solve issues from others.
