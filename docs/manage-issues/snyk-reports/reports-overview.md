# Reports overview

The **Reports** area offers data and analytics about Projects, issues, dependencies, and licenses. Report information appears based on the Organization in which you are working, and you can filter this data with different parameters.

Additionally, if your account is managed with Groups, aggregated data for all of your organizations is displayed when you navigate to **Reports** from the **Group** level.

From the **Group** level, you can filter to view data for multiple Organizations, similar to this example:

<figure><img src="../../.gitbook/assets/mceclip0-28-.png" alt="Group-level reporting"><figcaption><p>Group-level reporting</p></figcaption></figure>

You can also use the **Organization Filters** to save and store pre-filtered reports for selected groups of organizations. For more information about this, see our [Snyk groups overview](../../snyk-admin/manage-groups-and-organizations/snyk-groups-overview.md).

Additionally, at the Organization level see [General actions](general-actions.md) to filter for:

* project names
* project types
* vulnerability severity
* a specific period of time

### Reports tabs

The Reports area comprises these tabs:

* [Summary](summary-tab.md)—the main dashboard displays a birds-eye view of all of your issues (vulnerabilities and licenses), across all of your projects.
* [Issues](issues-tab.md)—all issues (vulnerabilities and licenses) across all of your projects, including their severity, any available fixes, and more.
* [Dependencies](dependencies-tab.md)—the package dependencies in your project and their health status.
* [Licenses](licenses-tab.md)—the licenses in all of your projects and their status.

Report data can also be generated and retrieved with our APIs. For more information about this, see our [API documentation](https://snyk.docs.apiary.io/#introduction).

{% hint style="warning" %}
There may be a delay from the time a project is tested and until that data appears in the Reports area. If you find that there is more than a 9-hour delay, [contact our Support team](https://support.snyk.io/hc/en-us/requests/new).
{% endhint %}

{% hint style="danger" %}
Read-only and deactivated Projects and results do not appear in the Reports area.
{% endhint %}
