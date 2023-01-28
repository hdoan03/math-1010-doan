# README
The files in this folder are titled `MF_x.npy` where x is a number between 
0 and 11 representing networks where the particpants were asked the corresponding question below. 
The other file in this folder is titled `MF_OR.npy` and is the OR network, where an edge is kept if it was present in any of the other 12 networks.

0: Those from whom the respondent would borrow money     
1: Those to whom the respondent gives advice     
2: Those from whom the respondent gets advice     
3: Those from whom the respondent would borrow material goods    
4: Those to whom the respondent would lend material goods
5: Those to whom the respondent would lend money
6: Those from whom the respondent receives medical advice
7: Non-relatives with whom the respondent socializes
8: Kin in the village
9: Those whom the respondent goes to pray with
10: Those who visit the respondent’s home
11: Those whose homes the respondent visits

You have three metadata files: `MF_gender.csv`, `MF_caste.csv`, and `MF_age.csv`. All values are stored as a number.

GENDER VALUE KEYS:
MALE: 1
FEMALE: 2

CASTE VALUE KEYS:
OBC: 0
General: 1
Scheduled Caste: 2
Scheduled Tribe: 3

--------------------------------------------------------------------------------------------------------
Agreement: Any researcher using the data and/or code included here agrees to properly reference the origins of the data and code from the following papers:
Abhijit Banerjee, Arun G. Chandrasekhar, Esther Duflo, and Matthew O. Jackson. "The Diffusion of Microfinance" Science 26 July 2013: 341 (6144), 1236498. doi: 10.1126/science.1236498
Matthew O. Jackson, Tomas Rodriguez-Barraquer, Xu Tan (2012) "Social Capital and Social Quilts: Network Patterns of Favor Exchange," American Economic Review.
