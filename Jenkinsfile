pipeline {
agent any
parameters {
string(name: 'branch', defaultValue: 'dev', description: 'Branch selected')
}
stages {
	stage ('Deploy stage') {
when {
branch 'dev'
}
steps {
echo 'Deploy master to stage'

}
}
}
}
