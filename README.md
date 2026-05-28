#  AWS CloudWatch Monitoring

EC2 instance monitoring with CloudWatch alarms and SNS email notifications.

##  Tech Stack
- **Monitoring:** AWS CloudWatch
- **Alerts:** AWS SNS
- **Infrastructure:** AWS EC2

##  Features
- CPU utilization monitoring
- Automatic alerts when CPU > 80%
- Email notifications via SNS
- Real-time EC2 health monitoring

##  Architecture
```
EC2 Instance
      ↓
CloudWatch Metrics
      ↓
Alarm (CPU > 80%)
      ↓
SNS Topic
      ↓
Email Notification! 
```

##  Steps Followed
1. Created SNS topic
2. Added email subscription
3. Created CloudWatch alarm
4. Set CPU threshold > 80%
5. Connected SNS for notifications
