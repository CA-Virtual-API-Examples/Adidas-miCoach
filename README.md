# Adidas-miCoach

This API is a virtualized sample of the Adidas miCoach API.
Full details of the latter can be found at https://api.micoach.adidas.com/v3/help.

The virtualized sample API is divided into the following groups:
  Achievements
  ClientErrorLogs
  ContentMicroGoalPlans
  Fitness
  Following
  
Full details of the request-response pairs making up the sample API can be seen in the Editor tab.
Note the use of the string pattern {{=[:Email:]}} in the "Append error log".
This will generate a random email address in the response when the request is sent.

All the pairs have JSON responses.  But when you execute any GET requests you can change the format of the response to XML using the $format=xml parameter e.g.
GET /Users/Sample-userId/achievements?$format=xml
