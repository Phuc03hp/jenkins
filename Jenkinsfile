podTemplate(yaml: readTrusted('pod.yaml')) {
  node(POD_LABEL) {
      container('busybox') {
        echo POD_CONTAINER // displays 'busybox'
        sh 'hostname'
      }
  }
}