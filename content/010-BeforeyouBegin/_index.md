---
title: "Before You Begin"
chapter: true
weight: 10
---

![Title](/images/DevLabSetup.jpg)
## Objective

This workshop is intended as a documented and outlined guide to set up a new Azhure EOD environmnet. This walkthrough will outline how to set up the basics with the goal of adding users, queues, call routing, etc. The end goal is to be able to send an inbound call using recommended demonstrations and successfuly deliver to an Agent. You will learn what tools agents have at their disposal when handling the interactions and how to best leverage those tools. This document is a recommendation and may not be one-size-fits-all.


**Notes before you start**: <br>

It is recommended to use search functionality in the admin panel vs. manually trying to navigate to any of the admin sections (Please see image below)
![Search](/images/gcadmin.png)

It is highly recommended to use naming conventions when creating any items (other than location, site, and base settings) to ensure you are not developing over colleague deployments. Ex: JaneDoe_Queue or JaneDoe_Inboundflow, etc

## Activating Your Account
1. Click the link in your welcome email to activate the account. _It is recommended that you enter in a shared account for this initial setup, instead of a personal account, to simplify recovery for future users_

2. **Admin** > **Genesys Add Ons** > **Ensure Genesys Cloud Voice Tile is active**
![Activate ](/images/activate.jpg)

_This should be enabled by default, however non GCV org orders will require manual activation <br>
If activation is required, select the tile and activate GCV- this can take around 10 minutes to fully activate_

**Note**: You may need to skip and come back to "Ensuring Genesys Cloud Voice is Activated" as making sure the proper roles and permissions have been assigned to the user may need to be accomplished first
