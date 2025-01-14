# Dnsmasq Cookbook CHANGELOG

This file is used to list changes made in each version of the Dnsmasq cookbooks.

## Unreleased

## v0.3.2

- Fix systemd-resolved conflict (fixes #35)

## v0.3.1

- Switch testing from serverspec to inspec

## v0.3.0

- Require Chef 14 as it has builtin hotfle management
- update testing harness to use ServerSpec with Test Kitchen in lieu of MiniTest
- add CONTRIBUTING documentation, update TESTING and README documentation
- changed to circleci for testing

## v0.2.0

- duplicate options support for dhcp and dns conf files, driven by dhcp_options and dns_options attributes
- TFTP support
- Test Kitchen 1.0 coverage for Red Hat 5.9, 6.4, Debian 7.1 and Ubuntu 10.04, 12.04 and 13.04
- Huge thanks to @mattray!

## v0.1.2

- initial version
