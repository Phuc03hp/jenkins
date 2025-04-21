podTemplate(yaml: readTrusted('pod.yaml')) {
  node(POD_LABEL) {
      container('golang') {
        echo POD_CONTAINER // displays 'busybox'
        sh 'go version'
      }
  }
}