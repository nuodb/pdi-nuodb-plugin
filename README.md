Pentaho PDI NuoDB JDBC Plugin
========================

[<img src="https://api.travis-ci.org/nuodb/pdi-nuodb-plugin.png?branch=master" alt="Build Status" />](http://travis-ci.org/nuodb/pdi-nuodb-plugin)

# Description

A plugin for Pentaho PDI (ETL) to enable NuoDB JDBC support in Pentaho.

# Building

    mvn clean install

# Releasing

Keeping the Release 1.0 associated with this project, delete the prior associated artifact and then save, then attach an updated artifact to the release. The Pentaho Marketplace will automatically pick this up.

Only update the release number when a version incompatibility exists for Pentaho and we must change our implementation.

# Installation

Install the plugin via the Pentaho Marketplace:

1. Open Pentaho PDE
2. Select from the menus, Help..Marketplace..
3. Search and Select PDI NuoDB Plugin
4. Click on the Install this Plugin button
5. Restart Pentaho PDE
