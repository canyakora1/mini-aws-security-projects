## AWS CLOUDWATCH ##

# Brief Overview: #

**To start using AWS CloudWatch, you'll need to follow these general steps:**

    Create or access an AWS account: You'll need an AWS account to access CloudWatch and other AWS services.

    Configure monitoring: Enable monitoring on AWS resources you want to monitor, such as EC2 instances or RDS databases. By default, many AWS services publish metrics to CloudWatch automatically.

    Create and customize dashboards: Create dashboards to visualize and track specific metrics that are important to you. Add widgets to display graphs, numbers, or logs.

    Set up alarms: Define alarms for your metrics to monitor thresholds and trigger notifications or automated actions when breaches occur.

    Explore logs and insights: Configure log groups and log streams to collect and analyze logs from your applications and systems. Utilize CloudWatch Logs Insights to query and gain insights from your log data.

    Integrate with other AWS services: CloudWatch integrates with various AWS services, such as Lambda, SNS, and Step Functions, to enable automated responses to events or metrics.

    It's important to refer to the official AWS CloudWatch documentation for detailed information on specific features, API references, and best practices. The documentation provides step-by-step guides and examples to help you get started with CloudWatch effectively.

**Note that AWS services and features evolve over time, so always ensure you stay updated with the latest AWS announcements and documentation.**

## Project Descriptions ##
We will be working on two real life scenerios that involves the utilization of AWS CloudWatch.

## Project One: ##
As a security engineer, the CISO has asked you to implement a real-time logging solution hosted in AWS for servers both on-premise and in AWS:

**Other requirements includes:**
    Configure retention periods
    Customization of logs collected
    it should work for both Windows and Linux
    it must trigger alertss for the SecOps team.

## Project Two ##
As a security enginner, you were tasked with configuring a monitoring solution on AWS that would monitor a web application running on AWS Beanstalk that consists of multipy EC2 Instances behind a load balancer. You want to monitor the CPU utilization of the instances and receive an alert when it exceeds a certain threshold.

**Other requirements included:**
    it must trigger an alarm, when CPU utilization exceeds 80 %
    it should also trigger an action, like sending notifications or trigging a lambda function.

