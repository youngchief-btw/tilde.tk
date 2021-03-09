# [tilde.tk](https://tilde.tk) - Outbound Email

<details>
<summary>Gmail</summary>

### Email me with your desired email address for your [tilde.tk](https://tilde.tk/) (sub)domain

Create a new Google account or use an existing Google account but be aware it will show up in DNS records for the forwarding service.
Then you email [me](youngchief@youngchief.tk) to setup that Gmail address to be the one forwarded for your email address.

---

### Fix emails ending up in spam

After me setting up forwarding you go to 
`Gmail --> Settings --> See all settings --> Filters & Blocked Addresses --> Create new filter`
Fill in `to` field to be your your desired [tilde.tk](https://tilde.tk/) (sub)domain email address
Then hit `Create filter`
All you need to make sure email to it doesn't end up in spam is to make sure you check on the `Never send to spam` and press `Create filter`

---

### Test inbound email

Send yourself an email to your new [tilde.tk](https://tilde.tk/) (sub)domain email address, and watch it come in! (also check spam and archive just in case you don't find it)

---

### Outbound Email

After you can successfully recieve emails, and you setup the filter. You can setup Gmail's `Send mail as` feature (located in Accounts & Import section) using the following values

```
Display Name: [your display name]
Email Address: [your email address]
Treat as alias: (have it on if you want emails to appear in inbox just like your other emails)

SMTP Details (if you wanna use Google SMTP servers):
- SMTP Server: `smtp.gmail.com`
- Port: [the default one is fine]
- Username: [your gmail address without `@gmail.com`]
- Password: [your account password if you don't use 2FA and have Less Secure Apps allowed OR an app password if you have 2FA enabled]
- Encryption: [leave it on the recommend one based on the port you used]
```

You will receive an email with a link/code to use to finish verification. After this you should test outbound emails from that email address!

**That's it! You can now send & receive emails from your (sub)domain email address**
</details>