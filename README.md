# Coffee Drop App Challenge
This task requires you to build either an Android or iOS application, or both. Submitted work in any other language will be considered but is not required.
 
## Brief
A brand new start up, CoffeeDrop, have spotted a gap in the market to build an Android and IOS mobile app which shows their existing 16 national coffee shops, listing them as "locations" for recycling Nespresso coffee pods, for which the client will recieve "cashback" - money for each pod.

### Specification 
0.1 The specification shall be used as follows - Shall requirements are core functionality, Should are desired functionality and Could is optional functionality.

1.1 The application shall be for either iOS or Android

1.2 The application shall run on the latest version of either OS

1.3 The developer shall take as little or as long time as the applicant desires to develop

1.3.1 The developer shall not be expected to spend any more than 4 hours on the project.

1.3.2 The developer could spend as long as he/she liked however.


2.1 The application shall have a splash screen while it loads

2.2 The application shall allow connected users to view a map with the CoffeeDrop locations marked upon it

2.2.1 This map and locations could work offline

2.2.1.1 This could be facilitated by appropriate caching

2.2.2 A user shall be able to "click through" to a more details screen displaying the opening hours for a specific location

2.3 The application shall allow connected users to enter a postcode and show the closest CoffeeDrop locations as the crow flies

2.4 The application shall allow users to query the amount of cashback by entering a quantity for each of the three possible "sizes" of pod
  1) Ristretto
  2) Espresso
  3) Lungo
 
## What we are looking for
 - Completion of an app that fulfills the specification
 - Use of best practices for the appropriate programming language (Swift, C#, Android/Java, Kotlin)
 - Appropriate consumption and error handlig of provided API
 - Appropriate caching 
 - Optionally: Attractive views and styling
 - Clean, well-commented code 
 - A way for us to install the app on a device for testing prior to an interview
 
## Technical Details
- The simple API can be consumed by using the url http://coffeedrop.staging2.image-plus.co.uk
- The API details can be discovered from the Postman file found in the repository
- There is no authentication for the API
- There is rate limiting of no more than 90 requests per 10s on the API
- There is inherited rate limiting of one request per second on the "postcode" request as this will call the free postcode.io API behind the scenes.
- The repository for the API specification is https://github.com/imageplus/CoffeeDropAPIChallenge
- The repository containing the code for the API is this implementation of the API challenge https://github.com/iHazzam/CoffeeDrop

 
 ## Submission Instructions
  - Please email your contact at Image+ with a link to a github repository containing your submission, as well as be prepared to discuss the technical apsects of the challenge at your interview.

