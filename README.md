# Hibernate-JNDI
1.4 What is JNDI?
JNDI stands for Java Naming and Directory Interface.
It’s a Java API for a directory service that allows Java clients to discover and look up data and objects via a name.
It’s just an interface and hence it is independent of the underlying implementation.
In simple words, JNDI provides a mechanism to bind an object to a name.
1.5 Why we need to use JNDI?
JNDI allows distributed applications to look up services in a resource-independent way.
Since it is independent of any specific naming or directory service implementation, it enables applications to access different naming and directory services like DNS, LDAP, CORBA and RMI using a common API.
1.6 When to use JNDI?
The most common use case is to set up a database connection pool on a Java EE application server.
Any application that is deployed on such server (where JNDI is configured) can gain access to the connections they need using the JNDI name without having any knowledge about the connection and the underlying database.
