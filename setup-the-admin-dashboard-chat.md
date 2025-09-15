---
title: "Setup the Admin Dashboard Chat in collony AI"
description: "Create a private Telegram dashboard chat in collony AI to receive alerts, moderation logs, and reports."
---

# ⚙️ Admin Dashboard

In addition to your main community chat, you’ll need a **private Telegram group** that serves as your **collony dashboard**. This is where moderation alerts, removals, and suspicious activity reports will be sent for your team’s review.

1. **Create a Private Telegram Group**  
   Name it something clear like **[Your Project] Dashboard** and add core team members who should receive moderation updates.  

2. **Enable Visible Chat History**  
   In **Group Settings → Chat History for New Members**, set history to **Visible**.  

> ✅ **Required:** Chat history must be visible in **both** your main community chat and your dashboard group for collony to function properly.  

3. **Add collony to the Dashboard Group**  
   As with your main chat, click **Add Member**, search for **@CollonyBot** (or `collony.ai`), and add it.  

![Adding collony bot to the dashboard group](/public/Screenshot_2025-08-22_at_12.08.54.png)

4. **How the Dashboard Works**  
   When collony flags suspicious content, it will:  
   - Remove the message from the main chat  
   - Mute or ban the user (depending on rules)  
   - Post a detailed report in your **admin dashboard group** with sender info, removed content, and reason for action  

   This way, your team has full visibility without disrupting the community experience.  

![Example of collony AI admin dashboard log](/public/Screenshot_2025-08-24_at_17.47.53.png)

> 🎉 **That’s it!** By completing these steps, you’ve fully configured the collony AI community moderator for your project.