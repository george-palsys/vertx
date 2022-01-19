FROM registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift:latest
ENV JAVA_APP_DIR=/deployments JAVA_OPTIONS="-Dvertx.cacheDirBase=/tmp -Dvertx.disableDnsResolver=true"
LABEL org.label-schema.description="Example application using Vert.x" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-01-19T03:39:01.970 org.label-schema.name="My Application"
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
