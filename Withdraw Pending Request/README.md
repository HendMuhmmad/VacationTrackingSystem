# Withdraw Pending Request 
## Actor: 
- Employee
## Goal: 
- The employee wants to withdraw an outstanding request for vacation time.
## Preconditions:
- An employee has made a vacation time request, and that request has yet to be approved or denied by an authorized manager. See also main flow preconditions.
## Case Flow:
1. The employee navigates to the VTS home page through the intranet portal application, which identifies and authenticates the employee with the privileges necessary for using the VTS.
2. The VTS home page contains a summary of vacation time requests, outstanding balances per category of time, and the current status of all active vacation time requests for the previous 6 months and up to 18 months in the future.
3. The employee selects a vacation time request to withdraw, one that is currently pending approval.
4. The VTS prompts the employee to confirm the request to withdraw the previously submitted vacation time request.
5. The employee confirms the desire to withdraw, and the request is removed from the manager’s list of pending approvals.
6. The system sends a notification e-mail to the manager.
7. The system updates the request state to withdrawn.

## Flowchart:

<p align="center">
    <img src="/Withdraw Pending Request/WithdrawRequestFlowChart.png">
</p>

## Sequence Diagram:

<p align="center">
    <img src="/Withdraw Pending Request/WithdrawRequestSequenceDiagram.png">
</p>

## State Machine:

<p align="center">
    <img src="/Withdraw Pending Request/WithdrawRequestStateDiagram.png">
</p>
