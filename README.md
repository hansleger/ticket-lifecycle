<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle Example</h1>
This outline contains an example of a ticket's lifecycle within an IT Help Desk environment.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Example Objectives</h2>

- Ticket Creation
- Granting Access
- Ticket Resolution


<h2>Ticket Creation (External User)</h2>

<p>
1) On the osTicket Support Center Home, open a new ticket. 

![Screenshot 2024-04-28 182540](https://github.com/kbd060/ticket-lifecycle/assets/150099961/6f1f9362-faa8-4901-8176-fe96a97b4abc)

<p>
2) Create user contact info, along with a help topic, such as "Karen" and "Business Critical Outage", respectively.

<p>
3) Provide a description of the issue regarding this ticket.

<p>
4) Create ticket.

![Screenshot 2024-04-28 184044](https://github.com/kbd060/ticket-lifecycle/assets/150099961/776d30d1-d76e-4a4b-9979-7dec668fca34)
![Screenshot 2024-04-28 184334](https://github.com/kbd060/ticket-lifecycle/assets/150099961/c8249b4d-399e-462a-8c97-b0b347db14ff)

<p>
5) Repeat the previous steps, using alternate user contact information and/or help topics, to create several tickets.

![Screenshot 2024-04-28 184916](https://github.com/kbd060/ticket-lifecycle/assets/150099961/092af6bb-1581-4fb4-adcf-4940d128de8e)
![Screenshot 2024-04-28 184948](https://github.com/kbd060/ticket-lifecycle/assets/150099961/eb707a2d-20cb-4e7a-94d1-190c5c35244f)
![Screenshot 2024-04-28 185213](https://github.com/kbd060/ticket-lifecycle/assets/150099961/e6cf5627-a1a9-4662-b441-d7b7837281e4)
![Screenshot 2024-04-28 195512](https://github.com/kbd060/ticket-lifecycle/assets/150099961/d8cb2f74-56d3-4b60-88ab-dbf2e08c2327)


<h2>Granting Access (System Administrator)</h2>

<p>
1) Log in as the System Admin (hans), and access the admin panel.

![Screenshot 2024-04-28 190612](https://github.com/kbd060/ticket-lifecycle/assets/150099961/630bac3f-99b3-443a-9152-b6dbb6b6f925)

<p>
2) Go to Agents, and then go to Jane Doe.

![Screenshot 2024-04-28 190922](https://github.com/kbd060/ticket-lifecycle/assets/150099961/617a0499-9b2d-4ee2-84ed-eb39eaca0be4)
![Screenshot 2024-04-28 190944](https://github.com/kbd060/ticket-lifecycle/assets/150099961/34eeb4b4-6588-418e-9da9-3835bf1a7413)

<p>
3) Go to Access and add Support to Jane Doe's Extended Access, with Supreme Admin being their role within Support.

![Screenshot 2024-04-28 191130](https://github.com/kbd060/ticket-lifecycle/assets/150099961/1605b353-4b54-4fa4-98b3-842b9e8108fb)
![Screenshot 2024-04-28 191414](https://github.com/kbd060/ticket-lifecycle/assets/150099961/6ea32226-bf12-4146-812a-635baa7db212)


<h2>Ticket Resolution (Help Desk Agent)</h2>

<p> 
1) Log in as Jane Doe, and access ticket #117214 ("Entire mobile online banking is down"). 

![Screenshot 2024-04-28 195629](https://github.com/kbd060/ticket-lifecycle/assets/150099961/419d935a-e566-4d75-8b66-1763daf3f1a9)
![Screenshot 2024-04-28 195818](https://github.com/kbd060/ticket-lifecycle/assets/150099961/d5a2f11f-f2b2-4a9e-a928-1d1e77f2aa61)

<p> 
2) Update the ticket's priority level to "Emergency", noting the reason why ("Business impacting event").

![Screenshot 2024-04-28 200315](https://github.com/kbd060/ticket-lifecycle/assets/150099961/3b89d0df-f0ea-45f9-baa0-635540513a7b)
![Screenshot 2024-04-28 200334](https://github.com/kbd060/ticket-lifecycle/assets/150099961/a91d6ef5-a7a3-4f88-b82a-95b7725a7491)

<p>
3) Update the ticket's SLA Plan to "SEV-A", noting the reason why ("Business impacting event").

![Screenshot 2024-04-28 202115](https://github.com/kbd060/ticket-lifecycle/assets/150099961/dd16e56c-589f-4573-8b34-a7aa1bb8eba5)
![Screenshot 2024-04-28 202128](https://github.com/kbd060/ticket-lifecycle/assets/150099961/456d0f6f-fe8d-427f-aa4e-66d9bba3785d)

<p>
4) Transfer the ticket from the Support department to the System Administrators department, noting the reason why ("Sys Admins responsible for mobile banking infrastructure").

![Screenshot 2024-04-28 202812](https://github.com/kbd060/ticket-lifecycle/assets/150099961/c17d2df2-b949-46c4-a55e-c75620c827f8)
![Screenshot 2024-04-28 205527](https://github.com/kbd060/ticket-lifecycle/assets/150099961/30f7d650-ac94-4a3d-9a61-cb25fafce441)

<p>
5) Provide Karen updates on her ticket by posting replies within the ticket thread ("Coordinating with Sys Admin team to bring mobile banking back online." "Jerry from System Engineering found and corrected a failed load balancer. Mobile banking should be back up"). Resolve the ticket.

![Screenshot 2024-04-28 205849](https://github.com/kbd060/ticket-lifecycle/assets/150099961/a119d880-f976-4dcd-9f19-a0bae522c2ca)
![Screenshot 2024-04-28 210212](https://github.com/kbd060/ticket-lifecycle/assets/150099961/dcdc090e-70ae-4ca6-b9cb-80423217be74)
![Screenshot 2024-04-29 204652](https://github.com/kbd060/ticket-lifecycle/assets/150099961/67ee5f8f-b0d3-4cd6-a1f5-79ce0af71dd9)
![Screenshot 2024-04-29 204725](https://github.com/kbd060/ticket-lifecycle/assets/150099961/07602e5f-d54c-4976-a668-c5733a199c54)
![Screenshot 2024-04-29 205457](https://github.com/kbd060/ticket-lifecycle/assets/150099961/b496b9d5-1583-483f-9568-093481878dfb)






