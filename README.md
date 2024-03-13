<a href="https://opensource.newrelic.com/oss-category/#new-relic-experimental"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/newrelic/opensource-website/raw/main/src/images/categories/dark/Experimental.png"><source media="(prefers-color-scheme: light)" srcset="https://github.com/newrelic/opensource-website/raw/main/src/images/categories/Experimental.png"><img alt="New Relic Open Source experimental project banner." src="https://github.com/newrelic/opensource-website/raw/main/src/images/categories/Experimental.png"></picture></a>

![GitHub forks](https://img.shields.io/github/forks/newrelic-experimental/newrelic-java-adobe-aem/?style=social)
![GitHub stars](https://img.shields.io/github/stars/newrelic-experimental/newrelic-java-adobe-aem/?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/newrelic-experimental/newrelic-java-adobe-aem/?style=social)

![GitHub all releases](https://img.shields.io/github/downloads/newrelic-experimental/newrelic-java-adobe-aem/total)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/newrelic-experimental/newrelic-java-adobe-aem)
![GitHub last commit](https://img.shields.io/github/last-commit/newrelic-experimental/newrelic-java-adobe-aem)
![GitHub Release Date](https://img.shields.io/github/release-date/newrelic-experimental/newrelic-java-adobe-aem)


![GitHub issues](https://img.shields.io/github/issues/newrelic-experimental/newrelic-java-adobe-aem)
![GitHub issues closed](https://img.shields.io/github/issues-closed/newrelic-experimental/newrelic-java-adobe-aem)
![GitHub pull requests](https://img.shields.io/github/issues-pr/newrelic-experimental/newrelic-java-adobe-aem)
![GitHub pull requests closed](https://img.shields.io/github/issues-pr-closed/newrelic-experimental/newrelic-java-adobe-aem)   
   
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


