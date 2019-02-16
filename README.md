## What have I tried ?

* Update protonmail-bridge (v1.1.0-1 -> v1.1.1-1) to see if it had not been solved during an update.
* Go through the issues and see that there were other derivations that had the same problem with qt5.12 and tried to use a previous version.

## How to test ?

Clone the repository, then run the following command.

```console
$ nix build -f build.nix
```
