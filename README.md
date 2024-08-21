
![Screenshot 2024-08-20 at 3 48 14 PM](https://github.com/user-attachments/assets/e6ca509b-dcc7-475a-b09b-66d5ee10f279)


# lily's mev reading list
This guide is for engineers who do not have a background in finance or economics but want to understand how to build blockchain technology that allows for more parties to be economically empowered.

'MEV', or maximal extractable value, from the view of a blockchain infrastructure or application developer, can be conceptualized as the way which entities are able to extract value from the underlying system. This list is heavy on market making strategy and algorithmic/model based trading topics as the behaviors in traditional finance are being copied in decentralized finance in an extractive manner. Different from traditional finance, blockchains are not able to regulate entities via law into 'good' behavior and instead must rely on architecture, permissions, and incentive structures to enable the intended users to benefit from a system.

The resources in the list build on each other if consumed in order.

## MEV Reading List
### Introduction to Traditional Finance 
1. [Flash Boys](https://en.wikipedia.org/wiki/Flash_Boys) by Michael Lewis
   - Famous for sensationalizing front-running and for claiming that traditional markets are 'rigged'. Is an odd read because the book better describes what is happening in blockchain trading than in traditional finance (there is no front-running in traditional finance). Recommended reading because it is referenced in other works.
2. Complex Systems Season 1 Episode 1: [How the Smart Money teaches trading with Ricki Heicklen](https://www.complexsystemspodcast.com/episodes/teaching-trading-ricki-heicklen/)
   - Ricki Heicklen (ex Jane Street) discusses how she teaches people how to be algorithmic traders. Good to listen to understand how order book trading works from the perspective of a trader. Touches on adverse selection, why it's better to clear orders often, the power of knowing traders' identities, the difficulty of position sizing, and the different types of arbitrage. 
3. Acquired Season 14 Episode 3: [Renaissance Technologies](https://www.acquired.fm/episodes/renaissance-technologies)
   - Complete history of Renaissance Technologies. Goes over history of model-based trading and why being right 51% of the time will make you billions. Helpful to understand how to build bots (introduced in the Complex Systems episode) and how the statistical games discussed in the the MEV-SBC'24 recording are centralizing. 
4. [Flash Boys : Not So Fast: An Insider's Perspective on High-Frequency Trading](https://g.co/kgs/8LR9aQj) by Peter Kováč
   - Response book to Flash Boys, goes over why traditional fincance does not suffer from front-running or other MEV games (hint: regulation). Good to read to understand how unregulated blockchain trading is and to understand how market makers operate on a buisness level. 

### MEV in Crypto 
5. [Flash Boys 2.0: Frontrunning, Transaction Reordering, and Consensus Instability in Decentralized Exchanges](https://arxiv.org/abs/1904.05234) by Philip Daian Et al.
   - Lays out how MEV games are played on blockchains in an explicit manner.
6. FlashBots MEV-SBC’24 Recording: Max Resnick & Phil Daian [The Incentives of Short Term Censorship Resistance](https://www.youtube.com/watch?v=SBOGdofF4u8).
   - Lays out how blockchain architecture affects how economic powerhouses are able to extract value. Main takeaway is that economic powerhouses (builders/searchers) will try to make money either through latency games, spamming games, or auctions. Blockchain architectures must choose which game they expose. Posits that the four properities needed for a decentralized cryptocurrency include: permissionlessness (ability to join system and express economic value at any time), logical and techincal distribution across many nodes, geographic distribution to minimize colocation profit, and the ability for neutral builders to enter the market without substantial barriers.
7. [i'M NeW t0 mEv](https://mteam.space/posts/im-new-to-mev/) by [@mteamisloading](https://x.com/mteamisloading)
   - Culture and technical piece on 'how to be a searcher'. Good starting point if you want to investigate searching with sections like 'Bot best practices' and 'Social Norms For Searchers'. If not interested in searching, good to read for sake of understand the searcher mindset. 

### Advanced Traditional Finance Topics I'm still reading:
7. [Market Maker Inventories and Stock Prices](https://www.cis.upenn.edu/~mkearns/finread/Inventories_and_Prices.pdf)
   - Will blurb and organize once read 
8. [Automated market maker inventory management with deep reinforcement learning](https://link.springer.com/article/10.1007/s10489-023-04647-9)
   - Will blurb and organize once read 

### Lists of other lists to pull from and organize (mostly crypto specific):
9. [DeFi Reading List](https://jmcph4.dev/defi-reading-list.html)
10. [Jump Crypto Reading List](https://github.com/JumpCrypto/crypto-reading-list/blob/main/MEV.md)
11. [MEV Weekend Reading List](https://github.com/peiyuechen/MEV-weekend-reading-list-)


Reach out if you have more resources, twitter: @lobstermindset! Will update as I find more relevant material. 
  
   
