# EclipseGO
The following steps show how to setup and use Eclipse with GOLang, 
* Eclipse Mars is the minimum Pre-req
* Java 8 is required to run GOClipse

## Install Eclipse J2EE from eclipse.org

http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/mars2 

Note: J2EE version is required for Node JS support and not GO, Java works for GO

## Get GoClipse prerequisites 

 *  go get github.com/nsf/gocode
 *  go get golang.org/x/tools/cmd/oracle

## Install and setup GoClipse
 * Start Eclipse and accept default workspace, by clicking on Eclipse executable in the root of Eclipse directory
 * From File Menu→ Help→ Install New Software → and click the add button
 * Set the location to http://goclipse.github.io/releases and name it goclipse
 * Click on OK
 * Wait for the list to get populated
 * Choose GoClipse from the list as follows:
 * Click on Next and accept all later on
 * Restart Eclipse after install
 * From File Menu → Eclipse → Preferences → Go
 * Set GOROOT to /usr/local/go
 * Accept the Gopath and projects 
 * Switch to Go→ Tools
 * Browse to gocode, oracle and godef which has been already installed in $GOPATH/bin
 * Accept all other defaults
 * Click on OK
 
## Build a GO project
 * File Menu → New → Go Project
 * Name the project
 * Uncheck Use Default location 
 * Type in the GOPath location in the Directory field
 * Click on Finish
 
 Any source code in GOPath/src is accesssible to debug and run in Eclipse 
