# ansible-role-nodejs

Installs configurable versions of:

- `nodejs` (default: 4.x)
- `npm` (default: use version bundled with nodejs)

on:

- Debian: 7 (wheezy) and 8 (jessie)
- Ubuntu: 12.04 (precise) and 14.04 (trusty)

Uses [nodesource's nodejs role][], but can also upgrade `npm` and
can potentially be expanded to support more OS families.

See [the defaults][] for possible configuration variables.

[nodesource's nodejs role]: <https://github.com/nodesource/ansible-nodejs-role>
[the defaults]: <https://github.com/eins78/ansible-role-nodejs-npm/blob/master/defaults/main.yml>
