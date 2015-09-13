# Passed

A simple script to modify password store entries with sed commands

## Installation

### ArchLinux

Get passed-git with your favorite aur helper

### Other systems

Copy passed from this repo somewhere in your path.

#### Dependencies:

- [pass](https://github.com/zx2c4/password-store)
- [ruby](https://ruby-lang.org)

## Usage

run `passed <your sed arguments>`

### Example:

To change `UserName` to `user` in your pass entries run `passed
's/UserName/user/'`

Passed will ask you to confirm each overwrite. If you know what you're doing
you can pipe `yes` to the passed command.
