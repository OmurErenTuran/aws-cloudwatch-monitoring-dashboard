## CloudWatch Dashboard
![AWS](https://img.shields.io/badge/AWS-CloudWatch-FF9900?logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon-EC2-F58536?logo=amazonec2&logoColor=white)
![SNS](https://img.shields.io/badge/Amazon-SNS-DD344C?logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/AWS-IAM-232F3E?logo=amazonaws&logoColor=white)
![Monitoring](https://img.shields.io/badge/Monitoring-CloudWatch-blue)

![CloudWatch Dashboard](dashboard.png)

# AWS CloudWatch Monitoring Dashboard

A monitoring dashboard built with Amazon CloudWatch to visualize EC2 performance metrics and generate alerts using Amazon SNS.

## Project Overview

This project demonstrates how to monitor an Amazon EC2 instance using AWS CloudWatch. It includes a real-time dashboard displaying CPU usage, network traffic, and instance health metrics.

## AWS Services Used

* Amazon EC2
* Amazon CloudWatch
* Amazon SNS
* AWS IAM

## Dashboard Metrics

| Metric            | Description                 |
| ----------------- | --------------------------- |
| CPUUtilization    | Monitors EC2 CPU usage.     |
| NetworkIn         | Incoming network traffic.   |
| NetworkOut        | Outgoing network traffic.   |
| StatusCheckFailed | EC2 instance health status. |

## CloudWatch Dashboard

![CloudWatch Dashboard](screenshots/dashboard.png)

## Features

* Real-time EC2 monitoring.
* CloudWatch dashboard with multiple widgets.
* Ready for CloudWatch Alarm integration.
* SNS email notifications (next step).

## Project Structure

```text
aws-cloudwatch-monitoring-dashboard/
├── README.md
├── screenshots/
│   └── dashboard.png
├── architecture/
│   └── architecture-diagram.png
└── docs/
    └── setup-guide.md
```

## Skills Demonstrated

* AWS Monitoring
* CloudWatch Dashboards
* CloudWatch Metrics
* EC2 Monitoring
* AWS Documentation
  ## CloudWatch Alarm Triggered

The alarm changes its state to **ALARM** when EC2 CPU utilization stays above **80%** for two consecutive evaluation periods.

![CloudWatch Alarm Triggered](alarm-triggered.png)


