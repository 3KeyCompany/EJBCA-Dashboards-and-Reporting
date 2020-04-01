This is the repository for configuring EJBCA to have reporting and dashboards in ELK stack.
Kibana is used to see the dashboard and different visualizations.

It contains the general approach how to connect EJBCA and start using the analytics.
As an extension, you can find here monitoring and alerting of certificates before expiration.

## EJBCA
Include the following:
- `/Elasticseach Template/ejbca-template.json`
- `/Kibana Visualizations/visualizations-dashboard.ndjson`
- `/Logstash Pipeline/ejbca-pipeline.conf`
- `/Wildfly Syslog Configuration/jboss-cli.commands`

## Certificate alerting extension
Include the following:
- `/Kibana Visualizations/certificate-visualizations-dashboard.ndjson`
- `/Logstash Pipeline/ejbca-pipeline-extended.conf`
- `/Watcher/certificate-expiration-watcher.json`