cf-jhipster-war
===============
This is war file for Jhipster based on Outh configuration.

===============
To Deploy PWS/PCF:

Manifest uses mysql instance with called pwsjhipster. You can create with below command or create your own mysql instance and change manifest file.

cf create-service p-mysql 100mb-dev pwsjhipster


cf push



