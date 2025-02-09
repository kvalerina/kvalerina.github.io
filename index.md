---
layout: default
title: Modernist Theme Test
---

# <span style="color:#1773a0; font-size:1em;">Introduction</span> <br>
<p style="font-size: 1.2em; text-align: justify;">
Hello my name is Karina Aronov. I started at SNHU June 2022 and began the Computer Science Program August 2023. This portfolio is to showcase my skills for my Capstone Project and enhancements that demonstrate my growth as a developer. My preferred area of specialization is App Development. Here you'll find a detailed look at my work, including the enhancements of an Event Planning app I originally built for my CS360 Mobile Architect & Programming class, that demonstrates Software Design and Engineering, Algorithms and Data Structure, and Databases. 
</p>

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
- <a href="https://github.com/kvalerina/kvalerina.github.io/blob/main/Enhancement%203.zip" target="_self"><b>Enhancement Three: Databases</b></a> <br>

# <span style="color:#1773a0; font-size:1em;">Professional Self-Assessment
<p style="font-size: 1.2em; text-align: justify;">
</p>
