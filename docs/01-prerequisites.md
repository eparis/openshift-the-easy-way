# Prerequisites

## Download Required Tools

1. Visit `[try.openshift.com](https://try.openshift.com)` with your web browser
1. Login with a Red Hat Account
1. Download the Pull Secret to location on host (e.g. ~/Downloads/pull-secret)
1. Download the Installer release for your platform

### Linux

```
wget https://github.com/openshift/installer/releases/download/v0.4.0/openshift-install-linux-amd64
chmod u+x ./openshift-install-linux-amd64
export OPENSHIFT_INSTALL_PULL_SECRET_PATH=~/Downloads/pull-secret
```

Next: [Installing the Cluster](02-install.md)
