# Python Selenium Demo

## Rules and Guidelines
You may use any resources you need to complete it, including emailing questions to me. However, please be sure that you've googled and read docs thoroughly prior to asking questions.

* We will be looking at the readability and cleanliness of your code.
* Provide unit tests. The cleanliness and readability of tests is just as important as your production code.
* Think simple. Readability and modularity are better than being clever.
* Track your changes in a git repository and make your commits atomic. 
* Send a public link to your git repository (e.g. via github or gitlab)

## Project Requirements
This is a project to automate the following actions using the Page Object Model: 

1. Go to Cars.com and:
    - Select `Used Cars`
    - Select Make `Honda`
    - Select Model `Pilot`
    - Select Price `50000`
    - Select Distance `100 miles`
    - Enter Zip Code 60008
    - Click `Search`

2. Validate using assertions that 4 filters are displayed next to `Clear All` 
    - Max Price is 50000
    - Selected Make is Honda
    - Selected Model is Pilot
    - Selected `Used`

3. Select `New` radio button from New/Used
4. Validate using assertion that the `New` filter is displayed and `Used` is NOT displayed
5. Select Touring 8-Passemger from Trim 
6. Validate using assertion that the `Touring 8-Passenger` filter is displayed
7. Select the second available car

8. Validate using assertions: 
    - Selected car title contains `Honda Pilot 8-Passenger For Sale`
    - `Check Availability` button is displayed 

9. In the Contact Seller section enter:
    - First Name: Car
    - Last Name: Owner
    - Email: carowner@yahoo.com

10. Scroll down to `Payment Calculator` and take a screenshot

