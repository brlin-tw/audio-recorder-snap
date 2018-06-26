<h1 align="center">
  <img src="snap/gui/audio-recorder.svg" alt="Audio Recorder's Application Icon" title="Audio Recorder's Application Icon" style="height: 256px">
  <br />
  Audio Recorder
</h1>

<p align="center"><b>This is the snap for Audio Recorder</b>, <i>"A free audio-recorder for Linux"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<p align="center">
	<a href="https://build.snapcraft.io/user/Lin-Buo-Ren/audio-recorder-snap">
		<img src="https://build.snapcraft.io/badge/Lin-Buo-Ren/audio-recorder-snap.svg" alt="Build Status of the Snap" title="Build Status of the Snap">
	</a>
</p>

<div align='center'>
	<img src='snap/screenshots/view-main-recording.png' alt='Screenshot of the Snapped Application' title='Screenshot of the Snapped Application' />
</div>

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

## Installation

    sudo snap install --channel=beta audio-recorder
    
    # OPTIONAL: Allow record in removable storage media
    sudo snap connect audio-recorder:removable-media

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## What's Works

* Recording to OGG/MP3 files
* Sound level meter

## What's Not

* Mpris interface doesn't seem to be working
* Dbus interface doesn't seem to be working

## Remaining Tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml) upstream so Audio Recorder can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account.
    - If you have already forked the Snapcrafter template to your account and want to create another snap, you'll need to use GitHub's [Import repository](https://github.com/new/import) feature because you can only fork a repository once.
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update the description of the repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, transfer the snap name from you to snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [ ] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![林博仁(Buo-ren, Lin)'s Avatar](https://www.gravatar.com/avatar/66a5b84972e73e895d5d68d48b1e1e21?size=128)](https://github.com/Lin-Buo-Ren/) |
| :----------------------------------------------------------: |
|   [林博仁<br>Buo-ren, Lin](https://Lin-Buo-Ren.github.io)    |

## Upstream

| [<img src='snap/gui/audio-recorder.svg' style='height: 128px' />](https://launchpad.net/~audio-recorder) |
| :----------------------------------------------------------: |
| [The Audio Recorder Team](https://launchpad.net/~audio-recorder) |
