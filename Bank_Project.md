<img src="Bank_Vissuals/Bank Project Header.jpg?raw=true"/>

# Drilling Down On IDA Loans.
 
## Background 

The data is a snapshot from the world bank for November 2022. We're going to be analyzing it. More specifically the IDA statement of credits and grants. **Then looking at helpful insights from the SQL inquiries.**

The origin of the data can be found [here](https://finances.worldbank.org/Loans-and-Credits/IDA-Statement-Of-Credits-and-Grants-Historical-Dat/tdwh-3krx) 

<img src="Bank_Vissuals/WHO GUY.jpg?raw=true"/>

The International Development Association (IDA) credits are public and publicly guaranteed debt extended by the World Bank Group. **IDA provides development credits, grants**, and guarantees to its **recipient member countries to help meet their development needs.** 

## The Data 

We started our journey by asking a few interesting questions!  
- What is the highest loan to the IDA? 
- Who has the most loans? 
- Which was the most recent to pay?<br>

## The Insights 

- Identified the top five countries with the most debt. 
- **Recommend checking if the top 5 are utilizing it for their development.**
- Identified the 5 countries with almost zero debt to IDA. 
- **Recommend confirming if the bottom 5 need more resources.** 
- It would be good to have a look at who is paying back most consistently.
- **We took a close look at Nicaragua specifically.**
  
### Let's get into it!
  
Want to guess what the answer is before I tell you what the database says?
<img src="Bank_Vissuals/QRY_results for details_COMBINED SHRUNK.png?raw=true"/>
<img src="Bank_Vissuals/flags.jpg?raw=true"/>

**India** has both the most amount owed at **793’256’127.64**  
**and** the highest number of loans of **58’339** 

**The curveball question** was tricky though. **The most recent country to pay was Tanzania.**
<br><br><br>
The next question we had was how much activity is going on in general. **We looked at how many total transactions.** 

<img src="Bank_Vissuals/Total Transactions_Combined.png?raw=true"/>

Looks like lots of activity that's great to see. With **1'109'994 transactions currently recorded.** What I see here is countries are actively investing in development and looking for ways to grow. 

We were asked to get some details about Nicaragua and this is what we found. 

<img src="Bank_Vissuals/Looking_At_Nicaragua_Combined.png?raw=true"/>

The amount gets kind of crazy to think about. The SUM of all their loan amounts is 84'467'522'051, **That's 84 Billion!** Is there a limit on how much can be owed? If not then there probably should be. 

Now one of the most interesting inquiries was to group transactions by country. **Let's look at the top and bottom 5 for the transaction amount.**

<img src="Bank_Vissuals/Total_trans_Country_Group_TOP&BOT_5.png?raw=true"/>

I learned here that Ukraine, South East Asia, and the Middle East are not using the IDA much at all. Two are clearly a category and should be broken up by country in more detail. We can see here as we learned before India has the most transaction 

Lastly, we had one last question looking at the **5 lowest loan amounts by the borrower.**

<img src="Bank_Vissuals/Due_Lowest_5_Combined.png?raw=true"/>

What I learned from this was the amount of the lowest borrower and the highest is a huge difference. Looking at why the divergence to so large between borrowers is worth looking at more. 

## The Insights 
- Identified the top five countries with the most debt. 
- **Recommend checking if the top 5 are utilizing it for their development.**
- Identified the 5 countries with almost zero debt to IDA. 
- **Recommend confirming if the bottom 5 need more resources.** 
- It would be good to have a look at who is paying back most consistently.
- **We took a close look at Nicaragua specifically.**

*The divergence in the borrowers could be related to the rate of interest or return they are offered.*  

If you enjoyed reading this project, let's connect on LinkedIn and check out some other projects I have done!  

[<img src="images/Button.jpg?raw=true"/>](/index.md).
  
