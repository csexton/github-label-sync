Radius Networks Github Labels

### Install

You need to have node installed, but once you do you can install the label sync utility with:

```
npm install github-label-sync
```

Copy over the `.env` file, and put you [GitHub Personal Access Token](https://github.com/settings/tokens) in place.

```
cp .env-example .env
```

### Setting up tags on a repo

Usage:

```
./bin/sync org/repo
```

For example:

```
./bin/sync RadiusNetworks/radius-spec
```


