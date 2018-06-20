### Changes to be made in order to allow parallel executions

- **Jenkinsfile** environment block ```MOLECULE_EPHEMERAL_DIRECTORY = "${WORKSPACE}/.molecule"```
- **molecule.yml** in every reference to instance hostname ```${BUILD_TAG-molecule_instance_manual}```
