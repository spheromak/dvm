## 0.5.1 / 2014-04-29

### Bug fixes

* Pull request [#35][], issue [#8][], issue [#24][], issue [#28][]: Ensure udhcpc is not running for statically defined eth1 interface. ([@fnichol][], [@adamleko][])
* Issue [#33][]: Fix `DOCKER_HOST` variable support under boot2docker 0.8.0. ([@fnichol][])
* Pull request [#31][]: In README, fix link to Docker Remote API. ([@dougireton][])

### Improvements

* Issue [#32][]: Fix VMware Fusion link in READER. ([@fnichol][])
* Conditionally implement TinyCore Linux Vagrant plugin if required. ([@fnichol][])


## 0.5.0 / 2014-04-14

### Bug fixes

* Pull request [#21][]: Fix inability to stop or delete containers if `DOCKER_ARGS` used. ([@yacn][])

### New features

* Pull request [#29][]: Upgrade to [boot2docker 0.8.0](https://github.com/boot2docker/boot2docker/releases/tag/v0.8.0). ([@jfoy][])
* Pull request [#20][]: Allow number of CPUs to be customized via `DOCKER_CPUS`. ([@rubbish][])
* Pull request [#22][]: Allow docker0 CIDR to be specified. ([@yacn][])
* Pull request [#30][]: Use boot2docker's `$EXTRA_ARGS` config option. ([@yacn][])

### Improvements

* Issue [#10][]: Add project rationale, explaining why it uses private IP address. ([@fnichol][])
* Issue [#19][]: Update `dvm check` to attempt to check VMware fusion on Mac. ([@fnichol][])


## 0.4.1 / 2014-02-13

### Bug fixes

* Up version tag in code for `dvm version`. ([@fnichol][])


## 0.4.0 / 2014-02-13

### New features

* Upgrade to [boot2docker 0.5.4](https://github.com/steeve/boot2docker/releases/tag/v0.5.4). ([@fnichol][])
* Support VirtualBox and VMware Fusion/Workstation, thanks to [@mitchellh][] upstream. ([@fnichol][])

### Improvements

* Pull request [#17][]: Install Vagrant and VirtualBox with homebrew-cask. ([@hiremaga][])
* Pull request [#11][]: Spelling updates in README. ([@agoddard][])
* Update inlined plugin code to not collide with Vagrant 1.5.0 support. ([@fnichol][])


## 0.3.0 / 2014-01-16

### New features

* Upgrade to [boot2docker 0.4.0](https://github.com/steeve/boot2docker/releases/tag/v0.4.0). ([@fnichol][])
* Issue [#5][]: Hombrew formula moved to a tap at [fnichol/hombrew-dvm](https://github.com/fnichol/homebrew-dvm). ([@jfoy][], [@fnichol][])

### Improvements

* Ensure that there is a sane DNS resolver on boot for docker daemon. ([@fnichol][])
* Use the host's resolver as a DNS proxy in NAT mode. ([@fnichol][])
* Pull request [#6][]: Add support for fish shell. ([@tlockney][])
* Pull request [#3][]: Update Mac/Docker documentation. ([@gianpaj][])


## 0.2.2 / 2014-01-06

### Bug fixes

* Pull request [#2][]: Explicitly set the provider to virtualbox. ([@hmarr][])

### Improvements

* Pull request [#3][]: Update README since docker is now available via homebrew. ([@gianpaj][])


## 0.2.1 / 2014-01-06

### Improvements

* Update to boot2docker-vagrant-box 0.3.0-1 which sets `shell = "sh -l"`. ([@fnichol][])
* Add `dvm help` subcommand, in addition to `--help` and `-h` flags. ([@fnichol][])


## 0.2.0 / 2014-01-05

### Changes

* Overwrite Vagrantfile on `make install`. ([@fnichol][])

### New features

* Use a Vagrant private network to communicate with Docker VM. ([@fnichol][])
* Add `dvm reload` subcommand. ([@fnichol][])


## 0.1.0 / 2014-01-05

The initial release.

<!--- The following link definition list is generated by PimpMyChangelog --->
[#2]: https://github.com/fnichol/dvm/issues/2
[#3]: https://github.com/fnichol/dvm/issues/3
[#5]: https://github.com/fnichol/dvm/issues/5
[#6]: https://github.com/fnichol/dvm/issues/6
[#8]: https://github.com/fnichol/dvm/issues/8
[#10]: https://github.com/fnichol/dvm/issues/10
[#11]: https://github.com/fnichol/dvm/issues/11
[#17]: https://github.com/fnichol/dvm/issues/17
[#19]: https://github.com/fnichol/dvm/issues/19
[#20]: https://github.com/fnichol/dvm/issues/20
[#21]: https://github.com/fnichol/dvm/issues/21
[#22]: https://github.com/fnichol/dvm/issues/22
[#24]: https://github.com/fnichol/dvm/issues/24
[#28]: https://github.com/fnichol/dvm/issues/28
[#29]: https://github.com/fnichol/dvm/issues/29
[#30]: https://github.com/fnichol/dvm/issues/30
[#31]: https://github.com/fnichol/dvm/issues/31
[#32]: https://github.com/fnichol/dvm/issues/32
[#33]: https://github.com/fnichol/dvm/issues/33
[#35]: https://github.com/fnichol/dvm/issues/35
[@adamleko]: https://github.com/adamleko
[@agoddard]: https://github.com/agoddard
[@dougireton]: https://github.com/dougireton
[@fnichol]: https://github.com/fnichol
[@gianpaj]: https://github.com/gianpaj
[@hiremaga]: https://github.com/hiremaga
[@hmarr]: https://github.com/hmarr
[@jfoy]: https://github.com/jfoy
[@mitchellh]: https://github.com/mitchellh
[@rubbish]: https://github.com/rubbish
[@tlockney]: https://github.com/tlockney
[@yacn]: https://github.com/yacn