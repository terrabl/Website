# How to Start Your Project

_A quick an dirty handbook to Terrabl_

> Because this project is in the pre-alpha stage, some functionality may be missing

## To Install Dependencies

```bash
sudo terrabl install [-y || --yes] [-s || --silent] <Installer>
```

### Installer

Terrabl can be used on a few [*nix](https://stackoverflow.com/questions/4715374/what-is-the-meaning-of-nix#answer-4715413) platforms. These include the following supported platforms:

* Mac OSX
* Ubuntu
* RedHat/Fedora

The options for what `Installer` to use are the following:

* `brew`
* `apt`
* `yum`

### Yes

If included, this will agree to any confirmations. -- _use this with caution_

### Silent

Use with `--yes`, if included, this will prevent Terrabl from logging any output.

## To Start Terrabl

> To be implemented next.

```bash
terrabl init [-s || --silent] [/path/to/directory]
```

* Creates `terrabl.yaml` in local directory
* Fills in `terrabl.yaml` from questionnaire
* **-s || --silent**: do not use questionnaire (defaults only)
* **path/to/directory**: use location specified rather than current directory