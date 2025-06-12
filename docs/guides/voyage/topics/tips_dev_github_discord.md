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
   A(["Enable GitHub/Discord Integration"]) --> B(Step 1 - Review this </br><a href='https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22' target='_blank'>Documentation</a>);
   B --> C(Step 2 - Create a team</br>channel thread -</br>GitHub Events);
   C --> D(Step 3 - Open a <a href='https://discord.com/channels/330284646283608064/1193342042080817323' target='_blank'>Support</br>Ticket</a> so the Admin</br>team can create a</br>Discord webhook for</br>your team);
   D --> E(Step 4 - Use the webhook</br>provided by the Admin</br>team to update</br>your GitHub repo</br>settings);
   E --> F(Step 5 - Test by creating a</br>PR);
   F --> Z([End]);
```