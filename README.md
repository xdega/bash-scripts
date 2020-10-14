### vimpdf (osx)

Opens a code file from the terminal, as PDF for printing. Only works for Mac.

Usage: `vimpdf [filename]`

### fr

Carries out a recursive find/replace operation on the specified directory.

Usage `fr [search term] [replacement] [search directory]`

### docker-nuke

Indiscriminately destroys all running or stopped Docker containers. This is useful when needing to clean up a Docker environment after a lot of trial and error from setting up new development workflows

Usage: `docker-nuke`

### docker-php

Runs a given PHP file via the latest stable php-cli Docker container. This is a useful tool to run PHP scripts in a portable context, without relying on inconsistencies of local PHP installs.

Usage: `docker-php [file name]`

### token-gen

Generates a simple uppercase-only ASCII token. These tokens are not ideal for anything that requires encryption, but allows generating simple validation keys that are easy for humans to enter into an interface.

Usage: `token-gen [token size]`
