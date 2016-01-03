# Packagecloud Recipes

A collection of Ansible plays to build and upload packages to my [Packagecloud Tools repo](https://packagecloud.io/aussielunix/tools)

## Cloud Foundry CLI deb

Ansible playbook that grabs the latest Cloud Foundry cli `.deb` and sends it up to a Packagecloud.io repository.

This playbook assumes you already have ruby and the `package_cloud` gem installed and in your `$PATH`.

## Slack chat Client deb

Ansible playbook that grabs the latest [Slack chat](http://slack.com) `.deb` and sends it up to a Packagecloud.io repository.

This playbook assumes you already have ruby and the `package_cloud` gem installed and in your `$PATH`.

## Direnv deb

Ansible playbook that:

* grabs the latest [direnv](https://github.com/direnv/direnv) source
* compiles it
* creates a `.deb` using [fpm](https://github.com/jordansissel/fpm)
* uploads to my [Packagecloud Tools repo](https://packagecloud.io/aussielunix/tools)
