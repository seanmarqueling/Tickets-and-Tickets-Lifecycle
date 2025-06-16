# Tickets-and-Tickets-Lifecycle
The lifecycle of a ticket and how to use the ticketing system

In this lab I will show how to create tickets in osTicket as an end user and then how to resolve them as a member of the Help Desk.

## Instructions - Create help tickets and resolve the tickets

The first thing we are going to do is open up the End User home page for ticketing. [End User Ticketing](https://localhost/osTIcket/)
- Click on Open a New Ticket

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture1.png?raw=true)

For our first ticket, our technical problem will be that our entire mobile/online banking system is down.
- Email Address: Select the user we created (in this instance it is Kathy999999999@gmail.com
- Full Name: Kathy Bates (this should fill in automatically when selecting the Email Address).
- Help Topic: Report a Problem
- Issue Summary: entire mobile/online banking system is down
- Summary: My employees are reporting that users are no longer able to access their online banking portal. The one who can occasionally access it, cannot log in.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture2.png?raw=true)

Our support is now made.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture3.png?raw=true)

Now we are going to login to the [Agent Portal](http://localhost/osTicket/scp/login.php)
- Login in as John
- Click on the ticket that was created as the End User

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture4.png?raw=true)

Looking at the ticket, there are parameters that we should always go over:
- Status: Is the ticket open, closed, or resolved
- Priority: Is the ticket low, medium, high, or emergency priority
- Department: Which department is the ticket assigned to
- Assigned to: Is the ticket assigned to a specific help desk technician
- SLA Plan: What is the severity of the ticket
- Help Topic: What kind of problem is the ticket
We will now go over the ticket and make updates to the parameters based on the problem of the ticket.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture5.png?raw=true)

We are going to update the following:
- SLA Plan: Sev-A; Wide impact, customer's unable to do online banking.
- Priority Level: Emergency; Customers cannot access their online banking accounts.
- Help Topic: Report a Problem / Business Critical Outage; No customers are able to access online banking.
- Assigned to: Online Banking; Customers not able to access online banking portal, assigning to Online Banking team.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture6.png?raw=true)

After updating the ticket information, we can see there are notes entered on the ticket that those attached to the ticket can see.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture7.png?raw=true)

Since the ticket is assigned to the Online Banking team, we are going to login as Jane (as she is assigned to Online Banking) and we are going to update and resolve the ticket.
- Assignee: Jane Doe; I'll be taking this ticket.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture8.png?raw=true)

We are going to send a reply message to all active recipients on the ticket.
- I suspect the problem might be related to the recent updates. We tested them sufficiently, but I am going to look into it further and roll them back if I determine that was the cause."

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture9.png?raw=true)

Now we will send a reply as if we have figured out what the solution is to the problem.
- It was determined that the root cause was the recent update. We rolled it back, notified the vendorm and are waiting for a proper fix. Online banking should be up and running.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture10.png?raw=true)

The ticket is now resolved, we need to change the status so that is no longer in the queue.
- Se the ticket status to Resolved.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture11.png?raw=true)

The ticket is no longer in the Open Queue.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture12.png?raw=true)

We will now create another ticket:
- Email Address: ken9989@gmail.com
- Full Name: Ken Bates
- Help Topic: General Inquiry / Other
- Issue Summary: Accounting deparment needs adobe uprade because they are unable to access software
- Summary: It looks like many people in the accounting department cannot use their adobe software.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture13.png?raw=true)

Login back as John in the Agent Portal
- Select the latest ticket that was submitted.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture14.png?raw=true)

Update the ticket:
SLA Plan: Sev-C; Only two people are unable to open adobe reader.
Assigned to: John Doe

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture15.png?raw=true)

Let's send out a message to the recipients as if we talked to the customers and asked them to restart their workstation:
- Customer states only two people in accounting department are unable to open and use adobe reader. Customer testing restart, will call back after lunch.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture16.png?raw=true)

We will send out another message stating that the issue is resolved:
- Customer states that the restart fixed the issue, closing out ticket.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture17.png?raw=true)

When you do a Post Reply, your post can be seen by anyone attached to the ticket. You can Post Internal Note as well, and these notes will not be seen by the customer.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture18.png?raw=true)

Here is an example of a Post Reply (top post) and a Post Internal Note (bottom post)

Set the status of that ticket to resolved.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture19.png?raw=true)

This is the final ticket we are going to create - return to the End User screen and create ticket.

In this instance, we are going to say that the CFO is unable to use their laptop.
- Email Address: kathy999999999@gmail.com
- Full Name: Kathy Bates
- Help Topic: Report a Problem / Personal Computer Issues
- Issue Summary: CFO states he is unable to use laptop
- Summary: Laptop won't power on, even though they are pressing the power button.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture20.png?raw=true)

We are going to update the following ticket properties:
- Priority: Emergency
- Assigned to: John Doe
- SLA Plan: Sev-B; May reclassifty after we get more information.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture21.png?raw=true)

We will see that the issue has been resolved, there was an issue with their charger.
- CFO's laptop was not charging due to broken charger. Brought new charger now successfully charging.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture22.png?raw=true)

Go ahead and set the ticket status to:
- Status: Resolved; Charger was broken, because of this, battery was dead and unable to turn on.

![image](https://github.com/seanmarqueling/Tickets-and-Tickets-Lifecycle/blob/main/Picture23.png?raw=true)
