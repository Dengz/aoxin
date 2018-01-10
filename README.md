# Aoxin Config

Config options for aoxin

## Filter options 

* app_build

Specific the build version of the app. Other build version will be excluded

* min_ios_version

Specific the minimun iOS version supported.

* max_ios_version

Specific the maximun iOS version supported.

## Configuration data

* sync_data

Specific a bunch of data that will be synchronized to iOS client's local cache

* patch_url

Specific the url of the patch file

* reset_login

Specific the the version of client that should be re-login when first-launched.

## Versions

If clients wants to set different value for specific version, then we should create a branch for this version and change the value at that branch. Clients should only access the matched branch's data.
