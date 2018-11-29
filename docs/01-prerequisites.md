# Prerequisites

## Download Required Tools

1. Visit `try.openshift.com` with your web browser
1. Login with a Red Hat Account
1. Download the Pull Secret to location on host (e.g. ~/Downloads/pull-secret)
1. Download the Installer release for your platform

### Linux

```
wget https://github.com/openshift/installer/releases/download/v0.4.0/openshift-install-linux-amd64
chmod u+x ./openshift-install-linux-amd64
export OPENSHIFT_INSTALL_PULL_SECRET_PATH=~/Downloads/pull-secret
```

**User Friction**
1. above is not obvious and should be on `try.openshift.com`
1. having a stable download url for latest would be nice up to release
1. the pull secret that a user can copy to clipboard is not pastable into install (contains new-lines)
1. the pull secret is rendered in install when using wizard (should be ***)
1. no place to download client tools but they are needed after install

Next: [Installing the Cluster](02-install.md)