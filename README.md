# The Config Server Component  

This component is based on the spring cloud configuration server.  
This project contains for now the central infrastructure components  

* RabbitMQ  
* MongoDB  

which are used within the service mesh of the application.  
This may change in the future.

This module contains a first experimental implementation of docker image creation via
the [jib project][GoogleContainerTools JIB].  

## Implementation  

To provide the configuration data for the config server during development this data
is setup absolutely. You can find the reference in the docker-compose file `docker/env/local.yml`.

```
    volumes:
      - ${HOME}/git/lsb2/lsb2-config-data:/gitrepo
```

So adjust this to your local environment.

## Settings  

To setup access to the dockerhub repository you can provide your credentials under `$HOME/.gradle/gradle.properties`

```
#
# docker details
dockerRegistryUsername=<userid>
dockerRegistryMail=<user email>
dockerRegistryPassword=<user password>
dockerRegistryUrl=<user registry url>
```

## References  

[GoogleContainerTools JIB]:(https://github.com/GoogleContainerTools/jib)
[Docker Images sicher bauen mit Google Jib & Kaniko]:(https://blog.codecentric.de/2018/07/docker-images-google-jib-kaniko/)