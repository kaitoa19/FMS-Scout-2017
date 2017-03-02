# FMS-Scout-2017
This document will give you, (most probably) Will X., step by step instructions on how to use this year's version of the FMS Scouting System.
### Setting up the Excel Workbook
1. Find the event you will be tracking on [the Blue Alliance](https://www.thebluealliance.com/). Here, note the number of teams competing at the event. Also note the event key, where the URL event page is thebluealliance.com/event/event_key. Often this will be the event's year followed by some string (ex. 2016nyny).

2. Go to the "Rank" sheet and select cells A3:U3. Use the fill handle to make n rows, where n is the number of teams competing at the event.

3. Run 2017FMS.jar. This is achieved by navigating to the jar file's directory, then executing
  ```
  java -jar 2017FMS.jar
  ```

4. Set the event key. This is achieved executing:
  ```
  setEvent event_key
  ```

5. Retrieve team list. Execute:
  ```
  teamList
  ```
Executing this should automatically copy the team list to your clipboard. At this point, go back to the "Rank" sheet in the Workbook. Select cell B3 and paste.
