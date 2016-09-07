---
layout: post
title: Initializing a New Data Project Directory
---
A while ago I read an [essay](http://faculty.chicagobooth.edu/matthew.gentzkow/research/CodeAndData.pdf) about code and data management targeted at social scientists. As a recovering social scientist, I'm guilty of the lax practices they describe.

They recommend (among other things) that project directories be built around /build and /analysis directories, and that each should have an /input, /output, /temp/, and /code directory, along with a run_directory.sh (or .py) script to ensure that the code is fully automated and replicable. 

Of course, manually entering eight mkdir commands was a little annoying, so I wrote this script that automates the process of initializing a new project directory system. You can get it [here](https://github.com/Chris-OKeefe/project_init). Enjoy!
