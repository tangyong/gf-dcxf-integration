Integrating-Glassfish-With-OSGi-Remote-Services-implementation
==============================================================

Please see. http://java.net/jira/browse/GLASSFISH-18973

[BackGround] [Reference By https://issues.jboss.org/browse/JBOSGI-322] 
The Enterprise OSGi Spec describes OSGi Remote Services which is a way to Distribute OSGi Services. 
An implementation on top of Web Services and REST is available at the CXF Distributed OSGi project 
(http://cxf.apache.org/distributed-osgi.html).  

Integrating this in the JBoss OSGi distribution would provide it with support for this important OSGi spec. 
[Requirement] In a distributed soa/cloud enviroment, in order to decouple the whole system and use the 
subsystems dynamicly, user can use osgi. However, because subsystems/modules can be distributed across the 
whole system, as a framework of publishing/consuming services, glassfish should have an capability to support 
Distributed OSGi.  

[Integration Example] "Deploying CXF-DOSGi to JBoss AS7" https://community.jboss.org/thread/174136