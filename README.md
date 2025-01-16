# Firebase Codelab: FriendlyChat

**Name:** MUHAMMAD MUKHRIZ ABADI BIN MUHAMAD REZAL
**Student ID :** 2023657294
**Group :** T5CDCS2703B2
**Lecture Name :** MUHAMMAD ATIF BIN RAMLAN

##Project Background : 

###Purpose
- The project is designed to teach how Firebase services can enhance web applications.
- It provides hands-on experience with Firebase tools, including Authentication, Firestore (database), Hosting, and more.

###Objective
- To build a fully functional web application that showcases Firebase's capabilities.
- Learn how to: 
  - Set up a Firebase project.
  - Use Firebase Authentication for user login and signup.
  - Store and retrieve data using Firestore.
  - Deploy the app to Firebase Hosting.

###Discussion : 
  The Firebase App Hosting lab exercise provided a hands-on experience with creating and deploying a web application using Firebase Hosting, a rapid and secure solution for both static and dynamic content. One of the main challenges I faced was making sure the Firebase and Angular CLIs were installed and launched properly in the appropriate file location. I had to fix a few permission and setup issues before I could get Firebase commands to work properly. I also had to handle the firebase.json and.firebaserc files with care to make sure the project structure and deployment parameters were set up correctly. One of the key takeaways from the exercise was the importance of the firebase init command, which helps create the configuration files needed to set up hosting. Additionally, the lab showed me how simple deployment involves using Firebase to distribute static files, such as HTML, CSS, and JavaScript, to a worldwide content delivery network. I gained useful experience working with several environments, including development and production, and how to efficiently transition between them by managing several projects on Firebase Hosting.

  A service called Firebase Authentication offers web and mobile applications reliable, secure, and simple user authentication. Numerous authentication methods are supported, such as phone numbers, email addresses, passwords, and third-party sources like GitHub, Facebook, and Google , but for my project I only use email addresses. With capabilities like session management and token-based authentication, Firebase Authentication improves security while expediting the user sign-in and sign-up process. In my experience, setting up user management in apps is more realistic when Firebase Authentication is used in a lab or project. Setting up Firebase in my project, adding the authentication SDK to your front-end code, and turning on authentication providers are usually the first steps in using Firebase Console. This enables developers to access user profiles, handle user statuses, and secure routes with efficiency. 

  In my FriendChat project, Firestore Database allowed me to track messages in real-time. Even if a message didn’t appear in the chat immediately, I could still check in Firestore to see whether it was sent or not. This real-time tracking was a helpful feature, but it also posed a challenge during development, as I had to ensure that the data was properly synced and displayed in the chat without delays. I had to troubleshoot issues related to data fetching and real-time updates, ensuring that messages appeared instantly across devices. Overall, Firestore made it easier to manage data consistency, but it required careful handling of asynchronous operations.

  Firebase's Cloud Storage SDK makes it easy for me to store and manage user-generated content like data in the cloud . With this SDK, I can easily upload and download files to and from Firebase's secure cloud storage, while benefiting from strong security features like Firebase Authentication. This ensures that so I  can only access my files, keeping everything safe and private. Even when working with big files. It supports asynchronous uploads and downloads, this means that my app can continue to run while files are being transferred. Additionally, the SDK allows for resumable uploads, so if a transfer is interrupted, it can pick up right where it left off without losing any progress. File permissions and security settings provide me a fine-grained control over who can upload or view specific files, making sure only the right people have access. While Firebase handles the heavy lifting of file storage, I still need to plan carefully when it comes to managing storage costs, as these can vary based on the number and size of the files being stored.

  Overall, the Firebase lab exercise provided a comprehensive and hands-on introduction to Firebase’s suite of services, including Firebase Hosting, Authentication, Firestore, Cloud Storage, and Performance Monitoring. Each service offered unique advantages and posed specific challenges. The experience gained from using these tools has enhanced my understanding of modern app development, real-time data synchronization, user authentication, and file management in cloud-based environments.

