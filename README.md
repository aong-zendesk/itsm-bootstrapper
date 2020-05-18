# **ITSM APAC DEMO**
This Bootstrapper allows you to run the following demo scenarios:
- Request Management
- Incident Management
- Problem Management
- Change Management

# **Pre-Demo Setup Steps PLEASE READ**
1. Please note the form IDs for IT Incidents, IT Request and Change Request Form. You can do so by going to the help center, log in as a end user. Click on submit a request and select each of the forms. For eg. "ticket_form_id=360000731751"

2. Go to the guide admin page and view the Chain Frost Theme.

3. Click "Edit Code"

4. Click on homepage_hbs and edit the form ID on line 40 "Need help?", 43 "Requesting something?" and 46 "Submitting change?". 

5. Please do the same for line 49 to link the "Knowledge" button directly to the FAQ and Announcement KB Category.

6. Add at least 1 agent to the T2 Support group.

Users created for the demo:

- John Tan ECAB (ECAB Member)
- Peter Chan ECAB (ECAB Member)
- Jason Lee Change Review (Change Review Process)
- Chris Lim C Staff (C Staff)

# Request Management Flow 
1. Impersonate as an end user and go to the help center to request for a hardware or software.
You may add more hardware or software that you feel that are relevant to the prospect. 
Note you will need to edit the approvals app to add the appropriate CI and to add the knowledge article with an image.

2. Click on the top link to access the Service Catalog or click on the button on the front page "Requesting Something"

3. View the knowledge article and click on the button "Submit Request" at the bottom of the article. Fill in the form. For example: Subject: Requesting for a phone. Description: Current phone is damaged.

4. Revert back to the agent's interface and walkthough on the landing page and the views.

5. Click on the ticket that is generated, and walkthrough on the form field and the apps side bar.

6. Optionally: Talk about the apps that are available on the marketplace that could provide more IT related functionality. Such as DevOps Integration or Remote desktop or Advanced Asset management.

7. Refer to the approvals side bar app and click approve. You could explain that this is built using Sunshine which is available on the enterprise plan or otherwise they could also use an approval app that is available on the marketplace.

8. Once approved, there will be a fullfillment task created that will be assigned to the IT team to procure/process the CI for the end user. Mentioned that there will be different SLAs tracking different type of tickets within Zendesk.

9. Once the fullfillment task has completed. The CI would be automatically created and attached to the user's profile. This would be helpful as this can provide more information on Incident management. 

# Incident Management Flow
1. Use the previous CI that was created from incident management as the scenario for the incident demo flow. Have the end user submit a case through email/phone/web form depending on your prospect's requirement.

**Note:** If the end user is a C Staff, the ticket priority would be set to high and this will also meant that there is another SLA created specifically for C Staff's incidents and requests. You can find out if the end user is a C Staff by going to user profile in Zendesk and look for the Employee Status field. 

2. Once the case has submitted, revert back to the agent's interface to work on the ticket.

3. Mentioned that since we have a knowledge of the current user's CI, the agent would be able to work more efficiently on the ticket.

4. Explain the use of macro and mentioned that to the prospects that the agent have found out they noticed a surge of cases that seem related. Create another ticket and use the macro to upgrade this to a problem ticket, and explain the use of relating the incidents to the problem ticket.

# Problem Management Flow
1. In the problem ticket view, explain the use of the Knowledge capture app.

2. Using the macros and the Knowledge Capture App, the agent could easily link Workaround, Known errors and Root cause related articles to the ticket.

**Note:** You will need to use the problem macro and add the link via the Knowledge Capture App.

# Change Management Flow
1. When a change is required to implement a workaround due to the problem ticket, the agent could create a ticket under the change ticket form. Explains that the type of changes that the agent could use for a change management process. Standard changes are changes that does not need approvals, while normal and emergency changes would require approval.

2. Have the agent create a normal change ticket, and approve via the approval app. 

3. Optionally: You could impersonate as another user to approve the change request.

4. Note that the additional change field to track the change stage. Once approved, there will be an fullfillment task created to implement the change. 

5. Assuming the implementation has completed, the agent could update the stage of the change request using the change macros and automatically add the change review team as followers to the change ticket. 

6. Optionally: Explain the use of the ECAB macro to add the ECAB members to this change ticket as follwers if it is an emergency change for visibility. Mention that we could use business rules such as triggers or automations to shorten any other manual processes.

# TO DO
- Incorporate HR Flow
- Help Center Updates
- ITSM Explore Dashboard


