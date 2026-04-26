# Workflow Logic

## Workflow Steps

1. Employee submits leave request
2. System validates inputs
3. Request is routed to:
   - HR
   - Lead
   - Manager
4. Each approver reviews and approves/rejects
5. Notifications sent after each step
6. Final decision stored in system

## Decision Model

- All requests must go through approval chain
- No auto-approval conditions
- HR manually handles edge cases (e.g., employee no-show)

## Notification Flow

- Teams notification sent on submission
- Email alerts sent at each approval stage
