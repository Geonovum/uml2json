# uml2json
Best Practise for OGC - UML to JSON Encoding Rules

The current state of the document is found in [document.html](<https://geonovum.github.io/uml2json/document.html>)

## Generating the document

First, metanorma needs to be installed. The general entry point for the documentation on how to install metanorma is located at https://www.metanorma.org/install/. 

Thus far, we have tested on Windows. The docker based installation was not successful, thus the installation instructions at https://www.metanorma.org/install/windows/ were used. The following commands can then be used:

* Command to generate the document (execute in the directory that contains file document.adoc): `metanorma compile --agree-to-terms -t ogc -x xml,html document.adoc`
* Command to upgrade the installation (execute as administrator): `choco upgrade metanorma -y`
* Command to identify the installed metanorma version (e.g. when reporting bugs in the metanorma GitHub repository): `metanorma --version`
