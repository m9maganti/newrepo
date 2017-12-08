//task 5
#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/m9maganti/newrepo.git/'],
    pipelineTriggers([githubPush()])])
node {
  stage 'build'
  echo 'build now'
  stage 'test'
  echo 'do now'
  stage 'deploy'
  echo 'avengers'
}
