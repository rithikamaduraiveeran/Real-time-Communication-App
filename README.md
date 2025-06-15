# Real-time-Communication-App

Start Page (start.html)

The start.html file is the welcome or landing page of the Real-time Communication App. In my vision, this page serves as the user's first interaction point with the platform. It is designed to be clean, minimalistic, and easy to navigate. The core idea behind this page is to let users decide whether they want to create or join a communication room. I structured this page using HTML and added stylistic elements through CSS to make it visually appealing.

From my point of view, the most important function of a start page is to direct users to the next step in a straightforward manner. I included buttons like "Start Communication" or “Join Room” that redirect users to the respective pages. While building this, I learned how to keep a page both functional and visually balanced. I didn’t overload it with too many options but instead kept the layout simple, with clear call-to-action buttons and short guiding texts.

Another thing I focused on was responsive layout so that this page would look fine on both desktop and mobile screens. I used flexible widths, proper padding, and centered alignment to achieve this. This is essential in any real-time app because users often access such platforms from different devices.

Although no backend logic is present, this static version of start.html works perfectly as the initial screen of the communication flow. Later on, when integrated with JavaScript and WebRTC, this page could include authentication logic or session ID generation. This file helped me understand how to build a gateway for real-time applications and design a user journey that starts simply but can grow in complexity.

Join Room Page (join.html)

The join.html file is one of the core components of this Real-time Communication App. From my perspective, this page represents the transition from the general interface into the active real-time environment. Users enter this page to join a specific communication room, often by entering a room ID or link. I created this page using HTML and styled it using CSS to ensure a clean and professional layout.

The main element on this page is a form input where users can type the room ID or name. Alongside that, I added a button labeled “Join Now” to simulate entering a call. While this functionality isn’t yet linked to a real communication engine like WebRTC, I built the structure such that it can be easily integrated in future stages. The idea was to imitate what users see in real-time platforms like Google Meet or Zoom, where they input meeting codes to join.

From a design point of view, I made sure the layout is responsive and the user’s attention is focused on the joining action. I learned the importance of user flow and how reducing visual distractions helps in decision-making. I also added space for error messages or success confirmations, which I plan to link with JavaScript validation later.

Working on this page taught me how critical joining logic is in a real-time app. Even though this version is static, it gave me the foundation to later build dynamic room-joining functionality using Firebase or WebSocket-based signaling servers. Overall, join.html captures the essence of connecting people and helps simulate the beginning of a communication session — a fundamental step in any real-time system.

Profile Page (CommProfile.html)

The CommProfile.html file functions as the user profile page in the Real-time Communication App. From my point of view, every app that involves interaction should have a profile section where the user can view or manage their identity. I structured this page using HTML to present basic information such as profile name, avatar section, communication history placeholder, and customizable details. While it's a static layout, it plays a key role in personalizing the user experience.

This page helped me practice layout alignment and clean sectioning. I used CSS to organize the layout into blocks — profile image on top, user name and bio underneath, and communication data (like past sessions or status) in another section. Even though there’s no back-end, I designed this page as if it would later connect to a real-time database, pulling actual user data dynamically.

The experience of building this file helped me focus on user-centric design. I made sure the font size was readable, the profile image was clearly visible, and edit buttons or icons were easy to find. This is very important for platforms where users rely on visual clarity for quick updates and actions.

In future versions, I plan to add JavaScript to allow real-time profile editing or viewing other users' profiles during a call session. This would make the communication app feel more personal and connected. Even though this is a mock-up now, CommProfile.html reflects how I approached front-end design with future scalability in mind.

Overall, this file was essential for me to understand how user identity is displayed and managed in a UI. It adds a personal dimension to the otherwise technical flow of real-time communication.
