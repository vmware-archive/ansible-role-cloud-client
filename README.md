# ansible-role-cloud-client

Ansible role for installing and configuring [CloudClient](https://code.vmware.com/tool/cloudclient/), a CLI tool for interacting with vRealize Automation APIs.

### Requirements

This role currently supports Debian/Ubuntu, CentOS/RHEL, and OSX distros.

### Testing

This role uses molecule as a testing framework.  Run the following to install molecule and its driver(s):

```
pip install molecule
pip install python-vagrant
```

Then, setup an `extra_vars.sh` file with your target endpoints and source this file.  A sample file is provided that
you can copy and update.

Then, run your tests:

```
molecule test
```

## Contributing

The ansible-role-cloud-client project team welcomes contributions from the community. Before you start working with ansible-role-cloud-client, please read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License and Copyright

ansible-role-cloud-client

Copyright 2017 VMware, Inc.  All rights reserved

SPDX-License-Identifier: MIT OR GPL-3.0-only

This code is Dual Licensed MIT or GPLv3
