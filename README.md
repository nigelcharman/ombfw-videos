# Updating Old Man's Beard status video creation

This repository contains the source files for creating the `Updating Old Man's Beard status` video. 

It uses video creation software called [Narakeet](https://www.narakeet.com/).

## Folder structure

The main script is [Updating OMB status script.md](Updating OMB status script.md). 

View [the getting started guide](https://www.narakeet.com/docs/script/) to understand the syntax of this script, or the [formatting reference](https://www.narakeet.com/docs/format/) to see all options.

The script uses files under [images](./images/) and [videos](./videos/).

## Video creation

You can either create the video through the Narakeet user interface, or using GitHub Actions. 

### Building using GitHub Actions

This repository contains a [workflow](./.github/workflows/make_omb_status_video.yml) which is triggered whenever changes are pushed to the main branch. It can also be triggered manually.

The resulting workflow run contains a link at the bottom of the page where the video can be downloaded.