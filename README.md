[![All Indy-Node Builds&Tests](actions/workflows/build-all.yml/badge.svg)](actions/workflows/build-all.yml)

# Indy Node Docker Container

This repository aims to provide easy-to-use containers with minimal dependencies to run instances of [Hyperledger Indy Node](https://github.com/hyperledger/indy-node). The primary goal is to support stewards joining an existing Network, but of course the containers can also be used in a stand alone (local/test/...) network. The initial contributions stem from the Container Working Group of [ID Union](https://github.com/IDunion). The repository was contributed to Hyperledger in 2022-02.

Primary artifact are the container images for
- [Indy Node](https://github.com/hyperledger/indy-node-container/pkgs/container/indy-node-container%2Findy_node)
- and the [Indy Node Controller](https://github.com/hyperledger/indy-node-container/pkgs/container/indy-node-container%2Findy_node_controller)
 which are build from the files in [the build folder](build/).

We also provide a few [utility scripts, including a docker-compose file](run/) to help setting up a run time environment for the containers.
See [here](run/) for instructions how to setup and run the indy node images from this repository.


## Contributing

Any contribution is welcome, e.g. documentation, [bug reports, feature request, issues](issues/), blog posts, tutorials, feature implementations, etc. You can contribute code or documentation through the standard GitHub pull request model.

[Please have a look at CONTRIBUTING.md](CONTRIBUTING.md) for details, in particular how and why you need to sign off commits.

## Code of Conduct

Be excellent to each other!

[See CODE_OF_CONDUCT.md for details.](CODE_OF_CONDUCT.md)


## License

Copyright 2020-2022 by all parties listed in the [NOTICE](NOTICE) file

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
   
