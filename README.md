# CallPop 3.0 ReadMe #

## Search for and Log Calls Page ##
The purpose of this page is to provide everyone with access to call data via a simple interface. 
Both the **File Number** and **Phone Number** searches allow for simple searches, while the
**User Extension** search allows para's to see what calls still need to be logged and log them; and managers can now log calls 
on behalf of para's using the administrator dropdown (para's only have access to their own call history) as the Proxy User.

### Navigate to Search for Calls Page ###
- [X] Click on the blue 'Search Calls' button that is fixed to the right of the screen of the main CallPop page
![Image of Search Calls button](https://github.com/senorzacharias/images/blob/master/searchforcallbtn.PNG)


### File Number Search ###
- [X] Enter a file number and click search to retrieve all logged calls for the given file number
![Image of File Number Search](https://github.com/senorzacharias/images/blob/master/filenumbersearch.PNG)

### Phone Number Search ###
- [X] Enter a phone number to retrieve all logged calls for the given phone number
![Image of Phone Number Search](https://github.com/senorzacharias/images/blob/master/phonesearch.PNG)

### User Extension Search ###
Loads table with all calls, logged and unlogged, for an individual para over the last 30 days

#### Para's ####
Can search only by their verified extension number
![Image of User Extension Search](https://github.com/senorzacharias/images/blob/master/userextensionsearch.PNG)

#### Managers ####
The administrator dropdown lists all para's and allows you to search individually
		to see the para's call list and log calls on their behalf as the Proxy User
![Image of User Extension Search](https://github.com/senorzacharias/images/blob/master/userextensionsearch.PNG)

#### Logging Calls ####
-[X] Search by User Extension
		-- UNlogged calls will show a red "X" and a Log Call button
		> All UNlogged rows will show red on hover
	[X] Click the Log Call button for the call you want to log
		-This will return to the main CallPop page
		-The chosen phone number will appear at the top next to **Called Number:**
	[X] Log the call following normal procedure
		-Enter the File Number and click the Search button
		-Ensure all required fields (Caller, Contact Result, Payment Options, Notes) are filled
			-Users cannot save the call until requirements are met
		-Click the green Save button fixed to the right of the screen

### Proxy User ###
The Proxy User column corresponds to logged calls and the user that logged them using the Call Search page (clicking the Log Call button), be them a para or manager. 
This information is relevant for two main reasons:
- Managers can track who the calls were logged by
- The Proxy User field is only populated by clicking a Log Call button on the Call Search page:
	-Blank Proxy User fields for logged calls indicate the original para logged the call from the main CallPop page
	-Logged calls with a Proxy User that matches the original para indicates that they logged their own call using the Call Search page
