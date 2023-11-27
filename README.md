# **Patrick Apilukpuvadol and Francis Lam T3A1**
********************************
## **Travelling Diary: MERN full-stack app assignment**
*****************************************



****************

### Purpose

Our Client wanted to establish a full stack web application, the web app will serve 2 main purposes. First purpose is to allow users to log and share their experiences from their travels. Second purpose is allow client to login and manage the content of the posts. 

The client wanted to establish this platform to create a niche and target a consumer base that has a strong focus on travel experiences and tips. The client realised that although there is social media applications and booking web applications that allow users to post content about where they have travelled, there was no application available that essentially combined the features of both with a focus on experiences and tips for other users. The client wanted to establish this app to allow users to be able to effectively search for unique experiences posted by others with a sole focus on travel instead of either just scrolling through all the other content of social media apps or search for destinations with no prior knowledge provided that allows them to make the most of their trip. 

*********

#### Target Audience

This application is targeting Young adults up to Parents with different reasons and budgets for travel. 

#### User Stories

##### Market Research

1. As a user, I want to be able to view detailed information about each travel destination, including photos, descriptions, and comments, so that I can make informed decisions about where to go.

2‌. As a user, I want to be able to search for specific travel destinations or blog posts so that I can quickly find the information I need.

‌3. As a user, I want to be able to create an account and log in so that I can access personalized features and save my preferences.

4‌. As a user, I want to be able to create and edit my own blog posts to share my travel experiences and tips with others.

‌5. As an administrator, I want to be able to manage user accounts, including approving new registrations and enforcing security measures.

6‌. As a developer, I want to ensure that the website is responsive and mobile-friendly, so that users can access it from any device.

7‌. As a developer, I want to implement a secure authentication system to protect user accounts and sensitive data.

#### Iterated Personas of Target Users

**Persona 1: Adventurous Alan**

Age: 33

Occupation: Software Engineer

Interests: Traveling, outdoor activities, photography

Background: Alan is a passionate traveler who loves exploring new places and documenting his experiences through photos. He enjoys trying out adventurous activities like hiking, scuba diving, and skydiving. As a software engineer, he appreciates well-designed and user-friendly websites and apps. Alan is always on the lookout for travel blogs that provide detailed itineraries, tips, and stunning visuals to inspire his next adventure.

**Persona 2: Wanderlust Wendy**

Age: 25

Occupation: Digital Nomad

Interests: Traveling, blogging, remote work

Background: Wendy is a digital nomad who works remotely while traveling the world. She enjoys immersing herself in different cultures, trying local cuisines, and meeting new people. Wendy is passionate about sharing her experiences through her travel blog, and she is always in search of new destinations and hidden gems to write about. She values web applications that offer a seamless user experience and provide valuable information about travel destinations, accommodations, and transportation.

**Persona 3: Budget Traveler Ben**

Age: 18

Occupation: Student

Interests: Traveling on a budget, backpacking, local experiences

Background: Ben is a student who loves traveling during his breaks. He often travels on a tight budget and looks for affordable accommodations, transportation options, and local experiences. He enjoys exploring off-the-beaten-path destinations and interacting with locals to get a true taste of the culture. Ben relies on travel blogs to find tips and tricks for budget travel, including suggestions for cheap eats, free attractions, and affordable accommodations.

**Persona 4: Family-oriented Fiona**

Age: 45

Occupation: Stay-at-home mom

Interests: Family-friendly travel, kid-friendly activities, family accommodations
Background: Fiona is a mom of two young children who loves traveling with her family. She looks for destinations that offer a range of family-friendly activities and accommodations. Fiona values travel blogs that provide recommendations for attractions suitable for kids, tips for traveling with children, and advice on finding family-friendly accommodations. She wants to ensure her family has a memorable and enjoyable travel experience while keeping everyone's needs in mind.

*********

#### Functionality/ Features

The Full stack application will be have a variety of features specifically for two groups. The User and the admin staff managing the application. Features will be as follow:

**All Users:**
The application will be protected and will require all users to login via authentication which will assign them the appropiate permissions such as user and admin. Users will be prompted to create an acount through the web application while admin users will need their accounts established by the assign data manager. 
- Login
- Logout

**Users**
When authenticated, users are allowed to access their personalised Dashboard that will feautrem recommended blogs and experiences based on their preferences and interests. 
- Create an Account 
- Display their content
- Edit their content
- Delete their content
- View other users' content
- Like/Unlike users' content
- Comment on users' content
- Follow/Unfollow users

**Admin** 
Once the Admin has been provided with credentials that grant them permissions and access to manage content as required for their role 
- Create/Delete/Edit/View Users
- Create/Delete/Edit/View Users' Content
- Manage User permissions
- Moderate content

****************
#### Planning (Sprints)

At the beginning of the project we had a briefing to delegate tasks and design a rough idea of how the app works. We then used Trello as a workload planner to organise and prioritise taks. We were responsible for ensuring that we completed appointed tasks in a timely manner and ensured we added notes to encourage communication during our regular meetings. We will hold regular status meetings through discord to communicate any issues and challenges we encounter during this project. 

With planning initially we plan to have the sprint organised in weekly sprints 

**Week 1**
- Implementation and establishment of Front-end and Back-end
- Establish login functionality for Users and Admin
- Integrate Amazon S3 functionality

**Week 2**
- Program CRUD functionality for both Users and Admin
- Integrate Google API functionality
- Integrate Personalised Dashboard for users 

**Week 3**
- Testing of code
- Front end cleaning up and testing for responsiveness
- Final touches before launch

Currently we have the Trello Screenshots for plannaing stage of MERN stack web application (see below)

<img src="wk2.png" alt="Beginning Trello" />

<img src="wk 3.jpg" alt="Ending Trello" />

***************

#### Workflow

We decided to work as a team within a Github Organisation and utlise forking to maintain integrity of version control. This will allow us to monitor changes made by team members effectively. We will be checking each of the pull requests to the main branch. We believe this will be the best approach to working in an agile project environment with team members working across on different aspects of the web application. Most tasks will be completed alone by each team member so this branching and pull requests will allow other team member to keep track of other's work. 

#### Dataflow Diagram

<img src="Data-Flow-Diagram.jpg" alt="Data Flow Diagram" />

****************

#### Application Architecture Diagram

<img src="Application-Architecture-Diagram.jpg" alt="alt text" title="Application Architecture Diagram" />

****************


## Technologies Used

- MongoDB: NoSQL database for storing user and travel log data.
- Express: Node.js framework for building the server-side API.
- React: Frontend library for building the user interface.
- Node.js: JavaScript runtime environment for server-side development.
- Redux: State management library for managing application state.
- Axios: HTTP client for making API requests.
- Other dependencies: Refer to the `package.json` files in the `server` and `client` directories for a full list of dependencies used.