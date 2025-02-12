---
layout: default
title: Modernist Theme Test
---

# <span style="color:#1773a0; font-size:1em;">Introduction</span> <br>
<p style="font-size: 1.2em; text-align: justify;">
Hello my name is Karina Aronov. I started at SNHU June 2022 and began the Computer Science Program August 2023. This portfolio is to showcase my skills for my Capstone Project and enhancements that demonstrate my growth as a developer. My preferred area of specialization is App Development. Here you'll find a detailed look at my work, including the enhancements of an Event Planning app I originally built for my CS360 Mobile Architect & Programming class, that demonstrates Software Design and Engineering, Algorithms and Data Structure, and Databases. <br>
</p>

# <span style="color:#1773a0; font-size:1em;">Professional Self-Assessment
<p style="font-size: 1.2em; text-align: justify;">
During my time in SNHU's Computer Science program, I have acquired a range of knowledge and useful skills that have influenced my career goals and prepared me for success in the tech industry. While this ePortfolio enables me to demonstrate my growth as a developer, the material has given me a strong foundation in computer science fundamentals. The combination of coursework, hands-on projects, and the development of this ePortfolio has given me the tools to pursue a career in software development.
<br><br>
Completing my coursework has been monumental in helping me improve my technical skills. For example, through my work on projects such as the Event Planning app, I’ve gained valuable experience in database management and software engineering. I initially started with Java and later transitioned to Kotlin, which helped me understand the importance of modern, efficient coding practices. I also had the opportunity to dabble in cloud technologies like Firebase, which not only improved the functionality of my app but also expanded my understanding of cloud-based solutions and real-time data synchronization. These experiences have strengthened my problem-solving abilities and prepared me for real-world software development challenges.
<br><br>
I have gained strong collaboration skills through online discussion board posts and real-world work experiences. I was able to ask questions, understand technical concepts, and help others in solving challenging issues on the discussion boards. Outside of school, I’ve had opportunities to work in groups in professional settings, where I collaborated with teammates on various projects, exchanging ideas and solving challenges together. I learned from these experiences how to listen to different viewpoints, communicate clearly, and play to each team member's strengths.
<br><br>
Software engineering has taught me how to efficiently manage the software development lifecycle, which includes gathering requirements, creating solutions, and producing maintainable code. Additionally, I have developed skills in working with version control systems like Git, debugging, and unit testing. These skills have been important in ensuring the success of projects and preparing me to work on more complex projects in the future.
My ability to develop code that is effective has been enhanced by my education in data structures and algorithms. I now know more about how to tackle complex computational tasks such as sorting algorithms to understanding how various data structures, such as trees, graphs, and arrays, can be utilized to solve problems effectively. My work on algorithmic problems has taught me how to choose the right approach for different problem sets.
<br><br>
Another important area of focus in my project has been database management. I've worked with Firebase and SQL databases to manage user data effectively and safely. I was able to successfully switch from a local SQLite database to Firebase Firestore for my Event Planning app project, which enhanced scalability and enabled real-time data updates. I've also learned how to check user input, create secure login systems, and protect sensitive data from vulnerabilities, all of which are critical components of modern software development.
<br><br>
Making my ePortfolio allowed me to reflect on my achievements, highlight areas for development, and highlight my professional goals. As I move forward, I am confident that the skills and knowledge I’ve gained will allow me to excel in the tech industry. My goal is to continue to grow as a developer, contribute to impactful software projects, and eventually specialize in areas like mobile app development and cloud technologies. I look forward to utilizing my expertise and abilities as I enter the workforce and continue to develop innovative solutions in the ever-evolving field of computer science.

</p> <br>

# <span style="color:#1773a0; font-size:1em;">Description of the App</span> <br>
<p style="font-size: 1.2em; text-align: justify;">
The Event Planning App is a mobile application designed to help users manage and organize their events efficiently. This app has evolved significantly since it's original implementation, through enhancements focused on improving functionality, security, and user experience. Originally written in Java, the app has been converted to Kotlin, leveraging modern language features like null safety, concise syntax, and improved maintainability. The app allows users to perform essential tasks such as creating, updating, and deleting events, with data stored securly in Firebase. <br>
</p>

<p style="font-size: 1.2em; text-align: justify;">
Enhancements have been made to ensure the app not only functions as expected but also adheres to industry standards for software design, database management, and user experience. The app has been improved by transitioning from a single, ongoing list of events to separate daily and monthly views, providing users with more organized and intuitive access to their schedules. Integrating Firebase for real-time data synchronization and adding advanced features like event prioritization and filtering, will take the app’s functionality to the next level. This app showcases my ability to develop and enhance mobile applications while demonstrating skills in software engineering, UI/UX design, and database management. It serves as a reflection of my growth as a developer and my dedication to creating user-centered, secure, and maintainable solutions.
</p>

