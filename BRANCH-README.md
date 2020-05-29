# ComputeStacks Theme Customizations

This branch will track the current release in use by our WHMCS installation. 

## Setup Local Repo

```bash
git clone git@github.com:ComputeStacks/templates-six.git
git remote add upstream https://github.com/WHMCS/templates-six.git
git checkout computestacks
```

## Update from WHMCS master repo

```bash
git checkout master && git pull upstream master # Lets keep our master in sync as well
git fetch upstream # Make sure we have all the latest release
git checkout computestacks && git merge v7.10.2-release.1 # or whatever the release you would like to merge up to.
```

