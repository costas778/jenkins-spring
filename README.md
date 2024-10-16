NOTE: This was written for a system with a Windows agent.
Hence the bat in the jenkinsfile script.
If you wish to deploy to a Linux machine with a Jenkins agents replace bat with sh in pipeline script.

Below  agent any add the below for Maven:
tools { maven 'M3' }
