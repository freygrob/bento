# Bento

Bento is a project that encapsulates [Packer](http://packer.io) templates for building [Vagrant](http://vagrantup.com) base boxes. 

## Requirements

* [Packer](http://packer.io)
* At least one virtualization provider: Virtualbox, VMware Fusion, Parallels Desktop, etc

## Build Your Own Bento Boxes

### Using `packer`

Build a box for Virtualbox:

    $ packer build -only="virtualbox-iso" centos-6.7-x64_86-minimal.json

You can change keyboard layout (default is 'us') to 'fr' (french) with option:

    -var "keyboard=fr" 

## Bugs and Issues

Please use GitHub issues to report bugs, features, or other problems. Please note:

## License & Authors

This Git repository is a fork of http://chef.github.io/bento


```text
Copyright 2012-2015, Chef Software, Inc. (<legal@chef.io>)
Copyright 2011-2012, Tim Dysinger (<tim@dysinger.net>)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
