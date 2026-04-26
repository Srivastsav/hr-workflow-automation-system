# Enterprise HR Workflow Automation System

## System Overview
This project represents an enterprise HR leave management system designed to automate employee leave requests, approval workflows, notifications, and analytics.

## System Model
Input → Process → Output

## Inputs
- Employee Name (auto-filled)
- Employee ID (auto-filled)
- Email (auto-filled)
- Leave Type (dropdown)
- Leave Dates
- Description
- Manager Email
- Lead Email

## Process
1. Employee submits leave request
2. Request is routed to HR, Lead, and Manager
3. Approval workflow is triggered
4. Notifications sent via Teams and Email
5. Data stored in SharePoint (HR restricted) and Dataverse
6. HR handles exceptional cases manually

## Outputs
- Approved / Rejected leave request
- Approval history
- Stored leave records
- Analytics-ready data

## Architecture
- UI Layer: Power Apps
- Workflow Engine: Power Automate
- Data Layer: SharePoint + Dataverse
- Notification Layer: Teams + Email
- Analytics Layer: Power BI

## Business Impact
- Reduced manual coordination
- Improved approval visibility
- Enabled leave trend analysis
- Correlated leave patterns with performance metrics

## Skills Demonstrated
- Workflow automation
- System design thinking
- Enterprise process modeling
- Approval systems

## Project Structure

- /docs → System architecture and workflow design
- /diagrams → System flow representation
- Data structuring
- Analytics integration
