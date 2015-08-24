Test Cases Implementation :

Test Case 1 : 

Validated 'Search' button functionality.
Step 1 : Selected 'Location' from drop down menu.
Step 2 : Clicked 'Search' button.
Step 3 : Clicked on link 'Exclude nearby locations'

Log Info : TestCase_01

[info] Playing test case TestCase_01
[info] Executing: |open | / | |
[info] Executing: |click | css=div.l-pre-1 | |
[info] Executing: |click | css=li.item.selected | |
[error] Element css=li.item.selected not found
[info] Test case failed
[info] Test suite completed: 1 played, 1 failed


Test Case 2 :

Validated Restaurant navigation on click events.
Step 1 : Opens Search Result.
Step 2 : Clicked on Restaurant 'Tim Tai'

Log Info : TestCase_02

[info] Playing test case TestCase_02
[info] Executing: |open | /bangalore/koramangala-restaurants | |
[info] Executing: |clickAndWait | link=Tim Tai | |
[info] Executing: |click | css=a.level-5 | |
[info] Executing: |clickAndWait | //div[@id='mainframe']/div[2]/div/div/div[15]/a/div/div[2] | |
[info] Test case passed
[info] Test suite completed: 1 played, all passed!
[info] Playing test case Untitled
[info] Executing: |open | /bangalore/koramangala-restaurants | |
[info] Executing: |clickAndWait | link=Tim Tai | |
[info] Executing: |click | css=a.level-5 | |
[info] Executing: |clickAndWait | //div[@id='mainframe']/div[2]/div/div/div[15]/a/div/div[2] | |
[info] Test case passed
[info] Test suite completed: 1 played, all passed!


Test Case 3 :

Validated 'Search' filter functionality.
Step 1 : Opens Search result.
Step 2 : Applied filter according to 'High-to-low' Popularity.

Log Info : TestCase_03

[info] Playing test case TestCase03
[info] Executing: |open | /bangalore/restaurants/empire-restaurant | |
[info] Executing: |click | css=div.search-filter-icon | |
[info] Executing: |clickAndWait | link=Popularity - high to low | |
[info] Test case passed
[info] Test suite completed: 1 played, all passed!


Test Case 4 :

Validated 
Step 1 : Selected  
