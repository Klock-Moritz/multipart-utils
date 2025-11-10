# multipart-utils
Command line utilities for dealing with multipart content types

## About
This project aims to provide commands for handling `multipart/*` content types.
They allow for the creation of pipes that deal with multiple files at once.
In addition, file attributes like the name can be preserved while processing
files.

Current commands:
- `multicat`: Prints out multiple files as a `multipart/mixed` message

Ideas for future commands:
- `multisplit`: Saves files from multipart message
- `multikeep`: Passes individual files to a command that decides whether they
               should be kept
- `multiedit`: Passes individual files to a command and replaces them with
               the standard output

