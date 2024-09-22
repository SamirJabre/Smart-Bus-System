<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> A smart transportation system designed to optimize bus transportation by providing real-time tracking, route optimization, and passenger management. This platform offers an enhanced commuting experience by ensuring efficiency and convenience for both passengers and bus operators.
>
> The IoT-Based Smart Bus Transportation System aims to transform public transportation by integrating IoT devices and smart technology. Users can track buses in real time, get optimized routes, and manage passenger loads. This project focuses on improving operational efficiency and passenger experience through automation and real-time data.

### User Stories

#### Customer
- As a customer, I want to view the real-time location of the bus, so I can know where I am exactly.
- As a customer, I want to know the estimated arrival time of the buses, so I can know when I'm possibly arriving.
- As a customer, I want to purchase digital tickets, so I can board the bus without needing cash or a physical ticket.

#### Driver
- As a driver, I want to update real-time location, so customers can see where they are.
- As a driver, I want to log my working hours, so I can keep track of my shifts.
- As a driver, I want to scan customers QR code, so I check if the customer is in the right trip.

#### Admin
- As an admin, I want to make trips and organize the buses schedules, so I can ensure timely service.
- As an admin, I want to check drivers applications, and choose whether to approve or reject the driver.
- As an admin, I want to manage user accounts, so I can keep track of active customers.

<br><br>
<!-- Tech stack -->
<img src="./readme/title3.svg"/>

###  iBus is built using the following technologies:

- Frontend: The mobile app uses React Native to provide a cross-platform experience on both iOS and Android devices. React Native allows us to create a highly interactive and user-friendly interface with a single codebase
- Backend: The backend API is developed using Laravel, a robust PHP framework that provides RESTful API endpoints for managing data and handling requests efficiently.
- Database: For persistent storage and efficient data management, the project utilizes MySQL. MySQL handles all the backend data operations, including user data, bus schedules, and real-time tracking information.
- Real-time Communication: The application uses Socket.io to provide real-time updates for bus locations, route changes, and passenger notifications, ensuring users receive up-to-date information instantly.
- IoT Integration: The system integrates with various IoT devices such as GPS modules for real-time location tracking, passenger load sensors for monitoring bus capacity.
- For Admin Panel: The admin panel is made with React js specifically for admins.

<br><br>
<!-- UI UX -->
<img src="./readme/title4.svg"/>


> We designed iBus using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/ipjDqjMgkYGaluOob6EjFh/iBus?node-id=0-1&t=0MmCr4qldXY9ofRe-1)


### Mockups
| Home screen  | Search Screen |
| ---| ---|
| ![Landing](./readme/demo/Home2.png) | ![Search](./readme/demo/Search2.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

###  Architecting Data Excellence: Innovative Database Design Strategies:

- <img src="./readme/demo/ERD.png"/>


<br><br>


<!-- Implementation -->
<img src="./readme/title6.svg"/>


### User Screens (Mobile)
| Landing screen | Register screen | Login screen |
| ---| ---| ---|
| ![fsdaf](./readme/demo/LandingPage.png) | ![fsdaf](./readme/demo/Register.png) | ![fsdaf](./readme/demo/Login.png) |

| Trips screen | Home screen | Search Screen |
| ---| ---| ---|
| ![fsdaf](./readme/demo/Trips.png) | ![fsdaf](./readme/demo/Home2.png) | ![fsdaf](./readme/demo/Search2.png) |

| Bus Screen | Booking Screen | Profile Screen |
| ---| ---| ---|
| ![fsdaf](./readme/demo/Bus.png) | ![fsdaf](./readme/demo/Booked.png) | ![fsdaf](./readme/demo/Profile.png) |

### Driver Screens (Mobile)
| Landing screen  | Login screen | Application screen |
| ---| ---| ---|
| ![fsdaf](./readme/demo/DriverLandingPage.png) | ![fsdaf](./readme/demo/DriverLogin.png) | ![fsdaf](./readme/demo/DriverForm.png) |

| Trips screen | Trip Info screen |
| ---| ---|
| ![fsdaf](./readme/demo/DriverTrips.png) | ![fsdaf](./readme/demo/DriverTripInfo.png) |


### Admin Screens (Web)
| Login screen  | Dashboard screen |  Users screen |
| ---| ---| ---|
| ![Landing](./readme/demo/AdminLogin.png) | ![fsdaf](./readme/demo/AdminDashboard.png) | ![fsdaf](./readme/demo/Users.png) |
| Trip Making screen  |
| ![Landing](./readme/demo/AdminTripMaking.png) |

<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  Intelligent Transportation Assistant: Enhancing the User experience of Public Tranporation:

- This project leverages cutting-edge IoT integration and data management techniques to enhance the experience of public bus transportation users.

###  Smart Assistant with OpenAI Propmt:

- <img src="./readme/demo/prompt.png"/>


<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

###  Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

###  Ensuring Backend Integrity: The Role of Unit Testing

- Backend Testing:

- This project integrates comprehensive unit testing protocols to validate the functionality of backend components. By isolating and testing each unit, we mitigate risks, enhance code reliability, and ensure the backend operates seamlessly under various conditions. This approach allows for early detection and resolution of issues, reinforcing the system's stability.

###  Test Samples

<img src="./readme/demo/test1.png"/>


<img src="./readme/demo/test2.png"/>

<br><br>


<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up iBus locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/your_username_/Project-Name.git)
3. Install NPM packages
   ```sh
   npm install
   ```
4. Install Expo packages
   ```sh
   npx expo install
   ```
5. To run the app
   ```sh
   npx expo start
   ```

Now, you should be able to run iBus locally and explore its features.