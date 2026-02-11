# FlashLearn Notification Service

FlashLearn Notification Service manages event driven notifications across the platform.

It processes study reminders, progress milestones, and system alerts.

## Responsibilities

- Send study reminders
- Notify users of milestones
- Trigger inactivity alerts
- Broadcast system updates
- Handle asynchronous events

## Architecture

Built with:

- AWS Lambda
- Amazon SNS
- Amazon EventBridge (optional)
- CloudWatch Logs

Event Flow:

1. Study or progress event triggered
2. Event published to SNS or EventBridge
3. Lambda processes notification
4. Notification delivered (email or in app)

## AWS Always Free Tier Usage

- Lambda executions
- SNS messaging
- EventBridge event routing
- CloudWatch logging

## Design Pattern

- Event driven architecture
- Decoupled microservices
- Asynchronous communication

## Portfolio Value

Demonstrates:

- Event driven microservices
- Cloud native notification systems
- Scalable serverless messaging architecture
