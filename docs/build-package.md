# o11n-package:build-package

* Description: Goal which create a vCO package from a given vCO server
* Implementation: com.vmware.o11n.mojo.pkg.VCOPackageMojo
* Language: java
* Bound to phase: package

### Available parameters:

#### allowedMask (Default: vef)
* User property: allowedMask
* (no description available)

#### archiveConfiguration
* The archive configuration to use. See Maven Archiver Reference.

#### excludes
* A list of exclusion filters for the compiler.

#### ignoreServerCertificate (Default: true)
* User property: ignoreServerCertificate
* Ignore the server certificate when importing a package

#### includes
* A list of inclusion filters for the compiler.

#### keystoreLocation
* Required: true
* User property: keystoreLocation
* Location of the keystore for package certificate

#### keystorePassword
* User property: keystorePassword
* Overwrite existing package file

#### packageFileName
* Required: true
* User property: project.build.finalName
* The name of the Package file to generate. By default use the project final name

#### project
* User property: project
* (no description available)

#### sourceDir
* Expression: ${project.basedir}/src/main/resources
* (no description available)