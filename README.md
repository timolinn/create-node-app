# Create Node App 😄

This is a simple bash script for creating an express app using [node-starter](https://github.com/timolinn/node-starter) kit (it is fully customizable).

This script was wriiten mostly for personal use, but feel free to make it your own 🙂!

## Installation
+ Clone this repo
```bash
    git clone https://github.com/timolinn/create-node-app
```
+ Then run `cd create-node-app`

Make the script executable on bash:
```bash
    chmod u+x create-node-app
```
The script is ready to use!!! 😁.

## Usage
Go ahead and run any of the commands below
```bash

    ./create-node-app

    // OR

    ./create-node-app newapp

    // OR

    ./create-node-app -s https://github.com/example/another-node-kit

    // For the rest
    ./create-node-app -h
```

## Make `create-node-app` command accessible from anywhere on your system
First create a `bin` in your home directory:
```bash
    mkdir ~/bin
```

Copy the script to the bin folder
```bash
    cp ./create-node-app ~/bin
```

Execute the following command:
```
    // Add this to `.bash_profile` to persist to persist it. Then open a new shell.
    export PATH=$PATH:$HOME/bin
```

That's it! Now you can run `create-node-app` from anywhere.

# Uninstall
Simple run `rm ~/bin/create-node-app`

## Warning
**Doesn't work well if source URL is incorrect**. see TODO

## TODO
+ Add error handling for invalid git url
+ Add support for private repository