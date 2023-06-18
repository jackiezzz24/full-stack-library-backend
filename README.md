# Full Stack Library Management Application - Back End

+ Designed a Full Stack library management application enabling users to search books by title and category, checkout and give star reviews. Administers can manage book information, receive, and reply to messages.  
+ Assembled interactive functions and callbacks with React and TypeScript in frontend and the backend utilizing Spring Boot and Java.
+ Applied Spring Data JPA for data’s access layer and leveraged Apache Maven for project management.
+ Aggregate data based on business logic and persisted results into MySQL to support downstream clients.
+ Integrated login/logout features with JWT, OAuth2 and OpenID Connect to handle user roles with limited access.

## App Screenshots
### `Main page`
Main page without login\
![Capture](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/f2a937c5-6338-4240-a359-ca9ebe36a400)

The NavBar would be changed after login as user or admin: 
+ Login as user 
![Capture](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/f8687d30-9734-4eca-95ea-9d8016c19681)
+ Login as admin
![Web capture_11-5-2023_145058_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/c0fbf204-0bdf-4131-aea5-fdb7a428c9f5)

### `Login page`
![Web capture_11-5-2023_144525_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/c5cd4eae-5ba6-40e3-a8c2-637695cb5129)

### `Search book page`
Users can use pagination to browse the book inventory.\
![Capture](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/818d44fd-03d2-4687-bb8a-35a6a1092e59)

### `Book page`
Users can checkout the selected book and leave a reivew for the book in the book page.\
![Web capture_11-5-2023_144728_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/e1c0c2f8-ec7b-4738-ba83-61ba4492e58d)
![Web capture_11-5-2023_144749_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/ef403193-e5ba-474b-8b02-8b68b99309c1)
![Web capture_11-5-2023_144812_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/68ae70bf-9368-4d40-8e5a-79fda6d74e92)

### `Shelf page`
Each user can checkout five books. Users can review the checked out books in the Shelf page.\
Users can manage the loan, return books or renew the loan in this page.
![Web capture_11-5-2023_144844_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/8f268729-8e67-4786-8e62-ba656abfb0b6)
![Web capture_11-5-2023_144925_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/e4354816-caf8-4577-aab3-a898e0159d84)

### `History page`
Users can view all the book histories.\
![Web capture_11-5-2023_144950_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/6c6ec42d-7144-430b-bb7c-898669dad6ef)

### `Payment page`
If uses have oustanding payments due to past due, they can check payment amount in this page.\
Users cannot checkout any books until the outstanding payments is paid.\
![Web capture_11-5-2023_145013_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/6f9d143d-a804-407a-8a21-21f7e92684b6)

### `Message page`
Users will be redirect to Message page by clicking the "Library Service" button in the main page after login. \
![Capture](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/8958c6a5-1c05-46f1-b2bc-f65849007ad4)

Users can submit questions to the administration.\
![Web capture_11-5-2023_16257_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/6b25d7dc-dd60-4e78-b9f4-5cb995a3803d)
![Web capture_11-5-2023_16316_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/8a6d3445-fb26-4706-886e-2d552329c16e)


### `Admin page`
If users login as admin, they add new books in the library system, edit current book inventory and reply customers inquiries. \
![Web capture_11-5-2023_145111_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/6cf89379-ed5a-4455-8b6b-35d387b64a65)
![Capture](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/d2bb8771-c176-418e-89e5-2dfef738e803)
![Web capture_11-5-2023_145159_localhost](https://github.com/jackiezzz24/full-stack-library-frontend/assets/99145834/3068bd5d-4fcd-4f7b-afc1-573502ed3482)
