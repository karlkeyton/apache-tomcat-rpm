apache-tomcat-rpm
=================

Just a simple apache-tomcat 7 rpm spec/build process.  Originally obtained
from http://meinit.nl/apache-tomcat-7-spec-file-rpm

Run the build

This fork is slightly modified to disable dbcp as it fails to build under java7.
dbcp is not needed anyway - jdbc is a much saner choice anyway.
