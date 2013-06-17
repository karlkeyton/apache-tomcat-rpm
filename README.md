apache-tomcat-rpm
=================

Just a simple apache-tomcat 7 rpm spec/build process.  Originally obtained
from http://meinit.nl/apache-tomcat-7-spec-file-rpm

Run the build

This fork is slightly modified to disable dbcp as it fails to build under java7.
dbcp is not needed anyway - jdbc is a much saner choice anyway.

Example result after a successful build:

RPMS
├── noarch
│   ├── apache-tomcat-docs-7.0.41-1.noarch.rpm
│   ├── apache-tomcat-examples-7.0.41-1.noarch.rpm
│   ├── apache-tomcat-host-manager-7.0.41-1.noarch.rpm
│   ├── apache-tomcat-manager-7.0.41-1.noarch.rpm
│   └── apache-tomcat-ROOT-7.0.41-1.noarch.rpm
└── x86_64
    └── apache-tomcat-7.0.41-1.x86_64.rpm

