properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("Clone"){
        git "https://github.com/Liel4494/DevOps1004.git"
    }
    stage("Show Files"){
        sh "ls -l"
    }
}
