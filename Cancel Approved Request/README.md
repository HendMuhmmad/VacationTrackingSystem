# Cancel Approved Vacation Request 
## Actor: 
- Employee
## Goal: 
- The employee wants to cancel an approved vacation time request.
## Preconditions:
- The employee has a vacation time request that has been approved and is scheduled for some time in the future or the recent past (previous 5 business days). See also main flow preconditions.

## Case flow:
1. The employee navigates to the VTS home page through the intranet portal application, which identifies and authenticates the employee with the privileges necessary for using the VTS.
2. The VTS home page contains a summary of vacation time requests, outstanding balance per category of time, and the current status of all active vacation time requests for the previous 6 months and up to 18 months in the future.
3. The employee selects a vacation time request to cancel, one that is in the future (or recent past) and has been approved.
4. If the request is in the future, the employee is prompted to confirm the cancellation. If the request is in the recent past, the employee is prompted to confirm the cancellation and provide a short explanation. If the employee approves the cancellation and provides the required information, an e-mail notification is sent to the manager, and the state of the request is changed to canceled. The time allowances used to make the request are returned to the employee. The employee can also abort the cancellation, effecting no changes to the current requests.
5. The employee is returned to the main VTS home page. The summaries are updated to reflect any changes made to the employee’s outstanding vacation time requests.

## Flowchart:

<p align="center">
    <img src="/Cancel Approved Request/CancelVacationFlowChart.png">
</p>

## Sequence Diagram:

<p align="center">
    <img src="/Cancel Approved Request/CancelVacationSequenceDiagram.png">
</p>

## State Machine:

<p align="center">
    <img src="/Cancel Approved Request/CancelVacationStateDiagram.png">
</p>