# Day One reference configuration for Panorama and Panos devices.

The Palo Alto Networks NGFW provides a wealth of features and capabilities well beyond what is provided in a legacy or single function firewall. Although highly beneficial from a security posture and operations perspective, the learning curve for the various features can be higher than a single function device.

Best practice recommendations for configuration can be found online for Internet Gateway, Datacenter, Wildfire, L4-L7 evasions and other use cases.

[Best Practice Recommendations](https://www.paloaltonetworks.com/documentation/best-practices)

While useful as suggestions and recommendations, the user is still required to manually use the GUI or CLI to configuration each recommendation.

The goal of iron-skillet is to create a template model for the most common, user agnostic elements. These templates can be easily loaded into a firewall or Panorama minimizing time to configure and user error. The repo stores the raw xml for each configuration element along with a full configuration file.

Loading the configuration snippets can be done in multiple ways using the xml format. See the repo wiki for more information.
[Iron Skillet Github Wiki](https://github.com/PaloAltoNetworks/iron-skillet/wiki "Iron Skillet Wiki")
