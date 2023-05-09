# config/prow

This directory contains the configuration files for the Prow instance running as "Chaotic Prow".

## Apply configurations by committing changes to this directory

There are a plugin called `updateconfig` for Prow, and this plugin will automatically update the configuration files in this directory when a PR is merged.

Ref: <https://docs.prow.k8s.io/docs/components/plugins/updateconfig/>
