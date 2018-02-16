# atom-ros
[![Build Status](https://travis-ci.org/argenos/atom-ros.svg?branch=master)](https://travis-ci.org/argenos/atom-ros)
[![License](https://img.shields.io/apm/l/badges.svg)](https://github.com/argenos/atom-ros/blob/master/LICENSE.md)
[![Version](https://img.shields.io/apm/v/atom-ros.svg)](https://github.com/argenos/atom-ros/releases/latest)
[![Installs](https://img.shields.io/apm/dm/atom-ros.svg)](https://github.com/argenos/atom-ros/releases/latest)

An atom package for development of Robot Operating System ([ROS](http://www.ros.org/)), including grammars for some common file types and useful snippets.

Contributions are greatly appreciated! Please fork the repository and open a pull request with your additions!

## Installation
This package makes use of the `ini` and `cmake` grammars, to install them use:

    $ apm install language-ini
    $ apm install language-cmake

Finally you can install this package by running

    $ apm install atom-ros

## Features
### Syntax Highlighting
Syntax highlighting for the following file types:
* ROS file types
  * `.msg`, `.srv`, `.action`
  * `.launch`, `.perspective`
* Stage
  * `.world`, `.inc`
* CMakeLists
  Basic highlighting for rosbuild.


### Snippets
Write the following prefixes and use `<Tab>` to autocomplete

#### rospy

#### rosconsole

#### roslaunch
