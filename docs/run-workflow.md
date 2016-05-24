# o11n-package:run-workflow
* Description: Goal which run a workflow on a server
* Implementation: com.vmware.o11n.mojo.pkg.VMOExecuteWorkflowMojo
* Language: java

### Available parameters:

#### ignoreServerCertificate (Default: true)
* User property: ignoreServerCertificate
* Ignore the server certificate when importing a package

#### outputDirectory
* Required: true
* User property: project.build.directory
* Location of the file.

#### serverConnection
* Required: true
* Service connection info format : host:port default == localhost:8230

#### serverPassword
* Required: true
* Password used to connect to a server

#### serverUsername
* Required: true
* Username used to connect to a server

#### synchro (Default: true)
* Wait for execution end

#### workflowId
* Required: true
* Workflow ID to start
