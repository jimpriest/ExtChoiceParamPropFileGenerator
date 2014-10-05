Extended Choice Parameter Property File Generator
====================================================
The application will query a GitLab server for a list of groups, projects and will generate a file containing those project's branches.

This file can then be used with the Jenkins Extended Choice Parameter plugin (https://wiki.jenkins-ci.org/display/JENKINS/Extended+Choice+Parameter+plugi) to display a list of available branches for a selected project.

Prerequisites
===================================
* CFML server (Railo)
* GitLab (7.2+)
* Jenkins CI server
* Jenkins Extended Choice Parameter plugin
