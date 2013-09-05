## P.net Object Recorder [![Build Status](https://travis-ci.org/cmontemuino/pnet-object-recorder.png?branch=master)](https://travis-ci.org/cmontemuino/pnet-object-recorder)

## Overview
This is an in-memory recording system for Java objects. Every object can be stored, versioned and later retrieved to perform some required processing.
Besides the object's content it is also maintained metadata  about it.

## Prerequisites
* Java JDK-1.6 or higher
* Gradle 1.4 or higher

## To Build this Application
Run 'gradle build' to build jar file

## License
The license is GNU GENERAL PUBLIC LICENSE Version 3.0, see LICENSE.

## Release Notes
Please see NEWS.md in this directory, https://github.com/cmontemuino/pnet-object-recorder/blob/master/NEWS.md

## Bugs and Patches
Report bugs to the GitHub issue tracker. Send patches as pull requests on GitHub.

## Notes for People Having Problems with Repositories
If you are behind a corporate firewall / proxy that prevents you accesing some of the repositories, then try to add a gradle init script:

    allprojects {
        buildscript {
            repositories {
                mavenLocal()
            }
        }
        
        repositories {
            mavenLocal()
        }
    }
    
(Please look at http://www.gradle.org/docs/current/userguide/init_scripts.html to see where you need to put the script file.)