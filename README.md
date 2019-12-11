<h1 align="center">
  <img src="https://zdoom.org/w/images/2/25/Circle_gzdoom.png" alt="GZDoom">
  <br />
  GZDoom
</h1>

<p align="center"><b>This is a snap for GZDoom</b>, <i> it is not official in any way! </i>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/fork-and-rename-me"><img src="https://build.snapcraft.io/badge/snapcrafters/fork-and-rename-me.svg" alt="Snap Status"></a>
</p>
-->

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->

# GZDoom snap
This is the Doom source port GZDoom, as a snap. It is still a WIP.

I tried using the newest conventions and so from snapcraft,
but if you have any recommendation or corrections, please do let me know.


## Version
g4.2 (I am still working on the snap itself, the GZDoom version is 4.2)

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### From the store
This snap is now in the store, simply run

    $ snap install gzdoom
	
### Manually
Clone this repo and run

    $ snapcraft

in the git repo (gzdoom-snap). Then install the produced snap with

    $ snap install *.snap --dangerous

## WADs
First run the snap once to generate the directory structure. See *Running GZDoom*. Then put your WADs in **~/snap/gzdoom/current/.config/gzdoom**

## Running GZDoom
Run it from shell:

    $ gzdoom

(ensure **$ which gzdoom** returns **/snap/bin/gzdoom**)

or simply run the desktop entry, called **gzdoom**.

The first time you launch the app, it will inform you that no WADs were found, don't worry! Follow the steps in *WADs* to set up your WADs.

## Problems
* ~~Sound does not seem to be working~~
* The snap has to be run before the directory structure is set up (for WADs/.ini)

## Licenses
See https://github.com/coelckers/gzdoom/tree/master/docs/licenses and https://zdoom.org/wiki/License

(Primarily GPL-3.0)

## Remaining tasks

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account.
    - If you have already forked the Snapcrafter template to your account and want to create another snap, you'll need to use GitHub's [Import repository](https://github.com/new/import) feature because you can only fork a repository once.
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update the description of the repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [ ] Add a screenshot to this `README.md`
  - [ ] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [ ] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Make a post in the [Snapcraft Forum](https://forum.snapcraft.io) asking for a transfer of the snap name from you to snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [ ] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

<!--
## The Snapcrafters

| [![Your Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431/?s=128)](https://github.com/yourname/) |
| :---: |
| [Your Name](https://github.com/yourname/) |
--> 

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->
