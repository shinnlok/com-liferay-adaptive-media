FROM mdelapenya/liferay-portal:7-ce-ga5-tomcat-hsql
MAINTAINER Sergio González <sergio.gonzalez@liferay.com>

COPY *.jar $LIFERAY_HOME/osgi/modules/
COPY supervisord-tomcat.conf /etc/supervisor/conf.d/supervisord-tomcat.conf
COPY portal-ext.properties $LIFERAY_HOME/portal-ext.properties