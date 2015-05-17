# Ssniff

*VS Solution giving you jip? Ssniff it for whiffs.*

This is a *sniffer* to catch MS Visual Studio solution and project *smells*  before they leave someone scratiching their head about a runtime or build error e.g. assembly version inconsistencies, .net version project inconsistencies, unsigned assemblies in the GAC...

Rather devs re-figure the same issues over and over, it is the aim that ssniff will grow to increase first time quality productivity for at least one .net developer.

The framework is adaptable for other evelopment platforms.

Sortware integrity is *always* the developer's responsibility - sniffers like this just cut them to the chase. 

## To contribute

Create initial smell classes which represent potential VS .net issues in '/lib/smells' directory. They can start as manual task descriptions (providing results which describe what to do to manually fix somethething) and evolve into functioning software, which will really tell you if you have an issue.

## Current features

+ .net version incompatability automated sniffer
+ some *manual* sniffers
+ notifies visually for found issues (windows 7 and 8, linux, osx)
+ console colours for issues, warnings, and ok results.

## Pre-requesites

Install node js - https://nodejs.org/
Set the NODE_PATH environment variable. 

## Installing ssniff

    >> git clone git@github.com:kzrbill/solution_sniffer.git

or 

    >> git clone https://github.com/kzrbill/solution_sniffer.git

## Run

    >> node sniff C:\Path\To\Solution\Directory\

## Running the tests

    >> jasmine-node .\test\ --verbose







