# apt-repo-droidian-berb

## TIP: Enable an apt repo on Github
- A repo with at least one commit need to be hosted on github.
- Go to the Github repo "Settings".
- Enter to "Pages" from "Code and automation" section
- On the "Branch" section, select the branch you want to publish, keep the root directory and save.
- Wait a minuts for dns updates.

## How to add droidian-berb apt repo:
* Download the last version of the droidian-berb-apt-config-stable and droidian-berb-apt-keyrings packages [from this url](https://github.com/droidian-berb/apt-repo-droidian-berb/tree/main/pool/stable/main/binary-all)

* Install the downloaded packages 
```
sudo dpkg -i droidian-berb-apt-config-stable<last_version> and droidian-berb-apt-keyrings<last_version>
```
* Update the apt archive
```
sudo apt-get update
```
