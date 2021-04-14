# Grafana Dashboards

This repository contains sample Dashboards to help you with a quick start. 
They may not cover all or explicit use cases and may be extended in the future. 

![Dashboard Example](/images/readme-dashboard-sample.png)

## Data Sources

Please note that these Dashboards require a specific Data Source configuration. 
For more input, please consult our 
[documentation](https://docs.zammad.org/en/latest/appendix/reporting-tools-thirdparty/grafana.html).

## Dashboards

For better overview we've decided to put each dashboard into its own folder. 
Every folder contains the ``.json`` file needed for importing and a screen shot 
for a better idea what the dashboard is about.

## Compatibility note

Please note that these dashboards work natively with Grafana 7.5. 
Older versions may not support them or need manual adjustments.

The chat session dashboard requires the 
[worldmap plugin](https://grafana.com/grafana/plugins/grafana-worldmap-panel/). 
Install it by using ``grafana-cli plugins install grafana-worldmap-panel`` 
followed by a Grafana restart.

## Extending / Building your own panel

To help you with fiddling, our documentation provides a page with all relevant 
elasticsearch indices and data we're saving. You can find this page here: 
https://docs.zammad.org/en/latest/install/elasticsearch/indexed-attributes.html

## Questions / Something not all right?

If you're unsure on how to configure your Dashboards, please consult our 
community: https://community.zammad.org .
