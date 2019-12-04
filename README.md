# Camunda configuration
- Web app for Camunda

## Dependencies
### Maven
- Install [Apache Maven](https://maven.apache.org/)

### LDAP
- Download [Apache Directory](https://directory.apache.org/apacheds/download/download-archive.html)

### Tomcat
- Download [Apache Tomcat](https://tomcat.apache.org/download-70.cgi)

### MySQL
Connect to `root` user:
```
mysql -u root -p
```

Create `camunda` database:
```
CREATE SCHEMA `camunda` DEFAULT CHARACTER SET utf8 COLLATE utf8_unicode_ci;
```

Create `camunda` user:
```
```

### MySQL Connector
- Download [mysql-connector-java-5.1.47.zip](https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-java-5.1.47.zip)

### Eclipse
- Download [Eclipse for Java EE](https://www.eclipse.org/downloads/packages/release/2019-06/r/eclipse-ide-enterprise-java-developers)

## Code
### Platform
- Clone [Camunda BPM](https://github.com/idega/camunda-bpm-platform) repository
- Checkout `master` branch
- Compile with `mvn clean install -DskipTests`

### Application
- Clone [Camunda application](https://github.com/idega/camunda)
- Checkout `master` branch
- Compile with `mvn clean package install`
