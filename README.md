<a href="dell"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Dell_logo_2016.svg/1200px-Dell_logo_2016.svg.png" align="left" height="48" width="48" ></a>
<br>
# Dell-H2H-CDC

Capture data changes (History) – Every time a change is made to the data, the old data should be captured as history
Capture data in a schema-based compressed file Providing data differences – data delta is about providing differences between two data objects, current state and past date provided. Read the current state and provide it to the utility.
Utility to read the change history captured should be fetched based on the “date” given (the data for which the user want to compare). Compare the data given (current state and all change history) and generate an output with all change records, highlighting the changes (in the case of CSV). The output can be in JSON/CSV format as user requests.