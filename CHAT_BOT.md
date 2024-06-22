# Turbine SMS Bot Opt-in

## Use case
Turbine has an sms-based chat bot that reports local wind speeds when a text message includes the phrase "wind check". 

## Message responses
The returned SMS are formatted as simple strings with average, lull, and gust wind speeds (either in knots or mph), wind direction, and the time of the wind reading. A message for wind in knots looks like the following:

`6.2kts S (5 - 8) @13:36:06`

## Privacy Policy
No user data is collected or stored. Text messages sent to the Turbine SMS bot will be checked for the hot phrase "wind check" and "mph" to determine that the asker would like the wind speed returned and in which unit. None of the asker's additional data such as phone number, other message contents or message metadata is read or stored by Turbine.



