# Zlib

Zlib is a compression tool from [http://zlib.net](http://zlib.net).

This is a fork of the original project from [https://github.com/madler/zlib](https://github.com/madler/zlib)

Because as of 2016-10-30 there were 57 commits in develop NOT yet released, 16 Issues and 63 pull requests outstanding, many related to build system on windows issues, this fork was done in order to create windows builds with

1. Known windows fixes applied to source but only in develop (waiting for a release since 2013)
2. Applied PRs with windows source fixes
3. Applied PRs with cmake build fixes (cmake is actually less of a hassle then hand build makefiles or visual studio projects)
4. Applied general source fixes

Because PRs are applied, this means this code is officially a fork of the library, but EVERY change from the official library exists as a PR in the official repo and are documented in CHANGELOG (and maybe someday will be pulled and I don't have to do this anymore)

I'm still waffling on naming - for now I'm using the semver trick of patch level naming - eg pl1 for each release
