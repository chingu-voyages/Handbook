# How can you integrate GitHub & Discord?
![Voyage topic banner](../assets/horizontal-paint-splash-green.jpg)

Having GitHub status messages automatically posted in Voyage team Discord channels for
significant events, such as when PR's are created, is something that can be very helpful
for teams. For example, knowing that a PR has been created allows team members to act
quickly to help review it.

Follow the following these steps if this is something your team would like to use.

```mermaid
flowchart TB
   A(["Enable GitHub/Discord Integration"]) --> B(Review this <a href='https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22' target='_blank'>Gist</a>);
   B --> C(Create a team channel thread - GitHub Events);
   C --> D(Open a <a href='https://discord.com/channels/330284646283608064/1193342042080817323' target='_blank'>Support Ticket</a> so the Admin team can create a Discord webhook for your team);
   D --> E(Use the webhook provided by the Admin team to update your GitHub repo settings);
   E --> F(Test by creating a PR);
   F --> Z([End]);
```

You can find more information and screenshots in [this Gist](https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22).