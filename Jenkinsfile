properties([parameters([string(defaultValue: 'liav', description: 'what is your name?', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git "https://github.com/LiavN/GitJenkins.git"
    }
    stage("bla"){
        sh "ls -l"
    }
}