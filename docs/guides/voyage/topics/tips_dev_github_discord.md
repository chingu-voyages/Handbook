# How can you integrate GitHub & Discord?
![Voyage topic banner](../assets/horizontal-paint-splash-green.jpg)

Having GitHub status messages automatically posted in Voyage team Discord channels for
significant events, such as when PR's are created, is something that can be very helpful
for teams. For example, knowing that a PR has been created allows team members to act
quickly to help review it.

![GitHub message posted to Discord](../assets/github_discord_msg.png)

Follow the steps shown below if this is something your team would like to use. 

It is important to note that in Step 3 the Chingu Admin team must create a Discord Webhook URL
for your team channel since Chingu's don't have the permissions needed for this. 

```mermaid
flowchart TB
   A(["Enable GitHub/Discord Integration"]) --> B(1. Review this <a href='https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22' target='_blank'>Documentation</a>);
   B --> C(2. Create a team channel thread - GitHub Events);
   C --> D(3. Open a <a href='https://discord.com/channels/330284646283608064/1193342042080817323' target='_blank'>Support Ticket</a> so the Admin team can create a Discord webhook for your team);
   D --> E(4. Use the webhook provided by the Admin team to update your GitHub repo settings);
   E --> F(5. Test by creating a PR);
   F --> Z([End]);
```