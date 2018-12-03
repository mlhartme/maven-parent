## Changes

### 1.1.0 (pending)

* inline foss-parent with these changes:
  * removed dependency management
  * removed profiles: foss-parent-run-its, foss-parent-enable-invoker-log-output-on-travis, 
    foss-parent-enable-githubreport-when-not-on-travis, foss-parent-spock-tests
  * removed plugins: jacoco, pmd, findbugs, invoker, jgitflow
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

