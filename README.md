# Open JDK - Docker

This repo will contain docker images with openjdk. Having a own docker file definition with standard for Java can help in many scenarios:
- Speed up the development process.
- Keep consistency. 
- Provides a secure baseline.

## Usage

Images can be found on [https://hub.docker.com/r/elviejokike/openjdk/](https://hub.docker.com/r/elviejokike/openjdk/).

For instance: 

```
docker run elviejokike/openjdk:11-jdk-slim java -version
```

