# Test Execution 

Clone the Repository: 
### `git clone https://github.com/GarimaGauri/RoomOccupancy_Cypress.git`
Install Dependencies: 
### `npm install`
Run Tests Locally:
### `npm test`
View Test Results: The CI pipeline will automatically execute tests on each push to the repository. Check the CI environment for detailed test results.


### Solution for task
To calculate the occupancy, we can sort the potential guests in descending order of their willingness to pay, and then loop through them. For each guest, we check if they are willing to pay more than EUR 100, and if so, we skip them. If they are willing to pay less than EUR 100 and there are available Premium rooms, we assign them a Premium room. Otherwise, we assign them an Economy room. We continue until there are no more available rooms.
