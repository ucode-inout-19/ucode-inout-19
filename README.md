# FastTrack: A modern solution to a crucial problem
## Introduction
In today's modern world where pretty much every other transportation mechanism utilizes modern technologies such as GPS and digital maps heavily, ambulances are still left behind with just the road sense of the overburdened driver. Communication between the driver and the hospital where the patient has to be taken to is also poor, resulting in waste of crucial time where the hospital could have prepared much better for the arrival of the patient.

This primitivity and miscommunication causes many deaths where the victim could have been saved with modern technology. 

This is the problem which we aim to solve using our project: FastTrack.

## Getting to the hospital quickly

With the advent of Google Maps and similar technologies, drivers these days have a much higher sense of distance and traffic and can predict the ETA to destination much better. 

We have used MapBox on our iOS app, which helps the paramedic and the driver decide the best route to the nearest hospital. The app also tells the driver which area of medicine a hospital specializes in, which may help in getting to the experts quickly.

## Checking availability in hospitals

Whenever a paramedic picks up a patient in their ambulance, they can send out a broadcast to the neareset hospitals, which can then respond accordingly keeping in mind the availability. This helps balance the load between hospitals equally and prevents depletion of medical resources. 

This early notification also allows the hospital to prepare well in advance for the patient's arrival, which saves some crucial time.

## Technologies used

The paramedic is now only for iOS, and is written in Swift. MapBox is used as the mapping component.

The server side code is written in Node.js and TypeScript, and uses Google Maps API for getting the list of nearby hospitals, Redis for caching and MongoDB for data storage.

The web application which is used by the hospital staff is written in React and uses Redux for state management.

All the 3 platforms heavily use SocketIO to ensure all the data is updated in real time and the parties involved do not need to refresh the page to get the updated data.

## Conclusion

We strongly beleive that FastTrack will help save many lives using modern technologies, and will make the healthcare system much more ef
ficient.
