# YODA-manual
Here you can find all information you need to use the mitarget DM suite YODA.

# The YODA portal
http://yoda-mitarget.medfdm.uni-kiel.de  
The YODA Dm suite can be reached from the CAU Kiel network (from outside via VPN) and from the UKSH clinic network.
You can log in with your CAU RZ E-mail account to the portal.   
Under data you can find the data of the groups you belong to. You can create folders, upload/download files and remove/rename files, if you have the corresponding user rights for the group.  
If you have group manager rights for a group, you can mange the users and their user rights via the Group Manager module (add user, change user rights). Only existing users can login to the YODA portal.  
Additional description can be found in the manuals in PDF format.


# Installation of iCommands
The current version of the iRODS backend of the YODA system is 4.2.7.  
## linux  
The installation of iCommands (command line tool for power user) with the package managers YUM and APT (for redhat and ubuntu) is described on the iRODS website here: https://packages.irods.org/  
For yum the package name is : irods-icommands-4.2.7-1.x86_64.rpm  
## Mac  
To use iCommands with a mac you can install a iCommand version provided by Cyverse. You can find the installation instruction here: https://learning.cyverse.org/ds/icommands/#icommands-installation-for-mac-os-x  
Do not forgert to open a new terminal or to source.  
# Start iCommands
1. create (if it not already exist after the installation of iCommands) the folder .irods in your home directory  
2. copy the here (in this repository) provided irods_environment.json file in the .irods directory and fill in you username.  
3. Type iinit you start the connection to the YODA system.  
4. You will be asked for your password (MS IKMB account).  
5. Test the connection by typing ils.  
6. If this works you can use all the iCommands commands. They are described here: https://docs.irods.org/4.2.8/icommands/user/
