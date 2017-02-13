# atom-ros

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
  * `.launch`
* Stage
  * `.world`, `.inc`
* CMakeLists  
  Basic highlighting for rosbuild.

### Snippets
Write the following prefixes and use `<Tab>` to autocomplete

#### rospy

| Trigger | Name | Body |
|---|
| logd | logdebug() |
| |  |

#### rosconsole

#### roslaunch
