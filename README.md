# SpringBoot-webapp-security-demo-userrepo-configfile
Spring boot webapp security demo by storing user creds in config file

What is it?
------------
Spring boot security project by adding security depedency.
Created the cofig file with the user creds.

Configuration file?
-----------------
Created a configuration class by extending WebSecurityConfigurerAdapter
Added @EnableWebSecurity annotation to the class
Override the configure method
added inmemory authentication user creds.

Added the passwordencoder method and add @Bean annotation to the method.
This encoder is manditory to make the application login work.
