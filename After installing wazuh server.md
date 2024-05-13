# Post-Installation Steps for Wazuh Server

Congratulations on successfully installing the Wazuh server! Now that you have the server up and running, there are a few additional steps you should take to configure and optimize your Wazuh environment.

## Step 1: Configure Agents

The next step is to configure Wazuh agents to communicate with the Wazuh server. Follow these steps to configure agents:

1. Install the Wazuh agent on each endpoint you want to monitor.
2. Edit the agent configuration file (`/var/ossec/etc/ossec.conf`) and specify the IP address or hostname of the Wazuh server.
3. Restart the Wazuh agent service to apply the changes.

## Step 2: Enable Rules

Wazuh comes with a set of predefined rules for detecting security threats. However, you may need to customize these rules or enable additional ones based on your organization's security requirements. Follow these steps to enable rules:

1. Review the available rules in the Wazuh rule directories (`/var/ossec/rules/`).
2. Edit the rules configuration file (`/var/ossec/etc/ossec.conf`) to enable or disable specific rules.
3. Reload the Wazuh server configuration to apply the changes.

## Step 3: Set Up Email Notifications

Configure Wazuh to send email notifications for important security events. Follow these steps to set up email notifications:

1. Edit the email notification configuration file (`/var/ossec/etc/ossec.conf`) to specify the SMTP server details and recipient email addresses.
2. Test the email notification functionality by triggering a test alert and verifying that you receive the notification.

## Step 4: Configure Log Collection

Wazuh can collect and analyze logs from various sources, including system logs, application logs, and network logs. Follow these steps to configure log collection:

1. Identify the logs you want to collect and analyze.
2. Configure log collection agents to monitor the specified log files or directories.
3. Customize log parsing rules as needed to extract relevant information from the logs.

## Step 5: Set Up Dashboards and Visualizations

Explore the Wazuh dashboard to view security alerts, visualize log data, and monitor the overall security posture of your environment. Follow these steps to set up dashboards and visualizations:

1. Access the Wazuh dashboard using a web browser.
2. Navigate to the dashboards section and explore the available dashboards and visualizations.
3. Customize dashboards and visualizations to meet your specific monitoring and reporting needs.

## Conclusion

By following these post-installation steps, you can configure and optimize your Wazuh server to effectively monitor and protect your environment against security threats. For more detailed information and advanced configuration options, refer to the official [documentation](https://documentation.wazuh.com/current/index.html).

---

*Note: This guide provides a basic overview of post-installation steps for the Wazuh server and may need to be adapted based on your specific environment and requirements.*
