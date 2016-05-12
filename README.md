# mmt
Extending Alfresco MMT to export AMPs from WARs

```
$ mvn clean package
$ cp target/alfresco-mmt-5.1.f.jar /opt/alfresco/bin
$ cd /opt/alfresco/bin
$ java -jar alfresco-mmt-5.1.f.jar export <moduleId> <warFileLocation>
```

Experimental (and incomplete) code.
