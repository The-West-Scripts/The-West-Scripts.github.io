# The West Scripts

## Guide to managing scripts

### Hosting
You can use [GitHub Pages](https://pages.github.com/) to host your userscript. You can then access the file using the following path: `https://the-west-scripts.github.io/<REPO-NAME>/<FILE-NAME>`

Make sure you select the master branch as a source for your GitHub Pages. `Settings->Options->GitHub Pages->Source->master`

#### Migrating Repositories to the org (keeping the commit history)
You can keep the old commits if you already had a repository. Just make a new repository in this organisation and *DON'T* initialise it. Then add a new remote on the old repository and push to the new remote. Your commit history will be kept.

### Contributions 
Everyone in the organisation has `Write` permissions by default to all repositories. It is a script owner's responsibility to decide whether or not he wants to keep it like that

You are free to change the content of this file however you please.

#### Branch rules
You can of course protect the `master` branch if you want full control of what code goes into your script. If you do that make sure you create a `.github/CODEOWNERS` file and add yourself as a Code Owner. More information about that here: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners


## UserScript List

* [TW Best Friends](https://the-west-scripts.github.io/TW-Best-Friends/)
* [TW Kappa](https://the-west-scripts.github.io/TW-Kappa/)
* [Magic Bundle](https://the-west-scripts.github.io/Magic-Bundle/)
* [Equipment Manager](https://the-west-scripts.github.io/Equipment-Manager/)
