# openldap
- Pull to local by git clone
- Cd to the project dir
- Run: docker-compose up
- Run to check ldap DIT: docker exec openldap ldapsearch -x -H ldap://localhost -b dc=example,dc=org -D "cn=admin,dc=example,dc=org" -w admin
