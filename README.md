# Maven parent

is a general purpose parent pom for Maven projects. Technically, it is a simplified https://github.com/1and1/foss-parent.

## Publishing to Sonatype central

* General documentation can be found at https://central.sonatype.org/pages/ossrh-eol/#process-to-migrate
* log in at https://central.sonatype.com
* adjust your settings
  * add a property "gpg.passphrase" with your passphrase
  * add your "user token" that should look something like <server>
    <id>sonatype-central</id>
    <username>someUsername</username>
    <password>somePassword</password>
    </server>
