## Changes

### 1.6.2 (pending)

* update help 3.3.0 to 3.4.0
* update javadoc 3.4.1 to 3.5.0
* update deploy plugin 3.0.0 to 3.1.1
* update compiler plugin 3.10.1 to 3.11.0
* update surefire/failsafe plugin 3.0.0-M7 to 3.0.0.
* update project-info plugin 3.4.1 to 3.4.2
* update dependency plugin 3.3.0 to 3.5.0
* update checkstyle plugin 3.2.0 to 3.2.1
* update maven-install-plugin 3.1.0 to 3.1.1
* update resource plugin 3.3.0 to 3.3.1
* update enforder plugin 3.1 to 3.2.1


### 1.6.1 (2022-12-04)

* added legacy-distribution profile, activated if file `src/legacy-distribution` exists
* update maven-plugin-plugin 3.6.0 to 3.7.0
* update maven-dependency-plugin 3.1.2 to 3.3.0 and remove analyze only execution
* update maven-install-plugin 3.0.1 to 3.1.0
* update maven-antrun-plugin 3.0.0 to 3.1.0


### 1.6.0 (2022-10-08)

* changed coordinates to de.schmizzolin.maven.poms:parent
* changed default branch to main
* bump java 16 to 17

* update distribution management to new sonatype hosts
* update checkstyle plugin 3.1.2 to 3.2.0
* update jar plugin 3.2.2 to 3.3.0
* update jxr plugin 3.2.0 to 3.3.0
* update help plugin 3.2.0 to 3.3.0
* update project-info plugin 3.3.0 to 3.4.1
* update javadoc plugin 3.4.0 to 3.4.1
* update resource plugin 3.2.0 to 3.3.0
* update install plugin 3.0.0-M1 to 3.0.1
* update deploy plugin 3.0.0-M1 to 3.0.0
* update site plugin 3.12.0 to 3.12.1


### 1.5.2 (2022-06-15)

* update clean plugin 3.1.0 to 3.2.0
* update compiler plugin 3.8.0 to 3.10.1
* update surefire and failsafe plugin 3.0.0-M5 to M7
* update spotbugs 4.1.4 to 4.6.0.0
* update jar plugin 3.2.0 to 3.2.2
* update javadoc plugin 3.2.0 to 3.4.0
* update war plugin 3.3.1 to 3.3.2
* update scm plugin 1.11.2 to 1.12.2
* update enforcer 3.0.0-M3 to 3.1.0
* update site plugin 3.9.1 to 3.12.0
* update doxia-module-markdown 1.9.1 to 1.11.1
* update jxr plugin 3.1.1 to 3.2.0
* update project-info plugin 3.1.2 to 3.3.0


### 1.5.1 (2021-05-10)

* update jxr plugin 3.0.0 to 3.1.1
* update project-info plugin 3.1.1 to 3.1.2
* update gpg plugin 1.6 to 3.0.1 - CAUTION: released now need mvn release:perform "-Darguments=-Dgpg.passphrase=thePassPhrase"


### 1.5.0 (2021-04-08)

* configure src/main/filtered-resources for filtered resources
* compiler plugin: enable general warnings and deprecation warnings  
* raised default Java Version from 11 to 16
* update checkstyle 8.37 to 8.40
* update checkstyle plugin 3.1.1 to 3.1.2
* update scm-publish-plugin 3.0.0 to 3.1.1


### 1.4.2 (2020-11-30)

* update spotbugs-maven-plugin 4.0.0 to 4.1.4
* update versions-maven-plugin 2.7 to 2.8.1
* update checkstyle engine 8.29 to 8.37
* update markdown 1.9 to 1.9.1
* dumped extra dependencies from surefire plugin
* fixed missing version warning for surefire report
* removed hardcoded Javadoc Links to Jdk, Slf4j and Junit from report generation


### 1.4.1 (2020-10-12)

* removed hardcoded Javadoc Links to Jdk, Slf4j and Junit (because Junit is down every now and then)


### 1.4.0 (2020-10-12)

* raised default Java Version from 8 to 11
* update war plugin 3.2.3 to 3.3.1
* update antrun plugin 1.8 to 3.0
* update checkstyle plugin 3.1.0 to 3.1.1
* update dependency plugin 3.1.1 to 3.1.2
* update javadoc plugin 3.1.1 to 3.2.0
* update site plugin 3.8.2 to 3.9.1
* update maven-project-info-reports-plugin 3.0.0 to 3.1.0  (TODO: no on maven central yet ...)
* update project-info-reports 3.1.0 to 3.1.1
* update spotbugs-maven-plugin 3.1.11 to 4.0.0
* update surefire plugin 3.0.0 M4 to M5
* update resource plugin 3.1.0 to 3.2.0


### 1.3.4 (2020-02-04)

* update checkstyle 8.21 to 8.29
* update source plugin 3.2.0 to 3.2.1
* CAUTION: do not update release plugin 2.5.3 to 3.0.0-M1 because of https://issues.apache.org/jira/browse/MRELEASE-973


### 1.3.3 (2019-11-29)

* update enforder plugin 3.0.0-M2 to 3.0.0-M3


### 1.3.2 (2019-11-20)

* update surefire and failsafe plugin 2.22.2 to 3.0.0-M4
* update jar plugin 3.1.2 to 3.2.0
* update source plugin 3.1.0 to 3.2.0


### 1.3.1 (2019-08-08)

* update javadoc plugin 3.1.0 to 3.1.1
* update site plugin 3.7.1 to 3.8.2


### 1.3.0 (2019-06-24)

* run checkstyle during `validate` phase
* added war plugin 3.2.3 to the managed plugins
* update checkstyle plugin 3.0.0 to 3.1.0
* update checkstyle library 8.15 to 8.21
* update surefire+failsafe plugin 2.22.0 to 2.22.2
* update javadoc plugin 3.0.1 to 3.1.0
* update source plugin 3.0.1 to 3.1.0
* update spotbugs 3.1.8 to 3.1.11
* update help plugin 3.1.0 to 3.2.0
* update jar plugin 3.1.0 to 3.1.2
* update scm plugin 1.11.1 to 1.11.2
* update doxia markdown module 1.8 to 1.9


### 1.2.0 (2019-01-29)

* checkstyle update
  * update to checkstyle 8.15
  * change checkstyles rules to cip rules


### 1.1.0 (2018-12-07)

* inline foss-parent with these changes:
  * removed dependency management
  * removed profiles: foss-parent-run-its, foss-parent-enable-invoker-log-output-on-travis, 
    foss-parent-enable-githubreport-when-not-on-travis, foss-parent-spock-tests, plexus-component-metadata
  * removed plugins: assembly, findbugs, invoker, jacoco, jgitflow, pmd
  * removed properties: netbeans.checkstyle.format
  * re-enable *relaxed* enforcer rules
  * site
    * removes dependency-updates-report
    * removed test javadocs
    

### 1.0.4 (2018-11-22)

* update compiler plugin 3.6.1 to 3.8.0
* define release to compile against (https://stackoverflow.com/questions/43102787/what-is-the-release-flag-in-the-java-9-compiler)


### 1.0.3 (2018-11-14)

* update foss-parent 1.5.12 to 1.6.0
* reconfigue javadoc plugin to check syntax only


### 1.0.2 (2016-12-05)

* update foss-parent 1.5.10 to 1.5.12


### 1.0.1 (2016-07-08)

* update foss-parent 1.5.9 to 1.5.10

