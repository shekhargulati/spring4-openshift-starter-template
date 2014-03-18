#Spring 4 starter template for OpenShift#

This is a starter template for developing Spring framework applications on OpenShift. It uses the latest Spring framework release i.e. 4.0.2.RELEASE. 

The project configures Spring application using WebApplicationInitializer. There is no web.xml in this project and everything is configured using annotations.

To deploy the project, run the following command.

```
$ rhc app-create springapp tomcat-7 --from-code  
```

After application is created, you can test the one REST resource exposed by application at http://springapp-shekhar007.rhcloud.com/api/v1/ping.