# SkyDecoder

An application for decoding the contents of astronomical images.

## Introduction

SkyDecoder is a Python application intended to label objects in astronomical images. Initially,
my goal is to create a non-GUI, command-line application. A graphical interface would be nice to
have, but that is a future project.

At the moment, SkyDecoder is in the very early stages of development. The application is not yet
functional in any meaningful way. It is nothing more than a placeholder.

## Setup

SkyDecoder uses the `conda` package manager. Start by installing
[Miniconda](https://www.anaconda.com/download) from the Anaconda website (scroll to the bottom
of the page to find the installer). Then use the command:

```bash
$ conda update -n base -c defaults conda
```

This updates the new installation to the absolute latest vesion of the `conda` tool. Then, in
the SkyDecoder folder, create the `skydecoder_env` environment using the command:

```bash
$ conda env create -f environment.yml
```

The contents of the environment are specified by the provided `environment.yml` file. Creating
the environment will entail downloading the necessary packages from the Anaconda repositories.

You can use the following commands to activate and deactivate the new environment, making the
appropriate Python interpreter and required packages available (or not):

```bash
$ conda activate skydecoder_env
  # ...
  # Do your development, etc., here.
  # ...
$ conda deactivate
```

I've been using Gemini CLI with this project, largely to get experience with AI coding tools. To
install it, first install Node.js with version 18 or higher. Then install the Gemini CLI tool
globally using this command:

```bash
$ npm install -g @google/gemini-cli
```

In the SkyDecoder directory, *after activating the conda environment*, run the command `gemini`
to start the agent. You will be offered a chance to authenticate with Google, which is useful if
you have a paid AI account. Authentication is necessary, of course, to access your paid
features.

## About Me

I'm just a nerdy girl who loves astronomy, photography, and coding. This project is my first
attempt at writing something real.
