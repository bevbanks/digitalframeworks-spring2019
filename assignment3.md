
### Assignment 3

The data set that I cleaned for this assignment was retrieved from the Centers for Disease Control and Prevention's [Vaccine Adverse Event Reporting System.](https://wonder.cdc.gov/vaers.html)

[Original Copy](https://github.com/bevbanks/digitalframeworks-spring2019/blob/master/2019VAERSVAX%20original.csv)

[Clean Copy](https://github.com/bevbanks/digitalframeworks-spring2019/blob/master/2019VAERSVAX%20edited.csv)

###### Below are the steps I took to clean the dataset. 

1. First, I renamed all of the titles for the rows. The original titles were confusing and did not adequately explain what the purpose the data point. Additionally, these titles included acronyms that were not universally understood outside the medical community.
2. I reorganized the columns so that the vaccination name came after the vaccination identification number. 
3. I checked each column for inconsistences and misspellings. In Column C, most of the companys' names were consistent. I changed the name ‘PFIZER\WYETH’ to “PFIZER & WYETH” to match the other names in the set. I made this change using the find and replace tool in excel. 
4. I also removed any commas from the names such as ‘SEQIRUS, INC.’ to match the formatting of the other company names. 
5. I replaced UN unknown for column G to make the information clearer. I also replaced N/A with unknown for consistency. 
6. Then I Googled searched the meaning of several acronyms for columns G and H. The CDC provided several of the meanings for the acronyms. For instance, SC stands for subcutaneous and IM stands for intramuscular. For the acronyms not listed on the CDC, I located their meaning through a Google search. 
7. Next, I replaced UN in column F to 0 because the unknown related to the number of dosages.
8. Lastly, I replaced acroynms such as RL to right leg and LA to left arm. If the box was blank, I put unknown. 


