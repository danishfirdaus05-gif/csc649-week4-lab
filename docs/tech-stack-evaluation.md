# Tech Stack Evaluation

## Project

Barber booking mobile app that shows barber availability and saves customers' hairstyle preferences.



## Requirements that drive the decision

List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.

* Customers can view barber availability and book a slot
* Customers can save their hairstyle preferences
* Barbers can update their available times
* The availability page loads within 3 seconds
* Customer login details must be stored securely (hashed passwords)



## Options

* Option A: Flutter mobile app with Firebase (auth and database)
* Option B: Native Android (Java) app with a Spring Boot backend and MySQL on a cloud host
* Option C: React Native (JavaScript, using Expo) cross-platform app with Firebase



## Decision matrix

Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

|Criterion|Weight|A score|B score|C score|
|-|-|-|-|-|
|Fits my requirements|5|5|5|5|
|Skills I already have|4|2|4|3|
|Time to build before my deadline|5|3|2|4|
|Free hosting and tools|3|4|2|4|
|Performance and security needs|3|4|4|3|
|Room to grow later|2|4|3|4|
|**Total (weighted)**||80|75|86|

## 

## Decision record

* **Context:** I need to build a barber booking mobile app before my deadline, as a solo student with no budget for hosting.
* **Decision:** Option C, a React Native (Expo) app with Firebase.
* **Reasons:** 1. It scored highest in the matrix, 2. It uses JavaScript, which I already know from web development, so I should learn it faster than Dart., 3. Firebase gives login and a database without me building a backend, which saves time. I must check the current free plan before I rely on it.
* **Consequences:** Easy: one codebase for Android and iOS, and I can test quickly on my own phone. Harder: if I later want custom backend logic, Firebase limits me and I would need to add a separate server.
* **Risks and next review:** Firebase's free limits or pricing could change. What would change my decision: if my lecturer requires a native Android app, I would switch to Option B. I will review this once my first prototype is running.

