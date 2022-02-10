# pybullet-svl

This is the C++ source code repository of the Stanford Vision and Learning Lab fork of the Bullet Physics SDK: real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc.

See the [PyBullet forums](http://pybullet.org) or the [upstream PyBullet GitHub repo](https://github.com/bulletphysics/bullet3) for more details.

## Versioning ##
We version based on the upstream pybullet version our fork is based on, and add an additional version number for internal updates. For example, releases matching pybullet 3.1.6 will be named
3.1.6.1, 3.1.6.2 etc.

To bump to a new version, first download the version bumping script: `pip install --upgrade bumpversion`.

If you simply want to bump a single version of the fork, you can do so by running `bumpversion fork`.

If you want to set the version after syncing to a new upstream version, you can directly set the new version, paying attention to the above pattern: e.g. `bumpversion --new-version 3.1.6.0`.