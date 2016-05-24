# o11n-package:import-package
* Description: Import an existing vco package into a project structure
* Implementation: com.vmware.o11n.mojo.pkg.ImportPackageMojo
* Language: java

### Available parameters:

#### allPackages (Default: false)
* User property: allPackages
* Import all packages from the server

#### exportHistory (Default: true)
* User property: exportHistory
* Export also the version history

#### ignoreServerCertificate (Default: true)
* User property: ignoreServerCertificate
* Ignore the server certificate when importing a package

#### packageName
* User property: packageName
* Name of the package to be imported

#### project
* User property: project
* (no description available)

#### projectName (Default: ${project.artifactId})
* User property: projectName
* Name of the created project, should be file system friendly

#### serverUrl
* Required: true
* User property: serverUrl
* Server url : user:password@server:port

#### targetDirectory
* User property: basedir
* Target directory where the project should be created. Default value is ${basedir}.