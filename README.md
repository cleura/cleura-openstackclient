# `cleura-openstack`

Conveniently installs OpenStack clients for Cleura Cloud.

## Purpose

By `pip`-installing this meta-package into a virtual environment (venv), you populate your environment with [OpenStack](https://openstack.org) clients whose versions are guaranteed to work with [Cleura Cloud](https://docs.cleura.cloud).

This package provides no functionality of its own; it only installs dependencies.

## Installation

To install directly from this repository, run:

```shell
pip install git+https://github.com/cleura/cleura-openstack@v0.0.1
```

Then, invoke the `openstack` command provided by the `python-openstackclient` package.

## License

Just like all other OpenStack client packages, `cleura-openstack` uses the Apache 2 license.
See [`LICENSE.txt`](LICENSE.txt) for details.
