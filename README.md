### 6b6t.org Bug Bounty Program

The most important thing in Anarchy Minecraft is the security of the coordinates & accounts. Anarchy servers have been failing completely at this task.
One of the examples is NoCom, which allowed for years for anyone with basic programming knowledge to spy on every player.

#### I'm starting a bug bounty of $500 in BTC for every critical bug on 6b6t.org.
#### Requirements:
1. Bounty is for bugs of NoCom or above in severity. If you are able to spy on players all over the map, even unreliably, it qualifies. Same with auth exploits.
2. Any other kinds of bugs that lead to mass coordinate leakage. For example, if some rogue plugin on the server sends coordinates of random players in audio packets, it's eligible for the bounty.
3. Bugs that require a player's interaction don't qualify. For example, trading beehives doesn't qualify.
4. I'm willing to make an exception for bugs that rely on player's interaction if said interaction is very likely to happen in reality.
5. Lagging the server doesn't qualify. DDoSing is also lame.
6. Smaller bugs may qualify for part of the bounty depending on my personal judgement depending on severity.

#### Rules of the bug bounty:
1. Disclosed bugs will be used only to fix `6b6t.org` and `endcrystal.me` if the bug is in SecurityKaiiju.
2. If you disclose a bug that doesn't qualify (ex. Folia bug patched in SecurityKaiiju), I'll never talk about it to anybody.
3. ~~If I discover your bug, you have 3 days to contact me for a bounty. After all, it would be unfair if I quickly patched every bug I saw in packets and declined the bounty.~~
   I don't really monitor packets, but if I discover a bug based on your actions, I'm still willing to pay a bounty.
4. You're allowed to exploit the bug even after disclosure. I'll simply try to patch it as quickly as possible.
5. ~~Only the first person who discloses a bug is eligible for the bounty.~~
   If multiple people report a bug, the bounty may be split between them depending on my subjective judgement.
6. I will never use that bug to exploit any other server.
7. Do not disclose the bug to the public before it's patched. If I get to learn about the bug from a YT video, no bounty.

As you can see, this bug bounty is 100% selfish. I want to secure my own servers, while allowing you guys to sow chaos everywhere else.

#### What software is running on the servers?
The servers are using a custom private fork of Folia called SecurityKaiiju.
I have a few private patches that hopefully fix all coordinate exploits in there. But I could've missed something.
And thus, a bounty.

The fork chain looks like this: [Folia](https://github.com/PaperMC/Folia) -> [Kaiiju](https://github.com/kaiijuMC/Kaiiju) -> [QuickKaiiju](https://github.com/xymb-endcrystalme/QuickKaiiju) -> SecurityKaiiju

Contact: `xymb` on Discord. I'm also available on `6b6t.org` and `endcrystal.me` discord servers.
