# Setup

>Download the community version zip file

* Add the file to a desired location
* Add Environmental variable 
* create a new folder called "data\db" in your root drive
    
 * in cmd type
    ```bash
    > mongod
    ```  
* (`this will start the server`)
* let the cmd running and open a new cmd
___
 * in cmd type `mongo`
```c
C:\Users\dev>mongo
MongoDB shell version v4.2.3
connecting to: mongodb://127.0.0.1:27017/?compressors=disabled&gssapiServiceName=mongodb
Implicit session: session { "id" : UUID("216b07bf-cf77-48d1-8fb9-ad1d97438b55") }
MongoDB server version: 4.2.3
Server has startup warnings:
2020-02-12T11:22:14.321+0530 I  CONTROL  [initandlisten]
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten]
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] ** WARNING: This server is bound to localhost.
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] **          Remote systems will be unable to connect to this server.
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] **          Start the server with --bind_ip <address> to specify which IP
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] **          addresses it should serve responses from, or with --bind_ip_all to
2020-02-12T11:22:14.322+0530 I  CONTROL  [initandlisten] **          bind to all interfaces. If this behavior is desired, start the
2020-02-12T11:22:14.323+0530 I  CONTROL  [initandlisten] **          server with --bind_ip 127.0.0.1 to disable this warning.
2020-02-12T11:22:14.323+0530 I  CONTROL  [initandlisten]

```  

____
