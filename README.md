# Repository for Grafana Dashboards used by the STFC Cloud

The yaml file [cloud_dashboards.yaml](cloud_dashboards.yaml) is used by Grafana to know where to pull provisioned dashboards from and set some rules with them.


### Current Dashboards:

- Kiosk - Dashboards that are useful to have on rotation:
    - Openstack L flavor availability: Shows the availablity of all L flavors
    - Openstack GPU pool availability: Shows the availability of the GPU flavors

- Power Metrics:
    - Cloud power metrics: Shows the energy usage across a variety of machines along with cumulative measurements
    - Cloud rack average energy usage: Shows the energy usage across each rack
    - Cloud Energy Overview by Aggregate: Shows the total power of the cloud by aggregate.

- Virtual Machines:
    Two dashboards estimate the power consumption and carbon emissions of Virtual Machines (VMs) over a selected time period, each using a different methodology:
    - Virtual Machine Power & Carbon Emissions Dashboard - Method 1
    - Virtual Machine Power & Carbon Emissions Dashboard - Method 2
    
- Service Status:
    - Harbor Node Exporter: Shows host resource usage

- Slots Available:
    - OpenStack GPU usage: GPU Usage on Production across all GPU flavors
    - Openstack slots available: Shows available flavor capacity for L and GPU flavors

- Weekly Reporting:
    - Weekly Reporting: Cloud weekly reporting statistics

- ChatOps:
    - Docker Monitoring: Shows usage information about containers from cAdvisor. [Grafana Community Made](https://grafana.com/grafana/dashboards/15798-docker-monitoring/)
    - HAProxy: HAProxy traffic information. [Grafana Community Made](https://github.com/rfmoz/grafana-dashboards)
    - Node Exporter: System usage information. [Grafana Community Made](https://github.com/rfmoz/grafana-dashboards)
    - Service Status: Service systemctl status information.
