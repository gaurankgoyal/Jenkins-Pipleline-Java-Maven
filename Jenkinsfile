@Library('github.com/gaurankgoyal/Jenkins-Shared-Lib') _
properties([parameters([string(name: 'goVersion', defaultValue: '1.5.0', description: 'Which version of Go language to use.')])])
mavenBuild environment: "golang:${params.goVersion}",
    mainScript: '''
go version
go build -v hello-world.go
''',
    postScript: '''
ls -l
./hello-world
'''
