# dmoxpress
Just a clone of WRH app which accesses data in an external backend DB.
By "external" I mean outside of the Openshift Cluster (i.e. a standard MySQL DB build using the standard Michelin tools & standards)

This project just embeds a WAR file. Note that this WAR file is generated by the standard Jenkins Xpress build job.
After that, it has been manually updated to reference the external DB (connection string & user+pass).
Of course, the target tis that all this is done by Jenkins ... but so far, Jenkins is not 'openshift'-compliant ... Let's be patient :)
