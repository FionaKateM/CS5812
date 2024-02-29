Note: This excel sheet is an updated sheet of 'movies_clean' from Github.

Updates done:
- Fixed typo on 'Review_by_Crtiics' to 'Review_by_Critics'
- Removed instances/rows that weren't English, Spanish, German and French for Language 
- Imputed the actual values from reliable sources for 'Budget' and 'Gross earnings'. 
  - For 'Budget', I couldn't find the actual values for 5-10 instances that were NA
  - For 'Gross earnings', I couldn't find the actual values for ~10% of the instances that were NA


Important Notes:
- I have left the NA. I don't know if this should be imputed or outright deleted, so this needs to be discussed. 
- I haven't converted the currencies
- Initially, I tried to assign units '($)' & '(min)' to variables 'Budget' and 'Gross_earnings' & 'Duration' respectively, but you get an RStudio error when you assign a unit/brackets to a variable, so I am fixing this
