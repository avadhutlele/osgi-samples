# osgi-examples
This repository contains few OSGi examples for beginner

Please follow below steps to deploy your application to Karaf server:

After installing karaf, please start it.

```
karaf@root()> bundle:install mvn:com.kodtodya.practice/osgi-example/1.0-SNAPSHOT
```
Above command will provide you bundle id. Please use it in below commands to start and stop bundle:

```
karaf@root()> bundle:start <bundle_id>
karaf@root()> bundle:stop <bundle_id>
```
