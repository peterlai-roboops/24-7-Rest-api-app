FROM openjdk:8
# Adapted from williamyeh/scala

COPY restApi.jar /home/restApi.jar

# print versions
RUN java -version

# Define default command.
CMD ["java", "-jar", "/home/restApi.jar"]