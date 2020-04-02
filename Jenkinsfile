pipeline {
agent any
parameters {
string(name: 'user', defaultValue: 'dev', description: 'Branch selected')
}
stages {
stage('Trigger pipeline') {
steps {
echo "Pipeline is running in ${params.branch}"
}
}
}
}
