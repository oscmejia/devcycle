devcycle
========

devcycle is command line interface that helps to move files from development 
to testing and testing to production
Right now, the following comands are supported:


## Instalation

One line instaltion witht [npm](http://npmjs.org). 

	[sudo] npm install devcycle -g


## Usage

	devcycle [command] [action]
	
Commands: 

## init
initialize project configuration
    
## list
list files in the development folder
    
## stats
count files in each main folder
    
## copyto [action]
copy files between folders. Valid actions are "test" and "prod"
    
## snapshot [action]
perform operations on local snapshots. Valid actions are "add" and "list"

This CLI uses as default the following names for your folders:

* development
* testing
* production
* snapshots

It's also under the assumtion that you will have all 4 folders under the same 
folder, for instance if you application's name is "my-app", your folder estructure
will look like this:

../my-app/development
../my-app/testing
../my-app/production
../my-app/snapshots

## Help

Type the following for an overview of the supported arguments.
		devcycle -h


