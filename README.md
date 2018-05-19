[![Build Status](https://travis-ci.org/wtanaka/ansible-role-git.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-git)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-git.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-git)

wtanaka.git
===========

Install git

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.git

### `git_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "git" is already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

Author Information
------------------

https://wtanaka.com/
