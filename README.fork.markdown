This is a Debianized branch of redis-py tracking upstream, for Ubuntu.

Set up remote for upstream:

    git remote add upstream git://github.com/andymccurdy/redis-py.git

Branches:

- master: contains the pristine source (plus this file), which gets upstream periodically merged into it
- debian: contains the debianization, which gets master periodically merged into it

Tags:

- Any tag ending in -ubuntu represents the same release but debianized for Ubuntu.
