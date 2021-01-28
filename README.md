# activity-standards

Standards for the ActivityFeeds released by CommunityXYZ.

These activities are shown on every Community dashboard and on the user profiles page on [CommunityXYZ](https://community.xyz). 

Viewblock has started to use the same standards to show the different actions going on under wallet transactions.

`activity-standards` are simple tags that are added to a SmartWeave actions, it's extremely simple to implement. It helps keep a clean and with all the required details in a single transaction.

SmartWeaveJS started allowing tags since version 0.4.23, make sure to at least have this version before trying to use the tags.

### Required tags
- **Service** - (PascalCase) Your project name to identify the service.
- **Community-ID** - The Contract ID of your Community, can easily be found on your dashboard.
- **Action** - (camelCase) Action name, usually a verb. Should be brief, as accurate as possible.
- **Message** - Message explaining what the action is doing, should be brief and as accurate as possible.
- **Type** - Should always be `ArweaveActivity`

#### Example of a transfer from CommunityXYZ

```json
{
    "Service": "CommunityXYZ",
    "Community-ID": "mzvUgNc8YFk0w5K5H7c8pyT-FC5Y_ba0r7_8766Kx74",
    "Action": "transfer",
    "Message": "Transfer to $addy of $value.",
    "Type": "ArweaveActivity"
}
```

### Join us!
If you have any questions, suggestions or just want to hang out with the community of BUILDERs, [join us on Discord](https://community.xyz/chat)!

