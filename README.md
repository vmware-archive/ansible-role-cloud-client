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

The MIT license (the �License�) set forth below applies to all parts of the ansible-role-cloud-client project.  You may not use this file except in compliance with the License.�

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
