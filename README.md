# ODI 12.2.1.x Ansible tools


## Components

### Playbooks

#### ODI migration plays

* migrateODIBinaries

* PLAY2

* PLAY3

#### Other plays


### Roles

#### ODI migration roles

* [backupODI](./roles/backupODI/README.md)

Create backups of Oracle Home and all domain directories.

* [installODIBinaries](./roles/installODIBinaries/README.md)

Installs ODI  12.2.1.4 into an existing ORACLE_HOME. 

* [shutdownODI](./roles/shutdownODI/README.md)

Shutdown  all WL server and node manager instances.

* [uninstallODIBinaries](./roles/uninstallODIBinaries/README.md)

Uninstalls ODI and FMW 12.2.1.3 and empties the existing ORACLE_HOME.

* [updateODIDatabases](./roles/updateODIDatabases/README.md)

Migrates ODI 12.2.1.3 database schemas to 12.2.1.4 .

* [updateODIDomains](./roles/updateODIDomains/README.md)

Migrates ODI 12.2.1.3 domains to 12.2.1.4 .

#### Other roles

* [installWDT](./roles/installWDT/README.md)

Installs Weblogic Deployment Tool


### Custom Filter Plugins:

* get_domains
* shutdown_wls_command