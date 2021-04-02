# Mule 4 template - cps


### What is included in this template?

- Mule runtime set to 4.3.0
- CIDC pipeline configuration pre configured
- EI Features:
	- EI's Splunk Logging (aka Firehose)
	- CPS
- Global elements aggregated in a single configuration file
- All Error are aggregated in a single configuration file
- Pre-populated application property files
- Updated file and folder structure
- pom.xml updated to use Ei's parent POM
- Sample RAML
- The following global elements are already configured:
	- HTTPS Listener
	- TLS Context
	- API Kit Router
	- Default error handler
- Sample flows:
	- `/ping` for monitoring.
	- `/template` as an example flow.
- Template testing suits included:
	- Bat
	- Karate

For more information and how to use this template please visit the [mule template confluence page](https://confluence.internal.salesforce.com/display/ITEI/The+Mule4+Template)
