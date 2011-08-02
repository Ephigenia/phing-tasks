# PHING-Tasks

A collection of configurable [PHING](http://www.phing.info/trac/) (php based ANT) tasks that can help to organize a projects shell scripts.

# Features / Tasks

* CSS and Javascript minimize via [Yahoo YUI Compressor](http://developer.yahoo.com/yui/compressor/)
* Version Tasks
* Environments with different configurations
* Deploy to different targets via FTP or rsync
* Install tasks that installs ruby gems and git submodules

## Environments

Deploy directly to a specific environment by passing "environment" property in the command line:

	$ phing deploy -Denvironment=test