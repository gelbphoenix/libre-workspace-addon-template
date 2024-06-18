# Template for Libre Workspace

## Why this template?

This template is pulled directly from the examples in the [Libre Workspace Documentation](https://docs.libre-workspace.org) and for use to create an addon for Libre Workspace.

**DISCLAIMER: This repository is not in any affiliation with the [Libre Workspace Project](https://github.com/Jean28518/libre-workspace) or it's creator [Jean28518](https://github.com/Jean28518).**

## How do I use this template?

After downloading, cloning or forking this repository you should change `[NAME]` to the name of your addon in lowercase.

It should look like this:

```
testaddon/
  - testaddon.conf
  - setup_testaddon.sh
  - update_testaddon.sh
  - remove_testaddon.sh
```

Now you can edit the script files and the config file. Make also sure to add an picture in either png/svg/jpg or webp format and a LICENSE if you want to distribute your addon. (The Apache 2.0 licence is recommended <https://www.apache.org/licenses/LICENSE-2.0.html#apply>)

**IMPORTANT: Please check the [documentation of Libre Workspace](https://docs.libre-workspace.org) for the example with an NocoDB addon**

The example of the structure of an distributed addon would look like this:

```
testaddon/
  - testaddon.conf
  - setup_testaddon.sh
  - update_testaddon.sh
  - remove_testaddon.sh
  - testaddon.webp
  - LICENCE
```

To install the addon in the Libre Workspace Portal you must compress the directory of the addon to a .zip file.
