# Flight MFA

The Flight MFA tool provides a facility for users to manage their
multi-factor authentication configuration.

## Installation

Install from git:

```
git clone https://github.com/openflighthpc/flight-mfa
cd flight-mfa
bin/mfa --help
```

Or install the RPM or DEB from the OpenFlight repos:

```
yum install flight-mfa
apt-get install flight-mfa
```

## Prerequisites

If installing from git, you'll also need to install some other packages.

### EL7

 * Install the `google-authenticator` package (EPEL) and `qrencode` package.

### Ubuntu 18.04

 * TBC.

# Contributing

Fork the project. Make your feature addition or bug fix. Send a pull
request. Bonus points for topic branches.

Read [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

# Copyright and License

Eclipse Public License 2.0, see [LICENSE.txt](LICENSE.txt) for details.

Copyright (C) 2020-present Alces Flight Ltd.

This program and the accompanying materials are made available under
the terms of the Eclipse Public License 2.0 which is available at
[https://www.eclipse.org/legal/epl-2.0](https://www.eclipse.org/legal/epl-2.0),
or alternative license terms made available by Alces Flight Ltd -
please direct inquiries about licensing to
[licensing@alces-flight.com](mailto:licensing@alces-flight.com).

Flight GL is distributed in the hope that it will be
useful, but WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EITHER
EXPRESS OR IMPLIED INCLUDING, WITHOUT LIMITATION, ANY WARRANTIES OR
CONDITIONS OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY OR FITNESS FOR
A PARTICULAR PURPOSE. See the [Eclipse Public License 2.0](https://opensource.org/licenses/EPL-2.0) for more
details.
