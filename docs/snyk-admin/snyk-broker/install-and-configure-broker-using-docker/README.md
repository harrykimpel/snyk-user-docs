# Install and configure Broker using Docker

{% hint style="warning" %}
**Multi-tenant settings for EU and AU**\
When you set up Broker, Code Agent, or both for use in EU or AU Multi-tenant environments, additional environment variables with the specific URLs are required.\
Example: `-e BROKER_SERVER_URL=https://broker.eu.snyk.io`\
For the URLs, see [EU and AU account datacenter creation](https://docs.snyk.io/snyk-processes/data-residency-at-snyk#eu-and-au-datacenter-account-creation).
{% endhint %}

Installing the Snyk Broker through Docker commands is straightforward. Follow the instructions for the different integrations:

* [GitHub](../snyk-broker-set-up-examples/broker-example-set-up-snyk-broker-with-github.md)
* [GitHub Enterprise](../snyk-broker-set-up-examples/setup-broker-with-github-enterprise.md)
* [Bitbucket Server/Data Centre](../snyk-broker-set-up-examples/data-center.md)
* [Gitlab](../snyk-broker-set-up-examples/setup-broker-with-gitlab.md)
* [Azure Repos](../snyk-broker-set-up-examples/setup-broker-with-azure-repos.md)
* [JFrog Artifactory](https://github.com/snyk/broker#artifactory)
* [Nexus](https://github.com/snyk/broker#nexus-3)
* [Jira](../snyk-broker-set-up-examples/setup-broker-with-jira.md)
* [Snyk Broker - Container Registry Agent](../snyk-broker-container-registry-agent/) (needed to connect to Container Registries)
* [Snyk Broker - Code Agent](../snyk-broker-code-agent/) (needed to enable SAST analysis)

{% hint style="info" %}
You can customize the configuration using the environment variables in the Docker images. For this reason, install separate, multiple instances of the Broker Client for different integration types to ensure proper configuration as well as redundancy.
{% endhint %}

Once the Broker is running, visit the settings for your brokered integration in [the Snyk Web UI](https://app.snyk.io) to see a message like the following and start importing projects:

<figure><img src="../../../.gitbook/assets/image (60) (2).png" alt="Brokered integration settings showing connected status"><figcaption><p>Brokered integration settings showing connected status</p></figcaption></figure>
