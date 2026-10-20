STUDYMATE FULL FRONT-END PROTOTYPE
=================================

FILES
- index.html: app structure and account screens
- style.css: responsive styling
- app.js: demo interactions and local browser data

HOW TO RUN
1. Extract the ZIP.
2. Open index.html in a browser, or deploy the folder to Netlify.
3. Create a demo account with parent/guardian phone numbers including country code.
4. Use the sidebar to test dashboard, timetable, subjects, practice, weekly tests, AI doubt demo, My Progress, Parent Access, and Settings.

IMPORTANT LIMITATIONS
- This is a functional front-end prototype. Account data is stored in localStorage in the current browser only.
- Do not use a real/reused password or sensitive real student data in this prototype.
- It does not provide secure production authentication, a cloud database, real AI answers, or real parent account linking.
- WhatsApp invitations open a pre-filled wa.me chat for the user to review and manually send. No messages are sent automatically.
- Parent/guardian numbers are personal data. Obtain permission, explain the purpose, and protect them. For production, use a secure backend, consent controls, authentication, authorisation, and appropriate data protection.
- The current weekly test and scheduler are demonstrations; align them to the correct board/class syllabus before launch.
- IQ-based scheduling is not implemented. The app's intended direction is academic diagnostic and topic-mastery based scheduling.

DEPLOY TO NETLIFY
Drag the extracted folder contents into a Netlify manual deploy, or connect the project folder/repository. For real backend features, add serverless functions and secure database/authentication. See official Netlify Functions docs:
https://docs.netlify.com/build/functions/get-started/
