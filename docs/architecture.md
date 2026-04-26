# System Architecture

## Overview
The HR workflow automation system is designed as a multi-layer enterprise system that handles request intake, approval routing, notifications, and analytics.

## Architecture Layers

### 1. User Interface Layer
- Built using Power Apps
- Handles user input and form submission

### 2. Workflow Logic Layer
- Built using Power Automate
- Controls approval routing and business logic

### 3. Data Layer
- SharePoint for HR-restricted data
- Dataverse for system-wide structured data

### 4. Notification Layer
- Microsoft Teams
- Email notifications

### 5. Analytics Layer
- Power BI dashboards
