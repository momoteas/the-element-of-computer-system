Aug 7 2017: video plugin: add "libflashplayer.so" to "~/.mozilla/plugins/" 
Aug 8 2017: packaging management: red hat-like   distribution: low-level tool: rmp; high-level tool: yum;                                               package search commond: red hat: yum search search_string;                                                                               installing a package from repository: red hat: yum install package_name;                                                                 installing a package from a package_file: red hat: rpm -i package_file;                                                                   removing a package: red hat: yum erase package_name;                                                                                     updating package from repository: red hat: yum update;   updating a package from package_file: rpm -U package_file;                       listing installed packages: rpm -qa;                                                                                                     determining if a package in installed:  rpm -q package_name;                                                                             displaying info about an installed package: yum info package_name;                                                                       finding which package installed a file: rpm -qf file_nam;
    chapter - 15 storage media                                                                                                                   commands: mount, umount, fsck, fdisk, mkfs, fdformat, dd, genisoimage(mkisofs), wodim(cdrecord), md5sum;                                 mounting and unmounting storage devices:                                                                                                     linux maintain a single file system tree with devices, this contrasts with other OS such as MS-DOS and Windows that maintain           separate file system trees for each device (for example C:\, D:\). a file named "/etc/fstab (short for "file system table").               /etc/fstab Fields: device, mount point, file system type, options, frequency, order;                                                     viewing a list of mounted file systems:                                                                                                      command: "mount" without arguments. the format of the listing is: "device" on "mount_file" type "file_system_type"                     A mount point is simply a directory somewhere on the file system tree. nothing special about it. it doesn't even have to be             an empty directory, though if you mount a device on a non-empty directory, you will not be able to see the direcoty's previous           contents until you unmount the device.                                                      
  
