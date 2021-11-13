properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone") {
        git "https://github.com/ilonalz/DevOps_repo.git"
    }
    stage("show files") {
        bat "dir"
    }
}
