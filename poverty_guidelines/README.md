Poverty guidelines for the 48 contiguous states, hawaii, and alaska

Code get_SES_data uses the national poverty guidelines, individual-level number of people living in the household, and indiviudal-level household income to make a percent of poverty threshold score which is used in these analyses as the individual-level income variable. Additionally, this code will use the ACS metrics and 3-digit zip code to get area-level SES for everyone based on the year of their indivdual-level survey. 

Questions in AoU: "What is your annual household income from all sources?" and "Not including yourself, how many other people live at home with you?" Because of the way the number_living question is phrased, we added 1 to the original value (not shown in this code) Please check your survey wording and adjust accordingly to reflect total number living in the house as expected by the povert guidelines.
