# rjug-2017-11
This repo holds the content from my November 2017 presentation for the Richmond Java Users Group entitled Docker for the Modern Java Developer.

Links to material from the presentation are:

The link below is for base images that you can use to create your own Dockerfiles from. Once you are comfortable building your own images, there are may images on DockerHub that you might find useful.

[OpenJDK images from DockerHub](https://hub.docker.com/_/openjdk/)

These links are for the official Gradle docker image as well as the GitHub repo with the Dockerfile(s) used to create their images. 

[Gradle docker image from DockerHub](https://hub.docker.com/r/_/gradle/)

[GitHub repo for Docker Gradle image](https://github.com/keeganwitt/docker-gradle/tree/bb744a56314f1621f3f4bd596d058f93fd3c1a9b)

This is the official guidance from Docker themselves on how and when to use bind mounts with your Docker images.

[Docker guide to bind mounts](https://docs.docker.com/engine/admin/volumes/bind-mounts/)

Bonus material on using ambassador containers to mediate access.

[Docker guide on ambassador containers](https://docs.docker.com/engine/admin/ambassador_pattern_linking/)

This is an excellent guide to building your own Java based docker image pipeline. This article helped me understand the process and inspired me to create this presentation.

[Docker pipeline guide](https://codefresh.io/blog/java_docker_pipeline/)

If you are going to use your containers effectively, you need to know how much memory they will consume. For local development, this is usually less of a problem but when you are deploying to the cloud, this becomes important.

[Java Memory Usage (Not garbage collection)](http://trustmeiamadeveloper.com/2016/03/18/where-is-my-memory-java/)

This is a tutorial on getting up and running quickly in a clustered configuration and is used as the basis for our cluster examples.

[JHipster Instructions (cluster setup)](https://github.com/dsharpe/rvameetup)

For those new to JHipster, this is it's home and provides many resources to help you get up and running.

[JHipster](http://www.jhipster.tech/)

Chaos. **It _will_ happen**.

[Jepsen (Perils of Network Communications)](https://aphyr.com/posts/281-jepsen-on-the-perils-of-network-partitions)

[Awesome Chaos Engineering](https://github.com/dastergon/awesome-chaos-engineering)

[Chaos Upgraded](https://medium.com/netflix-techblog/chaos-engineering-upgraded-878d341f15fa)

[Principles of Chaos Engineering](http://principlesofchaos.org/)
