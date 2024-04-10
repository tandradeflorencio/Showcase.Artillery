# Showcase.Artillery
A showcase project with load tests against a Web API using Artillery framework

- Requires [Node JS](https://nodejs.org/en) latest versions
- Some Commands:

````
--Run the tests and generates a report in JSON format. Only use the 'insecure' parameter only in local requests.

artillery run --insecure --output .\test-run-post-report.json .\postTest.yaml

--Generates a report in HTML format

artillery report .\test-run-post-report.json
