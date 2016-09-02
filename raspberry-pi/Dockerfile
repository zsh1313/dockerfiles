# Pull base image
FROM hypriot/rpi-java:1.7.0-jre
MAINTAINER Shuaijun(Jason) Zhang <szhang@research.ait.ie>

# Install dependencies
#RUN apt-get update && apt-get install -y \
#    vim \
#    --no-install-recommends && \
#    rm -rf /var/lib/apt/lists/*

# Copy IoTSys Gateway server
COPY felix-framework-4.2.1 /data/felix-framework-4.2.1/

# Define default command
CMD cd /data/felix-framework-4.2.1 && java -jar bin/felix.jar