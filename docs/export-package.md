# o11n-package:export-package
* Description: Goal which create a vCO package from a given vCO server
* Implementation: com.vmware.o11n.mojo.pkg.VMOExportPackageMojo
* Language: java
* Bound to phase: package

### Available parameters:

#### allowedMask (Default: vef)
* Properties of each element in the package v = view e = edit f = forward (re-distribute) default is 'vef'

#### exportVersionHistory (Default: false)
* Export version history

#### ignoreServerCertificate (Default: true)
* User property: ignoreServerCertificate
* Ignore the server certificate when importing a package

#### outputDirectory
* Required: true
* User property: project.build.directory
* Location of the file.

#### packageFileName
* Required: true
* User property: project.build.finalName
* The name of the Package file to generate. By default use the project final name

#### packageName
* Required: true
* Package name to export from server

#### serverConnection
* Required: true
* Service connection info format : host:port default == localhost:8230

#### serverPassword
* Required: true
* Password used to connect to a server

#### serverUsername
* Required: true
* Username used to connect to a server