# gs-authenticating-ldap
sping boot rest request authenticated vs ldap
https://spring.io/guides/gs/authenticating-ldap/


LDAP servers can use LDIF (LDAP Data Interchange Format) files to exchange user data. The spring.ldap.embedded.ldif property inside application.properties allow to Spring Boot pulls in an LDIF data file. This makes it easy to pre-load demonstration data.

src/main/resources/test-server.ldif

http://localhost:8080
ben/benspassword

