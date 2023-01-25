Redwood Nhost Auth Integration
==============================

> **Warning**
>
> This package is no longer maintained

Nhost used to be an officially supported auth provider in RedwoodJS. But,
starting in v4, we decided that we needed to cut back on the number of auth
providers we maintain support for. Based on usage statistics, we decided to
stop maintaining the Nhost auth integration.

This was the PR that removed support for Nhost and a few more:
https://github.com/redwoodjs/redwood/pull/7138. That means this was the last
commit that had support for Nhost:
https://github.com/redwoodjs/redwood/commit/3d057db199487ea0b17240317d66ddde3f83f332.

If you want to use Nhost as your auth provider, we recommend that you first
check to see if anyone has forked this repo (by using the
[Network Graph](https://github.com/redwoodjs/nhost/network)) and has an active
fork. If not, you can fork this repo and publish the packages to NPM. That way,
you and the rest of the community can keep using Nhost auth. You can also get
the community's help keeping the Nhost auth integration maintained.

Even though this package is not maintained, you can try it out by running
`yarn rw setup auth @redwoodjs/auth-nhost`. It may or may not work. Finding a
fork of this repo that has published packages to NPM is a better choice. Just
make sure you do your due diligence on their code before you start using it.
