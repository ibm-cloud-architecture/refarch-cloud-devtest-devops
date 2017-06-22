# Getting Ready for the DevTest DevOps Lab
This document provides you with the preparation for the lab. Please complete this prior to starting.

## Objective

This document provides all of the preparation you need to set up accounts and use those accounts to complete the [Create and use a microservices toolchain with DevOps Insights (v2)](https://www.ibm.com/devops/method/tutorials/tutorial_toolchain_microservices_cd?task=1). To be successful in the tutorials, you must have access to the internet, a set of active accounts noted below and this preparation document. Your Bluemix account needs to have an organization and two spaces created.  Please follow these guidelines when preparing for a lab: 
  - be mindful to limit your tool chain name to less than 30 characters and ensure it is unique
  - ensure you are in a Bluemix organization in the US South region (where Open Toolchain is available)  
  - if you are using a temporary Bluemix account, ensure you have sufficient memory and service instance availability
  [click here for guidance](https://console.bluemix.net/docs/pricing/index.html#bmtrial)
  
 **Use the accounts/credentials creared here in the lab tutorial you will access at the end of this document**

**Tasks**:
- [Task 1: Create Bluemix trial account](#task-1-create-bluemix-trial-account)
- [Task 2: Create Bluemix organization and spaces](#task-2-create-bluemix-organization-and-spaces)
- [Task 3: Create GitHub account](#task-3-create-github-account)
- [Task 4: Create a Sauce Labs account](#task-4-create-a-sauce-labs-account)
- [Task 5: Set up Slack access](#task-5-set-up-slack-access)
- [Task 6: Background Reading](#task-6-background-reading)

## Task 1: Create Bluemix trial account

1. If you already have an active Bluemix account, you can skip this task.
2. Open a web browser and enter the following URL: [https://console.ng.bluemix.net/](https://console.ng.bluemix.net/)
3. Click on the **Sign Up** button.
4. Follow the directions to fill out the form. Note you will need access to an eMail account to confirm the account setup activity. Make note of the password you specify.
5. Click **Create Account**. This will cause Bluemix to send an email to the eMail account you specified.
6. Login into the eMail account you specified. Open the eMail with the subject: _Action Required: Confirm your Bluemix account_.
7. Click on the **Confirm Account** button.
8. You now have an active Bluemix trial account.

## Task 2: Create Bluemix organization and spaces

1. Log in to Bluemix at: [https://console.ng.bluemix.net/](https://console.ng.bluemix.net/)
2. If this is your first time logging into this Bluemix account, you will be asked to enter an organization name. Ensure you are in the _US South_ region, pick one of the suggested defaults, such as your Bluemix ID or eMail address as the Organization name and click **Create**. If this is not your first time to log in to this Bluemix account, and this is a trial account, use the Organization you created when you first logged into this Bluemix account.
3. Create two Bluemix spaces (staging and prod) for use in this lab. If this is your first time logging into this Bluemix account, you will be prompted to create a space right after creating an Organization.  Enter **staging** as the space name and click **Create**,  
4. Click **I'm Ready**.  If you are not prompted to create a space, create the staging space when you create the prod space below.
5. Click the upper-right hand corner environment settings and click on **Create a space**.
6. Enter **qa** as the space name and click **Create**.
7. Repeat the steps to create a space called **prod**.
8. If you have created all three spaces correctly, when you click the upper-right hand corner environment settings and click on the down-arrow for _Space_ you will see all three spaces.

Only two spaces are needed for the lab, if you need to create additional spaces, repeat this process.

## Task 3: Create GitHub account

1. If you already have a GitHub account, skip this task.
2. In a web browser, enter the following URL: [https://github.com/](https://github.com/).
3. Follow the directions to fill out the form. Note you will need access to an eMail account to confirm the account setup activity. Make note of the password you specify.
4. Click on the **Sign up for GitHub** button. This will cause GitHub to send an email to the eMail account you specified.
5. Login into the eMail account you specified. Open the eMail from GitHub with the subject: _Please verify your email address_.
6. Click on the **Verify email address** link.
8. You now have an active GitHub account.

## Task 4: Create a Sauce Labs account

1. In a web browser, go to the following URL: [https://saucelabs.com](https://saucelabs.com)
2. Click **Free Trial**.
3. Fill out the information and click **Create Account**.
4. Go to your email account and accept the Sauce Labs trial account.

## Task 5: Set up Slack access

Once you create and add yourself to the Slack team/channel - use it in the tutorial. Feel free to install the Slack client on your desktop or the Slack mobile app to access Slack.

### Create personal Slack ID

1. If you have a personal Slack ID you want to use, you can skip this section.
2. In a web browser, open a new tab and go to the following URL:
   [https://slack.com](https://slack.com)
3. Enter your email address and click **Get Started**.

### Add Slack ID to team

1. In a web browser, open a new tab and go to the following URL to go to the (already created) Slack team.  You could create and administer your own Slack team if you would prefer, the instructions for doing so are not part of this exercise.

   [https://bluemixdevopslab.slack.com](https://bluemixdevopslab.slack.com)

2. Enter the following information:
   1. Email address: **BluemixDevOps@gmail.com**
   2. Password: **bluemix4me**
      and click **Sign in**.

3. Click on the down arrow to the right of BluemixDevOps, then click **Invite People**.
4. Add your Slack ID email address.  Click **Send Invitations**.
5. Return to the email InBox for your Slack ID.  You will have an invitation to join the BluemixDevOpsLab team.  Open the email and click **Join Now**.
6. Enter your information for the BluemixDevOpsLab Slack team and click **Next**.
7. Enter your password for the BluemixDevOpsLab Slack team and click **Next**.
8. Click **Continue** then **I agree**.
9. You will be signed into the BluemixDevOpsLab Slack team.

### Join appropriate channel

1. Join the relevant Slack channel based on the location of your training

  - montp_demolab_devops
  - ny_demolab_devops
  - tokyo_demolab_devops
  - melb_demolab_devops

This channel will show all the messages the Toolchain sends to it.
   
## Task 6: Background Reading

1. Complete the readings [located here](https://github.com/palistra/devops-demolabs/blob/master/lab-1-read-template-paper.md)


## Now go to your tutorial and begin! [CLICK HERE](https://www.ibm.com/devops/method/tutorials/tutorial_toolchain_microservices_cd)

