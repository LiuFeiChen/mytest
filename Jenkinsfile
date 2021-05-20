pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''#yum -y install pcre-devel openssl openssl-devel
chmod +x configure && ./configure && make
echo "hello word"'''
      }
    }

  }
}
