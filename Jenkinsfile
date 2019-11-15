@Library('github.com/gaurankgoyal/Jenkins-Shared-Lib') _

mavenBuild {
    environment = 'maven:3-alpine'
    mainScript = '''
mvn -B -DskipTests clean package
'''
    postScript = '''
echo "mvn test"
'''
}

