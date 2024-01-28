---
title: Update
taxonomy:
    category: docs
---

In AtroCore system you can install, update, and remove modules directly from the admin area.

To do it you need to go to "Administration > Module Manager" page.

![modules_manager](./_assets/module_manager_en.png)

As you can see, this page consists of three panels:

* **Installed** – a list of modules installed in the system is displayed here along with the following data given in the corresponding columns: module name and description, setting version (* means the latest version), current version of AtroCore and required dependencies.

  ![installed_panel](./_assets/module_manager_installed_en.png)
  
* **Store** – a list of all modules for AtroCore software platform is displayed here along with the description, tags, and status of each module. Tags identify modules by their main features to simplify your search for this or that module. For example: possibility to export or restore data, manage prices, etc. Management options are given in the "Status" column for each module separately. 

  ![store_panel](./_assets/module_manager_store_en.png)

* **Logs** – the history of all updates and upgrades performed by each system user is displayed here.

  ![logs_panel](./_assets/module_manager_logs_en.png)
  
  To view detailed information about any operation, click "View Details"  for the desired operation:
  
  ![logs_detailed](./_assets/module_manager_logs_detailed_en.png)

## System Update
To update the system click on the "Update" button. The system and all installed modules will be automatically updated. Bevor update is done the system maka a backup of itself and the database, to be able to be restored in case of unexpected problems.

> Please note, backup of your assets (files, which are stored in the system) is not done.

## Consideration of the Dependencies

During the update process the system installs the latest available module versions. It is possible, that some modules wil not be updated to the latest available version. The reason for it is the incompatibility of some of your modules with the newest version of the module you try to install.

