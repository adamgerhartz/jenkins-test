properties([
    parameters([
        string(name: 'NAME', defaultValue: 'Adam', description: 'Name')
    ])
])

node {
    checkout scm
    sh "chmod +x ${WORKSPACE}/shell.sh"
    sh("${WORKSPACE}/shell.sh")
}
