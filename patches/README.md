# Patches (Optional)

You can add optional patches for updates of your addon. For patch files it is good practice to add the date of the patch as a prefix. For example: `1994-01-01_replace_abc_with_xyz.sh`

Patches are applied in the order of the oldest to the newest based on the file name and executed as the root user. Besides that you should keep the addon consistent over time, so it should disable itself one year after patch release.

The environment variables `$DOMAIN`, `$ADMIN_PASSWORD`, `$IP` and `$LDAP_DC` are passed to and are available in the script.

For an example of an patch file see the [Libre Workspace Documentation](https://docs.libre-workspace.org).
