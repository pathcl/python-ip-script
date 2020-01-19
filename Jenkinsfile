def gitUrl = 'https://github.com/pathcl/python-ip-script'

job('test-job') {
    scm {
        git(gitUrl)
    }
    steps {
        shell('python main.py')
    }
}
