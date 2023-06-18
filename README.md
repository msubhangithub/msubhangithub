trigger:
- main

pool:
  vmImage: 'ubuntu-latest'

steps:
- script: echo Hello, world!
  displayName: 'Run a one-line script'
- script: |
    echo Add other actions to build,
    echo test, and deploy your project.
    echo See https://aka.ms/yaml
  displayName: 'Run a multi-line script'
