def label = "mypod-${UUID.randomUUID().toString()}"
podTemplate(label: label) {
    node(label) {
        stage('Run shell') {
            sh 'echo hello world from podTemplate'
            sh 'kubectl get pods'
        }
    }
}