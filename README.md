# Updating Old Man's Beard status video creation

This repository contains the source files for creating the `Updating Old Man's Beard status` videos. 

It uses video creation software called [Narakeet](https://www.narakeet.com/).

## Folder structure

Each folder is self-contained and includes all files needed to create the video corresponding to the folder name.

The scripts to create the videos are in the script.md file under each folder.

View [the getting started guide](https://www.narakeet.com/docs/script/) to understand the syntax of this script, or the [formatting reference](https://www.narakeet.com/docs/format/) to see all options.

## Video creation

You can either create the video through the Narakeet user interface, or using GitHub Actions. 

### Building using GitHub Actions

This repository contains a [workflow](./.github/workflows/make_omb_status_video.yml) which can be triggered manually.

The resulting workflow run contains a link at the bottom of the page where the video can be downloaded.