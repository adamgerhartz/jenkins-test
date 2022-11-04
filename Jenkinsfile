properties([
    parameters([
        string(name: 'NAME', defaultValue: 'Adam', description: 'Name')
    ])
])

node {
    checkout scm
    sh("${WORKSPACE}/shell.sh")
}
