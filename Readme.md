ngen (Coming soon)
=====

A views, models, routes, controller generator CLI for ExpressJS and Mongooose

Installation
------------

With [npm](http://github.com/isaacs/npm):

	npm install ngen
	
Now fork this project and send me updates :)

CLI
---

	Usage: ngen [action] [options]

    Usage:
      ngen new APP_PATH [options]

    Options:
      -t, [--template=PATH]   Path to an application template (can be a filesystem path or URL)
      -e, [--engine=ENGINE]   Template engine to when generating files
                                ex: ngin new webapp -e jade

    Ngen options:
      -v, [--version]  Show ngen's version number and quit
      -h, [--help]     Show this help message and quit

    Description:
        The 'ngen new' command creates a new ExpressJS application with a default
        directory structure and configuration at the path you specify.

    Example:
        ngen new ~/Code/Node/webapp

        This generates a skeletal ExpressJS installation in ~/Code/Node/weblog.
        See the Readme.md in the newly created application to get going.
