@Library('github.com/gaurankgoyal/Jenkins-Shared-Lib') _

mavenBuild {
    environment = 'golang:1.5.0'
    mainScript = '''
go version
go build -v hello-world.go
'''
    postScript = '''
ls -l
./hello-world
'''
}

