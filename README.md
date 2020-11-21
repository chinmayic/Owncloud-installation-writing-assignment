   ## TOC
  * [Admin tasks](#admin-tasks)
    + [Install](#install)
    + [Configure](#configure)
    + [Add a user account](#add-a-user-account)
  * [User tasks](#user-tasks)
    + [Connect to the ownCloud server](#connect-to-the-owncloud-server)






Welcome to ownCloud: a one-stop solution for file synchronization and sharing.
<br>
This guide helps you to quickly get started with administrator and user tasks on ownCloud.
## Admin tasks
### Install
1. You can install ownCloud manually or with Docker, using the official [ownCloud Docker image](https://hub.docker.com/r/owncloud/server/tags).<br>
    >**NOTE:**
     Before starting the installation, see [System Requirements](https://doc.owncloud.org/server/10.5/admin_manual/installation/system_requirements.html).
2. To install using the Docker image, see [Installing with Docker](https://doc.owncloud.org/server/10.5/admin_manual/installation/docker/).
3. To install manually, do the following:
     1. [Install the required packages](https://doc.owncloud.org/server/10.5/admin_manual/installation/manual_installation.html#install-the-required-packages).
     2. [Download the latest version of ownCloud and install](https://doc.owncloud.org/server/10.5/admin_manual/installation/manual_installation.html#install-owncloud).
     3. [Configure Apache web server](https://doc.owncloud.org/server/10.5/admin_manual/installation/manual_installation.html#configure-the-web-server) and restart it.
     4. Run the [Graphical installation wizard](https://doc.owncloud.org/server/10.5/admin_manual/installation/installation_wizard.html) or install from the [command-line](https://doc.owncloud.org/server/10.5/admin_manual/installation/command_line_installation.html).
   
### Configure
ownCloud allows you to:
- [Configure the ownCloud server](https://doc.owncloud.org/server/10.5/admin_manual/configuration/server/).
- [Convert your database type](https://doc.owncloud.org/server/10.5/admin_manual/configuration/database/db_conversion.html).
- [Configure database on Linux](https://doc.owncloud.org/server/10.5/admin_manual/configuration/database/linux_database_configuration.html).
- [Enable and disable encryption on the ownCloud server using the encryption app](https://doc.owncloud.org/server/10.5/admin_manual/configuration/files/encryption/root.html).
- [Configure external storage](https://doc.owncloud.org/server/10.5/admin_manual/configuration/files/external_storage/).
- [Manage users and groups](https://doc.owncloud.org/server/10.5/admin_manual/configuration/user/).


### Add a user account
1. Log in to the ownCloud web interface with the admin credentials.
2. Navigate to **Users** page.

   ![Users page](/Images/users_page.png)
3. Enter the new user’s **Login Name** and **E-Mail**.
   ![Users page new user](/Images/users-page-new-user.png)
4. Optionally, assign **Groups**.
5. Click the **Create** button.

## User tasks
### Connect to the ownCloud server
1. Download the latest version of the ownCloud Desktop Synchronization Client from the [ownCloud download page](https://owncloud.com/download/#desktop-clients); there are clients for Linux, macOS, and Microsoft Windows.
2. Double-click the downloaded program file to launch the installation wizard.
3. [Run the installation wizard](https://doc.owncloud.com/desktop/2.6/installing.html#installation-wizard).<br>
   After the ownCloud Desktop Synchronization Client successfully connects to the ownCloud server, it will automatically start synchronizing your files.
 


