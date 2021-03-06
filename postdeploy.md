# Post Deploy

## Security

GCP has a lot of good security features by default.  To open an SSH connection to a node, a user needs to authenticate through either the console or the CLI.  Because of the flat global network, all traffic goes over private IPs.  This means less work needs to be done setting up firewall rules than on other platforms.  By default configurations deployed using Cloud Launcher or Deployment Manager are closed off from the internet.

We recommend the following steps to further secure your cluster:

* Turn on authentication for OpsCenter
* Turn on SSL for OpsCenter
* Turn on authentication for DSE nodes
* Turn on SSL for DSE nodes
