# armis-bilisim-teknolojileri-case-study

While writing this program, I proceeded as follows: First of all, I opened the files named "test case" and "friendship_test" in read mode (a+). Then, in the function named readingOfCaseFile, I converted the sample usernames in the file named test_case into a list as integers by separating the \n and *** signs. Then, for each input value, I created a new nested list structure by taking each line on the file named friendship_test and getting rid of the \n and \t contents on those lines. Then I created a 2nd order recommended list by querying each list element based on its input value. Finally, I wrote the query according to whether these lists are empty or not, and if they are not, I print them in ascending order.

My shortcomings were: When I type the suggested friend ids for each input, there is an extra comma at the end.

My code is readable, secure.