# <span style="color:#1773a0; font-size:0.8em;">Repository Link <br>
- <a href="https://github.com/kvalerina/kvalerina.github.io/blob/main/Enhancement%201.zip" target="_self"><b>Original Code</b></a> <br>

# <span style="color:#1773a0; font-size:1em;">Code Review</span> <br>
<div style="display: flex; justify-content: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/zeWQIATf0QI?si=LYLm3LlUChoxMCWU" 
        title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; 
        encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
    </iframe>
</div>
<br>

# <span style="color:#1773a0; font-size:1em;">Enhancement One</span> <br>
<p style="font-size: 1.2em; text-align: justify;">
I enhanced the app by improving database management, input validation, security, UI/UX, exception handling, and overall code quality. While SQLite was used for local storage, groundwork was laid to migrate to Firebase for real-time capabilities. I added robust validation for user credentials and event details to ensure proper input formatting and secure data storage by switching to EncryptedSharedPreferences. UI feedback was improved by replacing toast messages with snackbars for better visibility, and comprehensive error handling was introduced to prevent crashes and provide clear messages for issues. The transition from Java to Kotlin modernized the codebase, making it more concise and maintainable. This process taught me the importance of balancing security, usability, and maintainability while adapting to new technologies. <br>
</p>

# <span style="color:#1773a0; font-size:0.8em;">Repository Link <br>
- <a href="https://github.com/kvalerina/kvalerina.github.io/blob/main/Enhancement%201.zip" target="_self"><b>Enhancement One: Software Design and Engineering</b></a> <br>

# <span style="color:#1773a0; font-size:1em;">Enhancement Two <br>
<p style="font-size: 1.2em; text-align: justify;">
One of the biggest improvements I made to my Event Planning app was refining how events are displayed. Before, everything was cluttered together, making it hard to see what was actually scheduled. Now, there’s a daily view that shows only the current day's events and a monthly view that lets users browse their schedule at a glance. To prevent any confusion, I added a "No Events Scheduled" message so users aren’t left wondering if something is broken. I also introduced sorting options that let users organize events by time or priority, ensuring that the event list updates in real time when a sorting option is selected. The search function got a big upgrade too—it now includes all events, allowing users to quickly find what they’re looking for without endless scrolling. To keep things clean, I rearranged the UI, placing the sort and search functions together, adding a footer button for easy monthly view access, and removing unnecessary files like GroupedEventAdapter and event_group_card.xml.
<br> <br>
A small but meaningful change was adding a dynamic greeting message at the top of the daily view, which greets users with "Good morning," "Good afternoon," or "Good evening," based on the time of day. To make it more personal, the app pulls the correct logged-in username instead of using a generic placeholder. Getting all the popups and dropdowns to function properly took some extra work, but now everything—searching, sorting, navigation, and popups—is smooth and intuitive. This enhancement really strengthened my skills in algorithms and data structures, especially when it came to organizing event data, implementing real-time sorting, and making sure the app’s features were both functional and user-friendly.
</p> <br>

# <span style="color:#1773a0; font-size:1em;">App Review</span> <br>
<div style="display: flex; justify-content: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/nJ9i_YvmYKk?si=HH3r-GVpTQ6eKF8W" 
        title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; 
        encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<br>

# <span style="color:#1773a0; font-size:0.8em;">Repository Link <br>
- <a href="https://github.com/kvalerina/kvalerina.github.io/blob/main/Enhancement%201.zip" target="_self"><b>Enhancement Two: Algorithms and Data Structures</b></a> <br>

# <span style="color:#1773a0; font-size:1em;">Enhancement Three <br>
<p style="font-size: 1.2em; text-align: justify;">
Moving the database to Firebase highlights my skills in working with modern, cloud-based technologies and improving the app’s functionality. By incorporating Firebase Firestore and Firebase Authentication, I’ve enhanced the app’s data handling and security, which are important aspects of software development. Firebase Firestore enables seamless, real-time synchronization of data, so users can access their event information from multiple devices simultaneously, without delay. Firebase Authentication ensures that user data is protected with secure login processes, which was important for ensuring the safety of personal information. The app has been improved by streamlining the data storage process and eliminating the need for local storage management With Firebase, I was able to create a more flexible and scalable app that not only meets the needs of individual users but also has the capability to handle a larger user base and accommodate future growth. The cloud-based architecture provides better performance and eliminates the limitations of traditional local storage, making the app more efficient and user-friendly.
</p> <br>

# <span style="color:#1773a0; font-size:0.8em;">Repository Link <br>
- <a href="https://github.com/kvalerina/kvalerina.github.io/blob/main/Enhancement%203.zip" target="_self"><b>Enhancement Three: Databases</b></a>
