# jmeter-test

Test the performace of TheDummyFlightCompany 

Task 1
Record the following scenario using Jmeter(Task1.jmx)

Scenario:
   - Navigate to http://www.TheDummyFlightCompany.com/
   - Use username/password as user/pass and click login
   - Select current date in flight departing and returning date and Click Continue of Flight finder screen.
   - Select random flights and click continue.
   - Fill firstname, lastname and number and click secure purchase.
   - Click logout.

Task 2
Execute the test case Task1.jmx and provide the performance numbers and analysis report for the following scenario:

        - Incorporate use of multiple users for login, name of the user and random selection of the flights for the execution.
        - Execute the test case for 5 virtual users for 20 minutes with the ramp-up time of 1 user / 10 sec. 
        - The SLA of the execution is 1000 ms/page.
        
##### Task2-datapool.csv contains the test data
##### Task2-Results.csv contains the test result
##### Task2-Analysis.docx contains the test result analysis
