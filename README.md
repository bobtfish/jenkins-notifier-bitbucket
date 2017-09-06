# jenkins-publisher-bitbucket

Bitbucket publisher and config for jenkins job builder

# Getting started

    - project:
      name: foo
      publishers:
          - bitbucket:
              notify-start: true
              notify-finish: true
              override-latest-build: false
              credentials-id: optional

