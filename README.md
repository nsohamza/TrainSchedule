[NOT AN EXPERT, AT THE MOMENT A STUDENT WILLING TO LEARN AND IMPROVE]
# TrainScheduleUppsala. 
# Check trainschedule to work. Get notified if any changes to trainschedule
# Create schedule-based automation workflows using Azure Logic Apps



These are the steps used to make this automation worflow: 
- Create a blank logic app and workflow.
  <img width="1664" alt="2572026d33f93bca2b08880874bac411" src="https://github.com/nsohamza/TrainSchedule/assets/112605993/abef5390-77b4-41ef-a794-12f685d98551">
  
- Add a Recurrence trigger that specifies the schedule to run your workflow
  <img width="853" alt="1c309007b723a0fb688563bab187e86e" src="https://github.com/nsohamza/TrainSchedule/assets/112605993/f848bb46-f5ed-4859-877a-6c671ed4f925">
  <img width="822" alt="3a280f6dbd1c6fa772f0e76fceae2d17" src="https://github.com/nsohamza/TrainSchedule/assets/112605993/9e217ce4-8214-49f6-aea9-4e1c481656f6">

- Add a Bing Maps action that gets the travel time for a route.
<img width="807" alt="071518f5f1d9cce2399fb0a9939c6a8e" src="https://github.com/nsohamza/TrainSchedule/assets/112605993/6b866ad9-2fac-4133-acd3-312e29d414c4">

- Add an action that creates a variable, converts the travel time from seconds to minutes, and stores that result in the variable.
- Add a condition that compares the travel time against a specified limit.
- Add an action that sends an email if the travel time exceeds the limit.

<img width="1369" alt="5a12f3c90a562b89ac957da8000a3d71" src="https://github.com/nsohamza/TrainSchedule/assets/112605993/8a8001cc-5e61-4eeb-981b-0e66c8b98da5">



