# How to forward emails from your GoDaddy Domain to your personal Email.

## Guide

Go to your GoDaddy Account, go to My Products, Additional Products, Redeem Email Forwarding, select the domain you want to forward the email of. Refresh the page, and a new **Workspace Email** Section should appear, **Manage All**. Create > Forwarding (top right button) put in the email address you want to forward and the email address you want it forwarded to. If you want any email sent to your domain sent to that address, select catch-all.

Next you will need to setup MX records if your DNS is handled by an external provider like cloudflare. On the **Workspace Email > Manage All** Page, click the tools menu and select server settings. In here you will see the two MX records you need to set, the first column is the priority, the 2nd is the server address.

## Send From

### Outlook

If you want to be able to send from an email address from this domain you will need to add it as an alias to your Outlook account. Go to your [Outlook Account Profile](https://account.microsoft.com/profile/) and select the [Contact Info Tab](https://account.microsoft.com/profile/contact-info). Click manage this email address next to your account, from here you can add an email address. Add an existing email address as a Microsoft account alias. This will send an email to the address you specify, you will then need to click the link to verify ownership, you can now send emails from that account.

## Sources

[Set up my forwarding email address - GoDaddy](https://uk.godaddy.com/help/set-up-my-forwarding-email-address-7598)  
[Checking and managing my MX records - GoDaddy](https://uk.godaddy.com/help/set-up-my-forwarding-email-address-7598)

