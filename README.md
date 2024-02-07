# Advance-Core-Java-Maven-and-Ant-Introduction
Implemented a standalone product search program in Java that lists matching products for a user who is looking for T-shirts. There are given 3 CSV files, each containing the T-shirts data for Nike, Puma and Adidas respectively. Sample CSV files links are attached here for reference.



PROBLEM STATEMENT:



CSV Fields	                                Details 
ID	                            Unique product id, starting with 2-digit company code
NAME	                          Model name
COLOUR	                        T-shirt Colour
GENDER_RECOMMENDATION	          Gender for which this T-shirt is recommended. M, F, U (M – 
                                Male, F- Female, U-Unisex)
SIZE	                          S, M, L, XL, XXL
PRICE	                          Price of the T-shirt per piece in INR
RATING	                 Rating of the T-shirt from 1 to 5 (1 being lowest and 5 being highest)
AVAILABILITY	Y or N
<img width="750" alt="image" src="https://github.com/YashKeshari/Advance-Core-Java-Maven-and-Ant-Introduction/assets/79370070/b7ae17a2-ca87-4a38-9f3d-79e086dc6520">



PROBLEM STATEMENT:


Input

Program should accept 4 input parameters

Color
Size
Gender
Output Preference 

“Gender” is a String which has two possible values like ‘M’ and ‘F’. M=Male and F=Female.
“Output Preference” is a String which suggests whether the results should be sorted only by Price or by Rating or by both  Price and Rating.





EXPECTED BEHAVIOUR AND OUTPUT:


After getting the inputs, program should search for the T-shirts in all 3 csv files and list the results on standard output, sorted by Output Preference.
Program should be written considering that there could be more csv files and at runtime program should load the files. Please make use of Thread which will look for any new file at a particular configurable location after some configurable time and load the provided file
If the suitable T-shirt is not present in any csv files, then program should return a user-friendly error
Assignment should be implemented as a Maven project.
Maven 3.x should be used.
Use available 3rd party dependencies to read and parse CSV files.
Write an ant script to build a jar file for the same java program
Use the new features of Java 8 wherever possible
Output
Program should display the list of available T-shirts with details on console  for provided user inputs.


