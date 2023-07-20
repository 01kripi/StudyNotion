# StudyNotion - Interactive Ed-Tech Platform



StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS. StudyNotion aims to provide:

- A seamless and interactive learning experience for students, making education more accessible and engaging.
- A platform for instructors to showcase their expertise and connect with learners across the globe.

Visit the [StudyNotion Website](https://study-notion-1zo0g1qt2-01kripi.vercel.app) to explore the platform!

## System Architecture

The StudyNotion ed-tech platform consists of three main components: the front end, the back end, and the database. The platform follows a client-server architecture, with the front end serving as the client and the back end and database serving as the server.

## Front-end

The front end of the platform is built using ReactJS, which allows for the creation of dynamic and responsive user interfaces, critical for providing an engaging learning experience to the students. The front end communicates with the back end using RESTful API calls.

### Features:

The front-end includes various pages for different users:

#### For Students:

- **Homepage:** A brief introduction to the platform, with links to the course list and user details.
- **Course List:** Displays all available courses with descriptions and ratings.
- **Wishlist:** Shows courses added to the student's wishlist.
- **Cart Checkout:** Enables students to complete course purchases.
- **Course Content:** Contains course materials, including videos and related material.
- **User Details:** Displays student account details.
- **User Edit Details:** Allows students to edit their account information.

#### For Instructors:

- **Dashboard:** Provides an overview of the instructor's courses, ratings, and feedback.
- **Insights:** Offers detailed insights into the instructor's courses, including metrics like views and clicks.
- **Course Management Pages:** Allows instructors to create, update, and delete courses, manage content, and set prices.
- **View and Edit Profile Details:** Enables instructors to view and edit their account details.

## Back-end

The back end of the platform is built using NodeJS and ExpressJS, with MongoDB as the primary database.

### Features and Functionalities:

- **User Authentication and Authorization:** Secure sign-up and login with email and password. OTP verification and forgot password functionality for added security.
- **Course Management:** Instructors can create, read, update, and delete courses, and students can view and rate courses.
- **Payment Integration:** Payment processing through Razorpay for course purchases.
- **Cloud-based Media Management:** Cloudinary used for storing and managing media content like images, videos, and documents.
- **Markdown Formatting:** Course content stored in Markdown format for easier display and rendering on the front end.

## API Design

The StudyNotion platform's API is designed following the REST architectural style using Node.js and Express.js. It uses JSON for data exchange and supports standard HTTP request methods like GET, POST, PUT, and DELETE.

### Sample API Endpoints:

- POST /api/auth/signup: Create a new user account (student or instructor).
- POST /api/auth/login: Log in using existing credentials and generate a JWT token.
- POST /api/auth/verify-otp: Verify the OTP sent to the user's email.
- POST /api/auth/forgot-password: Send a password reset link to the registered email.
- GET /api/courses: Get a list of all available courses.
- GET /api/courses/:id: Get details of a specific course by its ID.
- POST /api/courses: Create a new course.
- PUT /api/courses/:id: Update an existing course by its ID.
- DELETE /api/courses/:id: Delete a course by its ID.
- POST /api/courses/:id/rate: Add a rating (out of 5) to a course.

## Deployment

The StudyNotion platform is deployed and hosted at [StudyNotion Website](https://study-notion-1zo0g1qt2-01kripi.vercel.app). The deployment process includes setting up a hosting environment and infrastructure to run the platform smoothly.

## Testing

Testing plays a crucial role in ensuring the platform's functionality, reliability, and security. Various types of testing are conducted, including unit testing, integration testing, and end-to-end testing. Test frameworks and tools are used to streamline the testing process.

## Future Enhancements

StudyNotion has exciting future enhancements planned to improve the platform further:

- Live virtual classrooms for real-time interactions between instructors and students.
- Gamification elements to increase engagement and motivation.
- Peer-to-peer learning and discussion forums.
- Support for multiple languages and localization.
- Enhanced analytics and data-driven insights for instructors and administrators.

These enhancements will be prioritized based on their potential impact, and a timeline will be estimated for their integration into the platform.

Thank you for exploring StudyNotion! For any questions or feedback, feel free to contact us. Happy learning!
