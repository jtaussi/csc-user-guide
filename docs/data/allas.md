# Allas object storage

Allas object storage is a cloud storage service, where you can store and use data over HTTPS.
Object storage environments, like Allas, manage data as static objects that contain the actual data and
related metadata. When a file is uploaded to Allas, it is stored as an object that can later be downloaded 
or removed, but which can't be directly modified while the object is in Allas. In practice, this means that you
can use Allas to store and read your data, but if you want to modify your data, you must first download the data 
to a server where you do the modifications and then replace the original object with a new version. 

The benefit of an object storage is that it can handle practically any static data and that the data
can be accessed over the internet from any location. Further, the same data can be accessed through several
interfaces: ( command line clients, WWW-interfaces, virtual disk mounts etc.). The data can also be made 
publicly accessible of for authorized users only.



## Technical details
  

##Getting Access

The usage of Allas is based on CSC customer projects. To be able to use allas you need to be a member in 
a CSC project that has a permission to use Allas. If you don't have a CSC account, you must first register as CSC user
and join or start a computing project for which Allas has been enabled. All these steps can be done with the
MyCSC user portal: [https://my.csc.fi]( https://my.csc.fi)


The usage of Allas is based on project based storage quotas. All the project members have equal access rights to the storage 
area that has been granted for the project. In practice, this means that if one user uploads data to Allas, all the other users can read and also delete the data. Allas itself does not store any information about who has uploaded the data to Allas.


##Using Allas in Puhti and Taito



 1.  [Quick and safe: a_put, a_get, a_find](./a_commands.md)

 2.  [Advanced tools: Rclone and swift](./rclone.md)

 3.  [Persistent allas connections: s3cmd](./s3cmd.md)
