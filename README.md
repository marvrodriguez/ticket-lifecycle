<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 Pro  (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

| Terms | Descriptions |
| ------| -------------|
| `Assigned` | Tickets that have been assigned to either an Agent or a Team while also being in the Department or Help Topic listed in the column, or tickets that were assigned to the Agent listed in the column, within the timeframe chosen.
|`Working the Issue(s)` | Communicates with the requesting party letting them the status of the ticket(s) and steps that will be taken to reach a potential resolution
| `Resolution` | Ticket was resolved in order to resolve or close the Ticket. This may or may meet the requesting parties desired end result. |

### Lifecycle Stages 

#### Intake: 
When Help Desk Agent/Admin logs in, they can now see the tickets that are available that have been assigned/not assigned with a provided priority. The priority will be set by help desk agent or queue manager working the tickets. The below screen shows the `Ticket #`, `Last Updated`, `Subject`, `From` (user that created the ticket), priority and `Assigned To` (queue manager can assign the ticket, person viewing the ticket can assign it to themselves or it can be assigned to a team ).

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/eefa0ace-858b-48dd-914c-4b81525e2ff3)



### Assignment and Communication 

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/3c335086-ca26-4a84-9e54-6690039ef512)



#### Working the issues:
Working the `Mobile online banking is down` ticket that has a default priority of Normal, we are going to update it to Emergency since this is a business impacting event. Below reflects the selection of changing the priority and updating the notes: 

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/e4dcd352-4c6e-455f-b151-f8943a195ad3)

Updating the priority level from `Normal` to `Emergency`

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/4222e715-2e27-49b6-b3b7-fe1238a5f709)


We can now see that the tickets have been updated from previous screenshot reflects that the tickets is assigned to 'Jane Lee' and the Priority is now 'Emergency'. The ticket also shows that it has been transferred to the System Administrators Department, which was previously under the Support Department.

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/2d4c0188-0430-43ba-9ebd-c14273615516)

How it appears on the Ticket Dashboard.

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/8bebd2d1-b8ff-4e85-a267-6ed05ad26d37)



##### Resoltuion:
After connecting with the Sys Admin tean, we received a response letting us know that the ticket has been resolved and now reflects those comments 

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/0eb7f6d5-ae97-41f5-b414-ad8a2aa150fe)


Now that the ticket has been resolved, it will now be reflected in the 'closed' tickets column since it reached a resolution.

![image](https://github.com/marvrodriguez/ticket-lifecycle/assets/141983161/714638e3-e06b-48d9-a3a3-aa4cd5f76272)
