node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DokerHub') {

        def customImage = docker.build("99664477/dockerwebapp1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
