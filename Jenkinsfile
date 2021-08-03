node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub') {

        def customImage = docker.build("abhilashnarayan/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
