# Logging, Monitoring and Alerting

The ability to proactively have logs on Security related events presented for triage to the relevant resources is key to the detection and prevention of Cyber Security Incidents. Many organizations utilize Security Information and Event Management (SIEM) platforms to corelate and analyze logs and alerts from relevant assets. 

The following table summarizes the curated list of resource URLs for this domain:
<table>
  <tr>
    <th>Resource Title</th>
    <th>URL</th>
  </tr>
  <tr>
    <td colspan="2" align="center"><h3>Enable Resource Logging</h3></td>
  </tr>
  <tr>
    <td>Enabling Logging for a resource</td>
    <td>https://docs.oracle.com/en-us/iaas/Content/Logging/Task/enabling_logging.htm</td>
  </tr>
  <tr>
    <td>VCN flow logs</td>
    <td>https://blogs.oracle.com/cloud-infrastructure/post/announcing-vcn-flow-logs-general-availability-for-oracle-cloud-infrastructure</td>
  </tr>
  <tr>
    <td>VCN Flow logs concepts</td>
    <td>https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/vcn-flow-logs.htm</td>
  </tr>
  <tr>
    <td>OCI Flow Logs Enhancements</td>
    <td>https://blogs.oracle.com/cloud-infrastructure/post/oci-flow-logs-enhancements-network-monitoring</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><h3>SIEM Integration</h3></td>
  </tr>
  <tr>
    <td>Design Guidance for SIEM Integration</td>
    <td>https://docs.oracle.com/en/solutions/oci-aggregate-logs-siem/index.html</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Splunk SIEM Integration</strong></td>
  </tr>
  <tr>
    <td>Splunk Addon for OCI - Setup documentation on Git Hub</td>
    <td>https://github.com/splunk/Splunk-Addon-for-OCI/tree/main/README</td>
  </tr>
  <tr>
    <td>Splunk Addon for OCI - (direct link to the Addon)</td>
    <td>https://splunkbase.splunk.com/app/5222</td>
  </tr>
  <tr>
    <td>App for Dashboards in Splunk(To visualize data coming from Oracle Cloud Infrastructure (OCI))</td>
    <td>https://splunkbase.splunk.com/app/5289</td>
  </tr>
  <tr>
    <td>Implement a SIEM system in Splunk using logs streamed from Oracle Cloud(Example Terraform code)</td>
    <td>https://docs.oracle.com/en/solutions/logs-stream-splunk</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Azure Sentinel Integration</strong></td>
  </tr>
  <tr>
    <td>Azure Market place sentinel solution</td>
    <td>https://azuremarketplace.microsoft.com/en-us/marketplace/apps/azuresentinel.azure-sentinel-solution-ocilogs</td>
  </tr>
  <tr>
    <td>OCI(using Azure Functions) connector</td>
    <td>https://learn.microsoft.com/en-us/azure/sentinel/data-connectors/oracle-cloud-infrastructure-using-azure-functions</td>
  </tr>
  <tr>
    <td>Step by step guide for recieving logs from OCI by using the Microsoft Azure Sentinel OCI connector(Azure Functions)</td>
    <td>https://docs.oracle.com/en/learn/stream-oci-logs-to-azure-sentinel/index.html</td>
  </tr>
  <tr>
    <td>Step by step guide for sending logs to Microsoft Azure Sentinel using OCI Functions</td>
    <td>https://docs.oracle.com/en/learn/oci-logs-ms-azure-sentinel/index.html</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Qradar Integration</strong></td>
  </tr>
  <tr>
    <td>Move Logs from Oracle Cloud Infrastructure to IBM QRadar</td>
    <td>https://docs.oracle.com/en/learn/move-ocilogs-to-ibmqradar/</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Cribl Integration</strong></td>
  </tr>
  <tr>
    <td>Integrate OCI Logging with Cribl using OCI Streaming</td>
    <td>https://blogs.oracle.com/cloud-infrastructure/post/integrate-oci-logging-cribl-oci-streaming</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Rapid7 Integration</strong></td>
  </tr>
  <tr>
    <td>Rapid7 InsightIDR Integration</td>
    <td>https://blogs.oracle.com/cloud-infrastructure/post/ingest-oci-service-logs-to-rapid7-insightidr</td>
  </tr>
  <tr>
    <td>Forward Logs from Oracle Cloud Infrastructure to Rapid7 InsightOps</td>
    <td>https://docs.oracle.com/en/learn/forward-log-from-oci-to-insightops/index.html</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Logstash Integration</strong></td>
  </tr>
  <tr>
    <td>Logstash Integration</td>
    <td>https://docs.oracle.com/en/learn/oci-logs-streaming-kafka-logstash/index.html</td>
  </tr>
   <tr>
    <td colspan="2" align="center"><strong>Datadog Integration</strong></td>
  </tr>
  <tr>
    <td>Datadog Integration(using OCI Functions)</td>
    <td>https://docs.datadoghq.com/integrations/oracle_cloud_infrastructure</td>
  </tr>
   <tr>
    <td>Datadog Integration(using OCI Functions)</td>
    <td>https://docs.oracle.com/en/learn/logs_oci_datadog/index.html</td>
  </tr>
  <tr>
    <td>Datadog Observability Pipelines(Generic Integration pattern)</td>
    <td>https://docs.datadoghq.com/observability_pipelines 
    (Use OCI Streams as source of type 'kafka' and 'datadog logs' as destination)</td>
  </tr>
 <tr>
    <td colspan="2" align="center"><strong>Sumologic Integration</strong></td>
  </tr>
  <tr>
    <td>Sumologic Integration</td>
    <td>https://docs.oracle.com/en/learn/blog_sumologic/index.html</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>OCI Logging Analytics</strong></td>
  </tr>
  <tr>
    <td>Oracle Cloud Infrastructure Security Fundamentals Dashboards using OCI Logging Analytics</td>
    <td>https://www.ateam-oracle.com/post/security-fundamentals-dashboards-using-logging-analytics</td>
  </tr>
  <tr>
    <td>OCI Security Fundamentals Dashboards - Manage Logging Analytics Storage</td>
    <td>https://www.ateam-oracle.com/post/oci-security-fundamentals-dashboards-manage-logging-analytics-storage</td>
  </tr>
  <tr>
    <td>OCI Logging Analytics Best Practices Series - Management Agent Tuning</td>
    <td>https://www.ateam-oracle.com/post/oci-logging-analytics-best-practices-management-agent-tuning</td>
  </tr>
  <tr>
    <td>OCI Logging Analytics Best Practices Series - Cost Optimization</td>
    <td>https://www.ateam-oracle.com/post/oci-logging-analytics-best-practices-series-cost-optimization</td>
  </tr>
  <tr>
    <td>OCI Logging Analytics Best Practices Series - Custom Log Sources and Parsers Tips</td>
    <td>https://www.ateam-oracle.com/post/oci-logging-analytics-best-practices-log-parsing-and-enrichment</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><h3>Notifications,Monitoring & Alerting</h3></td>
  </tr>
  <tr>
    <td>Notification Overview</td>
    <td> https://docs.oracle.com/en-us/iaas/Content/Notification/Concepts/notificationoverview.htm</td>
  </tr>
   <tr>
    <td>Notifications for Network changes</td>
    <td>https://www.ateam-oracle.com/post/oci-observability-and-management-for-networking---part-two---notifications-for-network-changes</td>
  </tr>
   <tr>
    <td>OCI basic monitor/alarms setup for FastConnect and VPN using native services</td>
    <td>https://www.ateam-oracle.com/post/oci-basic-monitoralarms-setup-for-fc-and-vpn-using-native-services</td>
  </tr>
   <tr>
    <td>Notifications for Network Outages</td>
    <td>https://www.ateam-oracle.com/post/oci-observability-and-management-for-networking---part-three---notifications-for-network-outages</td>
  </tr>
</table>
