# MicroTransaction Analysis


Objective:
  To learn about the playerbase of an online game, and about how profitable various in-game items are for the game company.
  
Note(s) about the dataset:
  The unique key is Purchase_ID. Age, Item, and Price are the main variables to be considered.
  
Enjoyable Success:
  len() in combination with .unique() is generally very useful.
  Creating dataframes purely for display can be an effective way to present relevant findings quickly.
  df[['Gender','SN']].drop_duplicates(subset = 'SN') made it possible to count users of each gender.
  
  
Satisfying discovery:
  Creating bins by age (5 years apart), and then examining the number of players in each bin showed a nice normal distribution of ages.
