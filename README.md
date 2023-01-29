[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![ansible-lint](https://github.com/zerwes/git-remembrall/actions/workflows/lint.yml/badge.svg)](https://github.com/zerwes/git-remembrall/actions/workflows/lint.yml)
[![molecule test](https://github.com/zerwes/git-remembrall/actions/workflows/molecule.yml/badge.svg)](https://github.com/zerwes/git-remembrall/actions/workflows/molecule.yml)

# git-remembrall
notification script running on git repos deployed and configured via a ansible playbook ...

## description
In order to avoid git branches diverging to much from the *main* branch and/or to enforce timely intergation of changes made on the *main* branch on prominent files (test configurations, commit checks, submodules, ...) you can run a script on a checkout that will notify the author/commiter of the last commit on the branch in question by mail.

Many parameters can be configured, as the script is implemented as a *jinja2* template:

### configuration
see: [defaults/main.yml](defaults/main.yml)

## tl;dr
[blog post](https://zero-sys.net/ubloit/blog/git-remembrall)
