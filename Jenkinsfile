node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("Srirammk18/pywebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
