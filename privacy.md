# Demonic Addictions Verification – Privacy Policy

**Last Updated:** October 21, 2025  
**Developer:** [DiscipleShadow](https://discord.com/users/215131967744638976)  
**Organization:** Demonic Addictions Systems  
**Governing Law:** United States  

---

## 1. Introduction
This Privacy Policy describes how **Demonic Addictions Verification** (“the Bot”) collects, uses, stores, and protects personal information and server data.

By using the Bot, you agree to the collection and handling of data as described in this Policy.

The Bot follows a **privacy-first design** — collecting only what is necessary for its features and protecting all stored data through encryption and access control.

---

## 2. Data Collected
The Bot collects limited information necessary to perform its verification, logging, and analytics functions.

### 2.1 User Data
- Discord User ID  
- Age and birthday information (masked and encrypted)  
- Verification status, trust score, and internal flags  
- Servers where the user is verified  

### 2.2 Server Data
- Discord Server ID  
- Server configuration data (channels, roles, verification settings)  
- Whitelist and blacklist entries  
- Lists of users pending or unreachable during verification  
- Aggregated server analytics (non-identifiable, statistical data)  

### 2.3 Subscription Data
- Subscription status, tier, and renewal information  
  - **Note:** The Bot never handles payment data. All transactions occur through **Discord’s official monetization system**.  
- Premium status is stored as a Boolean or timestamped flag to unlock advanced features.  

---

## 3. Purpose of Data
### 3.1 Collected data is used for
- **Verification Management:** Assigning roles based on user age or verification input.  
- **Birthday Announcements:** Optional automated birthday messages.  
- **Security and Moderation:** Maintaining watchlists, trust scores, and lists of unverified users for moderators.  
- **Premium Access Validation:** Checking subscription status via Discord APIs.  
- **Server Analytics:** Generating aggregate (non-identifiable) statistics such as age maps or verification rates.  
- **Developer Communication:** Sending system or policy update notices to server owners.  
- **User Transparency:** Allowing users to view stored data and opt out at any time.

The Bot **never sells, rents, or shares** user data under any circumstance.

### 3.2 Developer Access to Servers Using the Bot
The Bot includes functionality that allows authorized Bot Developers to view a list of servers using the Bot and generate temporary invite links.
**This access is used strictly for:**
- Investigating potential misuse of the Bot.
- Providing direct support to server administrators.
- Ensuring compliance with the Bot’s Terms of Service.

Developers do not access server messages or user content beyond what the Bot itself collects as described in this Privacy Policy. All developer access is logged and restricted to authorized personnel only.

### 3.3 Behavior Monitoring & Safety Signal Tracking
The Bot includes a behavior monitoring system designed to identify potential misrepresentation of age and to improve verification accuracy.
**The system monitors:**
- Entry into NSFW-designated channels
- Newly created Discord accounts
- Usernames containing numeric age indicators
- Keywords commonly associated with age misrepresentation
- Eandomized honeypot question triggers (~5% probability)

These checks contribute to an internal scoring system used solely to support moderation teams. The Bot does not make automated moderation decisions; instead, server moderators receive warnings if concerning patterns are detected. The Scoring **may** be shared with additional servers appon joining if your score is considered in the red. 

### 3.4 Honeypot Question Logging
When a honeypot question fails, the Bot logs:
- The user’s Discord username and ID
- The question asked
- The user’s response
- The expected response based on the user’s prior verification data

### 3.5 Verification Reminder Tracking
The Bot tracks whether a user has completed verification in a server. If a user remains unverified, the Bot records reminder status and timing until either:
- The user completes verification, or
- The user leaves the server
---

## 4. Data Security and Encryption
- All stored data is encrypted end-to-end using secure encryption standards.  
- SQLite databases are fully encrypted.  
- Legacy encrypted backups use **monthly rotating encryption keys**.  
- Only the developer and authorized system processes have access to encrypted data.  
- Moderator-visible information (e.g., verification status) is limited to data relevant to their server.

---

## 5. User Rights
### 5.1 View Stored Data
Users can view all data currently stored about them using the Bot’s built-in data access command.

### 5.2 Opt-Out and Deletion
Users may opt out of all data collection and request deletion at any time.  
When deletion is requested:
- All user-related data is permanently erased from all systems.  
- The user becomes ineligible for most verification features unless they reverify later.  

### 5.3 Transparency
The Bot informs users of their data rights during verification.  
Server owners are encouraged to keep users informed about these options.

---

## 6. Data Retention
- User data is retained only as long as necessary for verification or premium functionality.  
- Inactive or deleted users’ data may be automatically purged.  
- Server analytics and configuration data are retained until the Bot is removed or reset on that server.  

---

## 7. Sharing and Disclosure
- Data is **never shared** with third parties.  
- Discord’s API may process user and server data under **[Discord’s Privacy Policy](https://discord.com/privacy)**.  
- Server moderators can view limited verification data for moderation purposes.  
- Developers may access encrypted data solely for debugging, maintenance, or compliance checks.  

---

## 8. Subscriptions and Monetization
- Premium features are provided through **Discord’s subscription system**.  
- The Bot does **not** process payments directly.  
- Subscription information (status, renewal, tier) is securely retrieved from Discord’s API.  
- Refunds or billing disputes are handled exclusively through **Discord Support**.  

---

## 9. Data Hosting
- The Bot is hosted on **hidencloud.com** in a secure environment.  
- All stored data is encrypted at rest and in transit.  
- Future versions may transition to **self-hosting** to further strengthen data control.  

---

## 10. Policy Updates and Notifications
- This Privacy Policy may be updated from time to time.  
- Major updates will be announced to server owners via the Bot’s developer notification system.  
- Continued use of the Bot after updates indicates acceptance of the revised Policy.  

---

## 11. Contact
For privacy questions, opt-out requests, or legal concerns:

- **Discord:** [@DiscipleShadow](https://discord.com/users/215131967744638976)  
- **Email:** shadow344384@gmail.com *(not monitored regularly)*  

---

© 2025 **Demonic Addictions Systems**. All rights reserved.  
Linked Policies: [Terms of Service](https://github.com/DiscipleShadow/Demonic-Addictions-Verification-Terms-Of-Service/blob/main/TOS.md)
