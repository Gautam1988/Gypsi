Type: Cross Platform Mobile Application 

App Name:  Gypsi (Any where, Any time)

Purpose: Socialized Ride Hailing/Sharing 

End Customers: Drivers, Traveler’s

Business Model: Basic free, Premium payment for additional features

Existing Problems in Ridesharing Apps:-
    1. Surge Pricing (Less Transparency in payment)
    2. Dropping driver incentives
    3. Large signing up amounts from drivers
    4. Security issues for drivers

Customer Problem Statement:-
    1. Driver: "I have to pay commission for every ride which i take and i receive only a portion of the fare"
    2. Hitchhikers: "I can't find people who can offer free travel to me"
    3. Travelers: 
        a) "I can't find a driver who is very near to me and can offer a quick ride"
        b) "I can't find likeminded people who can accompany me during my travel"

Areas Served:
    1. No Payment/Commission, 
    2. Social Networking for travelers, 
    3. Rideshare in remote parts of the world.

Operating System:- Android, iOS, Windows (Administrator dashboard)

Definition:-
    1. User - A person who has registered for the application.
    2. Social Driver - The user who owns a vehicle (eg. Van, Car, Bike etc) and is willing to share his ride without commercial benefits.
    3. Commercial Driver - The user who owns a vehicle (eg. Van, Car, Bike etc) and is willing to share his ride with commercial benefits.
    4. Social Traveler - The user who currently needs a free ride service.
    5. Commercial Traveler - The user who needs a commercial ride service.
    6. Administrator - A person who administers the users. He regulates the status (eg. Ban) of the users.

Brief Description:-
The proposed application provides a socialized ridesharing service based on driver/traveler request and on the willingness of the traveler/driver. 

Pre-Requisites for Registration:-
    1. A user should have a valid Phone number or a Facebook or Gmail or Twitter account. 
    2. A user should be of 18+ years of age.

Status:-
    1. ForRide - A user who is ready to offer a ride.
    2. ForLyft - A user who needs a ride.
    3. Banned - A user who is banned from using the application.

