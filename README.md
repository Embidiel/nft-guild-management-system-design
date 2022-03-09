# NFT Guild Management System Design

**Why build?**
I've been thinking of scaling up and improving the current system that I'm currently using. There are some parts of the current system that contains replicated code or logic that should have been built to be reusable in the first place. 

Also, there's this QR Code Photo Generation feature that I should have used a file system instead of using the drive of the machine where the application is hosted.

If my guild scales up to a hundred or thousand (hopefully) people across the globe, I'll definitely need a tool to manage this people to check their progress.

**Scope**

****

**Management Dashboard**

 - Monitor the progress of different players across different games that they are playing.
	With the word *progress*, this will vary based on the game that they are playing like 
	> A guild member's available items with partnered quantity and price
	> A guild member's available / playable characters with detailed level or number of experience points
	> A guild member's battle logs / records
	> A guild member's average number of farmed item.
	> A guild member's battle win rate
-	Management of players in terms of:
    > Removing or banning a guild member due to breach of guild rules.
    > Adding a new guild member to the guild
    > Modifying a guild member's information
    > Checking the list of guild members
  - Checking the investment portfolio of the guild manager
    > The current overall worth of the NFT characters per game is the most important detail to be tracked here.
   - Management of guild admins that can use the dashboard
     > Only the guild manager can access this part of the management dashboard.
     > Same thing as managing guild members, the guild manager can add, modify or remove a guild admin.
