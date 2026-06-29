# Task 2 - Cloud Monitoring and Alerts

## Objective
Set up monitoring for a cloud-based application using AWS CloudWatch and configure alerts with a dashboard showcasing metrics.

## Platform Used
AWS CloudWatch with Amazon EC2

## Steps Performed
1. Created/used an EC2 instance to monitor.
2. Opened AWS CloudWatch.
3. Created a dashboard named `InternshipMonitoringDashboard`.
4. Added the following widgets:
   - CPU Utilization
   - Network In
   - Network Out
   - Status Check Failed
5. Configured a CloudWatch alarm for high CPU utilization.
6. Set threshold to trigger alert when CPU usage goes above 70%.
7. Linked the alert to an SNS notification topic or configured the alarm state.

## Deliverable
- Configured CloudWatch dashboard
- Configured CPU utilization alert

## Outcome
Successfully implemented cloud monitoring and alerting for a cloud-based resource.