Features (MVP):-
    1. The app should integrate Google maps API for landscape navigation, shortest route & time determination.
    2. The app should integrate Gmail API for authentication.
    3. The app should integrate Gpay API for authentication.
    4. The app should integrate Facebook API for authentication, web scrapping, sharing.
    5. The app should integrate Twitter API for sharing.
    6. When a user signs in via phone number, the app should process OTP based verification.
    7. The app shall have access to the GPS sensor of the user.
    8. A user shall register either as a driver/traveler. This option shall not be editable in future. A user must delete his current account and create a new account 
      to change his profile from a driver to a traveler and vice versa.
    9. A user (driver/traveler) shall register a Social or Commercial account. This option shall be editable in future with corresponding change in fare prices.
    10. A user registered as a social driver should provide the following mandatory details 
        a. Driver pic (with option to take instant photo)
        b. Vehicle pic (with option to take instant photo)
        c. Registered Driver Name
        d. Registered Driver Age
        e. Vehicle Make
        f. Vehicle Model & Year
        g. Vehicle Registration Number
        h. Driving License Registration Number
        i. Copy of License (attachment)
        j. Copy of Vehicle Registration (attachment)
    11. A user registered as a commercial driver should provide the following mandatory details 
        a. Driver pic (with option to take instant photo)
        b. Vehicle pic (with option to take instant photo)
        c. Registered Driver Name
        d. Registered Driver Age
        e. Mobile Number
        f. Address
        g. Vehicle Make
        h. Vehicle Model & Year
        i. Vehicle Registration Number
        j. Driving License Registration Number
        k. Soft Copy of License (attachment)
        l. Soft Copy of Vehicle Registration (attachment)
        m. Fare per km (There should be an option to select individual country currency symbol while entering fare amount)
        n. Fare per hour (There should be an option to select individual country currency symbol while entering fare amount)
    12. A user registered as a social traveler should provide the following details
        a. Traveler pic (with option to take instant photo)
        b. Name
        c. Age
        d. Mobile Number
    13. A user registered as a commercial traveler should provide the following details
        a. Traveler pic (with option to take instant photo)
        b. Name
        c. Age
        d. Mobile Number
        e. Maximum Fare per km affordable by him (There should be an option to select individual country currency symbol while entering fare amount)
        f. Maximum Fare per hour affordable by him (There should be an option to select individual country currency symbol while entering fare amount)
    14. Any registered user may provide the following optional details
        a. Profession
        b. Link to his Facebook account
        c. Link to his Twitter profile
        d. Gpay id.
    15. Any registered user account shall display the following details which he cannot edit
        a. Rating acquired by him
        b. User Reviews about him
        c. Link to his Facebook account
        d. Link to his Twitter profile
    16. A user registered as a driver will have the view permission of a driver
    17. A user registered as a traveler will have the view permission of a traveler
    18. A driver should be displayed as a car/van/bike with approximate fare range in the map, all other details (i.e., profile) should be displayed in a separate 
        screen if a driver is clicked.
    19. A traveler should be displayed by a traveler symbol with requested fair range in the map, all other details (i.e., profile) should be displayed in a separate 
       screen if a traveller is clicked.
    20. A traveler (social/commercial) shall be able to filter for car, van, bike etc.
    21. When a user login as a commercial traveler
      a) He should land on maps of his area with indication of his current location and with the list of all drivers (i.e., globally) available for a ride.
      b) He should be able to enter his source and destination location.
      c) Once the destination address is entered, he should be able to search and view (car, van, bike symbol etc) all the available social or commercial drivers 
         around a radius of 10km along with the details of the expected fare, time of arrival for the journey in addition to all other drivers (fare, time of arrival 
         details need not be displaced for drivers beyond 10km) in global map. He may book a ride with any of these drivers by selecting them manually and sending a 
         ForLyft request.
                                                                                    OR
        Once the destination address is entered, he should be able to automatically book a best fit driver within a radius of 10km. A best fit driver is based on an 
        algorithm that uses the rating, user reviews, no of user rides, time of arrival and fare for the ride.
    22. When a user login as a social traveler
      a) He should land on maps of his area with indication of his current location and with the list of all drivers (ie. globally) available for a ride.
      b) He should be able to enter his source and destination location.
      c) Once the destination address is entered, he should be able to search and view (car, van, bike symbol etc) all the available social drivers around a radius of 
      10km. He may book a ride with any of these drivers by selecting them manually.
                                                                                    OR
      Once the destination address is entered, he should be able to book a best fit social driver within a radius of 10km. A best fit driver is based on an algorithm that 
      uses the rating, user reviews, no of user rides, time of arrival.
    23. A traveler generated booking request shall be forwarded to the manually selected or best fit driver with the details of source & destination, approximate fare 
        range, approximate travel time, short description of the traveler’s profile. The request shall have an optional 150-character message field.
    24. Once a ForLyft request sent by the traveler is accepted by the driver, the traveler shall have view of the path taken by the driver to the traveler with details 
        of time for arrival. The list of all other drivers in the map should become invisible to the traveler until the current ride is completed/cancelled.
    25. When a user login as a commercial driver
      a) He should land on maps of his area with indication of his current location and with the list of all available travelers globally requesting a ride.
      b) He should be able to search and view all commercial travelers (including source, destination address, traveler requested fare details, traveler profile) around a radius of 10km in addition to all other drivers (fare details need not be displaced for travelers beyond 10km) in global map. He may book a ride with any of these travelers by selecting them manually and sending a ForRide request.
    26. When a user login as a social driver
      a) He should land on maps of his area with indication of his current location and with the list of all available travelers globally requesting a ride.
      b) He should be able to search and view all social travelers (including source, destination address, traveler profile) in global map. He may book a ride with any of these travelers by selecting them manually and sending a ForRide request.
    27. A ForRide/ForLyft request can be forwarded to a traveler/driver who is within a radius of 10km.
    28. A ForRide/ForLyft request sent anytime will automatically disappears from traveler/driver screen after a period of 60sec.
    29. Only one ForRide/ForLyft request can be sent at a time. A new request can be initiated only after 300sec of initiating the previous request.
    30. A driver/traveler can either accept, decline the ForLyft/ForRide request. He can also block the user from sending any future request. 
    31. Once a ForRide/ForLyft request is accepted by the traveler/driver, a OTP shall be generated and be forwarded to traveler mobile via sms and shall be visible 
        in his screen.
    32. Once a ForRide request sent by the driver is accepted by the traveler, the driver shall have view of the shortest path leading to the traveler with details 
        of time for arrival. The list of all other travelers in the map should become invisible to the traveler until the current ride is completed/cancelled.
    33. Once a ForRide/ForLyft request is accepted and the driver arrives 500m close to the traveler, 
        a) the traveler screen should display the name, photo of the driver, vehicle details (pic, vehicle registration no).
        b) the driver screen should display the name, photo of the traveler along with the option to enter OTP which will be forwarded by traveler.
    30. Once the OTP provided by the traveler is entered in the driver screen, the ride shall be considered as started.
    31. A driver/traveler shall be able to cancel his ride only before the start of the ride.
    32. During ride, the commercial traveler and driver shall be provided with the details of real time fare in their screen.
    33. The algorithm for fare calculation shall depend on the actual distance covered, time elapsed.
    34. Once the GPS coordinate of the traveler matches with the destination, a ride shall be considered complete.
    35. Post completion of ride the fare meter in the driver and the traveler screen shall freeze. The app shall provide option for payment of fare payment via Gpay or via cash.
    36. During the course when a ride is accepted and until it ends, the driver and the traveler shall be invisible to other users of the app in the map.
    37. Once a ride is completed, both the driver and the traveler shall be able to rate each other in a scale of 5. There shall be short comment text box for the traveler to enter reviews of his driver. The driver/traveler shall have option to share their rating and reviews in Facebook/Twitter with details of their ride.
    38. Both the driver and the traveler shall be able to view their ride history and make comments of each other. These comments shall be displayed in the profile of the driver and traveler.
    39. Once a ride is completed, a driver shall again become visible in the map.
    40. The app shall provide option for the driver to rest so that he becomes invisible from the map, yet he shall be able to view any available traveler requesting ride. 
    41. The app shall provide option for view and edit of individual profile.
    42. The app shall provide option for view ride history and making reviews of driver/traveler.
    43. The app shall have provision for making complaints, feedback to the administrator.
    44. If a traveler/driver makes a serious complaint about the driver/traveler including the following, the user may be banned from using the app using an automated process using ML algorithm
        a) Man handling
        b) Sexual assault
        c) Unfair Fare collection
    45. The administrator shall only have permission for banning any user.
    46. The administrator shall only have permission to enable any banned user.
    47. A separate desktop based dashboard shall be provide for control & monitoring the status of the app, users

Notifications
    1. Notification to be sent to a traveler (who has requested a ride) if any driver passes within 1km.
    2. Notification to be sent to a driver (who is ready to offer a ride) if any traveler passes within 1km.
