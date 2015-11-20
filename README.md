# ansible-role-nodejs

Installs configurable versions of:

- `nodejs`
- `npm`

on:

- Debian: 7 (wheezy) and 8 (jessie)
- Ubuntu: 12.04 (precise) and 14.04 (trusty)

Uses [nodesource's nodejs role](https://github.com/nodesource/ansible-nodejs-role),
but also upgrades `npm` and can potentially be expanded to support more OS families.
