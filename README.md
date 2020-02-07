# cp2mvs
This z/OS UNIX utility cp2mvs allows to copy data into an MVS data set or a member of an MVS PDS or PDSE data set. Different than standard cp it allocates the PDS as shared by default. If a PDS is accessed already shared standard cp fails while cp2mvs is able to run successfully.
