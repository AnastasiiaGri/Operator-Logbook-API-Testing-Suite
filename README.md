# Operator-Logbook-API-Testing-Suite

🚀 Here’s a summary of the tests included in the collection:

1. GetToken Endpoint

Test: Validates that a token is successfully retrieved and stored in the Token environment variable.
Purpose: Ensures authentication works as expected.

2. GetFolders Endpoint

Tests:
Validates the response contains exactly 14 objects.
Confirms the uid and id of the first and last objects.
Checks specific properties, such as libCat and name, match expected values.
Purpose: Verifies the integrity of folder data.

3. GetAPIVersion Endpoint

Tests:
Validates the response status is 200.
Purpose: Ensures the API version endpoint is functional and accurate.


4. GetActiveProject Endpoint
Tests:

Validates the status message is Optiramp Message.
Confirms that an unauthorized request returns a 403 status code.
Purpose: Ensures proper error handling and the endpoint's ability to identify an active project.

5. GetProjectState Endpoint
Test:

Confirms the response matches an exact JSON structure, including modificationTime.
Purpose: Ensures the endpoint correctly returns the state of a project.

6. GetRecords Endpoint
Tests:

Sets up dynamic variables (timeFrom and timeTo) for filtering records by date.
Validates that the API returns a response containing the expected structure and data.
Purpose: Ensures the endpoint retrieves records based on specific criteria, such as date range, folder UID, and project name.

7. CreateRecords Endpoint
Test: Validates that a record can be created with dynamic timestamps.

Purpose: Ensures that the creation of records works as expected and handles dynamic data

8. UpdateRecord Endpoint
Tests:

Confirms that a record update returns the appropriate status code.
Ensures dynamic timestamps are correctly processed.
Purpose: Ensures the endpoint allows record updates and handles data modifications correctly.


9.GetRecordCount Endpoint
Test: Confirms that the API returns the correct record count for the provided IDs.

Purpose: Validates the accuracy of record count retrieval.



