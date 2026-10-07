# Maven parent

is a general purpose parent pom for Maven projects. Technically, it is a simplified https://github.com/1and1/foss-parent.

## Publishing to Sonatype central

* General documentation can be found at https://central.sonatype.org/pages/ossrh-eol/#process-to-migrate
* log in at https://central.sonatype.com
  * in "view user tokens": create a fresh on

* adjust your ~/.m2/settings.xml
  * add a property "gpg.passphrase" with your passphrase
  * add your fesh user token, it should look something like 

        <server>
          <id>sonatype-central</id>
          <username>someUsername</username>
          <password>somePassword</password>
        </server>

* deploy snapshot:

      mvn clean deploy -Psonatype-publish

* release:

      mvn release:prepare
      mvn release:perform

* publish: 
  * manually publish at https://central.sonatype.com/publishing/deployments
  * can take an hours to complete

* auth problems with github:
  * also login interactively
  * try https, not git protocol
