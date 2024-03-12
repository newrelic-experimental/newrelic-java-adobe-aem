# newrelic-java-adobe-aem
This repository contains the necessary instrumentation components for monitoring the Adobe AEM product. It contains components from several different Labs repositories for components used by AEM.   
These include   
[Apache Felix](https://github.com/newrelic-experimental/newrelic-java-apache-felix  )   
[Apache Sling](https://github.com/newrelic-experimental/newrelic-java-apache-sling)   
[Apache Jackrabbit](https://github.com/newrelic-experimental/newrelic-java-apache-jackrabbit)   
[Apache Jackrabbit Oak](https://github.com/newrelic-experimental/newrelic-java-apache-jackrabbit-oak)  
[Adobe Granite](https://github.com/newrelic-experimental/newrelic-java-adobe-granite)   
[Adobe AEM API](https://github.com/newrelic-experimental/newrelic-java-aem-api)   

Release contains all the appropriate instrumentation extension jars from these repositories and is updated whenever one of them is updated.   
## Installation ##
1. Download the latest instrumentation release archive.
2. In the New Relic Java Agent directory (directory that contains newrelic.jar), create a new directory named extensions if it does not already exist.
3. Extract the jar files from the instrumentation archive into the extensions directory.
4. Restart the application.


