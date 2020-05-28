# Android-Note-Exception

### java.net.ConnectException: Failed to connect to /10.35.233.224:3000

cause by use 4G not use same wifi, route or fireware.

reference : https://stackoverflow.com/questions/28167054/java-net-connectexception-failed-to-connect-to-192-168-253-3-port-2468-conn

### No excexption catched : (WifiManager)getscanresults is empty

cause by miss permission 

sol : before use this method call permission check box, let user check it manu.

reference : https://www.hellojava.com/a/48685.html

### app:mergeDebugResources keep not success always

what : when use api 26 to build app will keep in app:mergeDebugResources always(sometimes not)

why : maybe fireware or grandle version support by 32bit(not sure) 

how : have not good solution now
