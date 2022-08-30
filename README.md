node-sonar-scanner
==================

Forked to use sonar-scanner-cli-4.7.0.2747

Wrap [SonarQube Scanner](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner) as a node module.

# Installation

You can install node-sonar-scanner as a development dependency and add it as a script property in your package.json.

```shell
npm i sonar-scanner --save-dev
```     

```json
{
  "scripts": {
    "sonar-scanner": "node_modules/sonar-scanner/bin/sonar-scanner"
  }
}
```

```shell
npm run sonar-scanner
```     
