---
title: Cycle Billing Day Codes
---

# Cycle Billing Day Codes

These are used to determine when the contract should be billed <br/>
If the calendar has been setup in **Calendar** with the default Cycle Billing Day codes, <br/>
Then the correct billing day code will automatically assigned to the contract <br/>
Typically, the codes are numeric, i.D Day 1 is code 1, Day 2 is code 2. etc.
<img src="img/billing-cycle.png" />

<br />

#### To activate billing code
The customer needs to have a account with the firm <br/>
The account flag needs to set in **Customer Information** <br/>

<br />

#### How codes are picked
The codes were picked on either a monthly or 28 day basis.

* When billing monthly, the software always assigns the code equal to the calendar day. <br/>
e.g. the 14th day is always assigned to 14, the 20th day is always assigned code 20 <br/>
* When billing 28 days, the code is assigned based on a 28 day cycle so that every 28 days, the cycle starts over again
* If your firm uses a combination of 28 day and monthly billing periods to meet customer requirements, refer to Default Billing Method in the Calendar to setup the billing day codes correctly, and activate the Respect Customer Cycle Bill Interval option in the Company Billing Parameters so that individual customers can be flagged ith their billing preference in Customer Billing Settings.

If your firm uses a combination of 28 day and monthly billing periods to meet customer requirements, refer to Default Billing Method in the Calendar to setup the billing day codes correctly, and activate the Respect Customer Cycle Bill Interval option in the Company Billing Parameters so that individual customers can be flagged ith their billing preference in Customer Billing Settings.