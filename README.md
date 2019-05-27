Deploy new release script:
```
mvn deploy:deploy-file \-DgroupId=ca.psiphon \
-DartifactId=psiphontunnel \
-Dversion=<library version in form of 1.2.3> \
-Dpackaging=aar \
-Dfile=<path to the ca.psiphon.aar> \
-Durl=file://<full path to the root this git repo in the filesystem> \
-DgeneratePom=true \
-DcreateChecksum=true
```
