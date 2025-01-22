# Folder Queue Manager - FQM
Simple software for ad-hoc Directory Monitoring, command executing, and folder copying/moving software for small tasks

## About

This software is written for the ad-hoc needs of a physics research group [LRG](https://avesis.gazi.edu.tr/arastirma-grubu/lrg/). With the COVID-19 outbreak, the laboratory went to all remote work. However, there were some computational codes needed to run on lab computers. However, because Teamviewer type of remote connection software and Reverse SSH were not working on the lab computers, there was a need for this small software. It is best used with Google Drive and Dropbox type of cloud file management tools.

With this code, you can use your Google Drive or Dropbox as a queue for your computation tool. The program checks a folder (likely in GD or Dropbox Folder). When finds a file (likely a Python script), it copies it to a temp folder (likely a local folder). Then, it executes the file. When the execution of the command finishes, it zips all results and puts them in another folder (again likely a Google Drive or Dropbox folder). Therefore, without using other tools, you can use your Cloud file space as a computation queue. It can be used on many computers you need.

We believe many people may need this kind of software on a day like this. Therefore, we publish it freely as quickly as possible (First release: Mar 25, 2020). Code is very primitive. It is easy to recompile for your needs.

## Getting Involved

FQM needs active development. The development of FQM is a volunteer effort, and you can contribute. Please do not hesitate to send your merge requests.

## Features can be added in Future Releases:

- Not delete folders in the TEMP folder (it can be good for archiving),
- Change the interval of controlling input files,
- Choose output will be zipped or not,
- More than one instance,
- Instance(s) will not work as a child process.

## Maintainer
Sefer Bora Lisesivdin is the original author and the current maintainer of FQM. Please use [his website](https://sblisesivdin.github.io/) for contact.

## Licensing
FQM is free software; you can redistribute it and/or modify it under the terms of the GPLv3 as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.
