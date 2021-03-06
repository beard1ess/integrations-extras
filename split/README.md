# Split

## Overview

[Split](http://www.split.io) is a platform for [controlled rollouts](http://www.split.io/articles/controlled-rollout), helping businesses of all sizes deliver exceptional user experiences and mitigate risk by providing an easy, secure way to target features to customers.

Integrate Split with Datadog to:

 * See feature changes in context by including Split changelogs in your event stream
 * Correlate feature impact with application performance
 * Avoid critical issues before they happen. Disable features proactively based on Datadog metrics and alerts

## Setup

**In Datadog**

 * Create an API Key <span class="hidden-api-key">${api_key}</span>

**In Split**

 * Go to **Admin Settings** and click **Integrations** and navigate to the Marketplace. Click Add next to Datadog.<br/>

![Split Screenshot](https://raw.githubusercontent.com/DataDog/integrations-extras/ilan/split-integration/split/images/in-split.png)

 * Paste your Datadog API Key and click Save.

![Split Screenshot](https://raw.githubusercontent.com/DataDog/integrations-extras/ilan/split-integration/split/images/integrations-datadog.png)

Split data should now be flowing into Datadog.

## Data Collected
### Metrics

The Split check does not include any metrics at this time.

### Events
Push your Split listing/de-listing events into your [Datadog Event Stream](https://docs.datadoghq.com/graphing/event_stream/).

### Service Checks
The Split check does not include any service checks at this time.

## Troubleshooting
Need help? Contact [Datadog Support](http://docs.datadoghq.com/help/).

## Further Reading

Learn more about infrastructure monitoring and all our integrations on [our blog](https://www.datadoghq.com/blog/).


[1]: http://www.split.io
[2]: http://www.split.io/articles/controlled-rollout
[3]: https://raw.githubusercontent.com/DataDog/integrations-extras/ilan/split-integration/split/images/in-split.png
[4]: https://raw.githubusercontent.com/DataDog/integrations-extras/ilan/split-integration/split/images/integrations-datadog.png
[5]: https://docs.datadoghq.com/graphing/event_stream/
[6]: http://docs.datadoghq.com/help/
[7]: https://www.datadoghq.com/blog/
