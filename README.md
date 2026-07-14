# VinShare | Dream Together

**Created by Vinuthna Depala, Srihas Gupta, Isabella Wu, and Nisitha Sree Gadhi**

---

## What does our app do?

VinShare is a decentralized, anonymous creative vault where users share "fragments" of their imagination—be it digital art, voice notes, or stories—under a peaceful, starry night-themed interface. It allows users to build a personal "Vault" and discover the hidden dreams of others.

---

## What problem does it solve?

In a world of high-pressure social media, many creators feel hesitant to share unfinished ideas or raw "fragments" for fear of judgment. VinShare addresses this by providing a high-privacy, anonymous environment where the focus is on the creation, not the creator's identity.

---

## Why is it useful?

- **Creative Freedom:** Anonymous identities (like `StellarVoyager_4821`) allow for honest, raw expression without social pressure.  
- **Collaboration:** The built-in notification system allows makers to offer collaborations on fragments they find inspiring.  
- **Curation:** Users can "Save to Vault" pieces that inspire them, building a personal library of digital fragments.  
- **Multimodal:** Supports visual art, text-based stories, and audio/voice recordings in one unified grid.

---

## Who will benefit from it?

- **Artists & Writers:** Those looking for a low-stakes place to "dump" ideas and fragments.  
- **Collaborators:** Musicians looking for lyrics, or artists looking for stories to illustrate.  
- **Anyone needing a digital escape:** Users who want to browse a peaceful, aesthetic collection of human imagination.

---

## How did we come up with this idea?

We noticed that "finished" projects get all the attention, but the "fragments"—the sketches, the hummed melodies, the half-written poems—often stay hidden in a phone's camera roll. We decided to create a "Vault" specifically for these pieces, themed under a night sky to represent the quiet, reflective side of creativity.

---

## Instructions on how to run our project

1. Clone the repository from GitHub.  
2. Ensure all three files (`index.html`, `style.css`, `script.js`) are in the same folder.  
3. Open `index.html` in any modern web browser.  
4. **Note:** For the full experience (including uploads), use a local server like VS Code's "Live Server" extension to handle the API calls correctly.

---

## Tech Stack & Code Structure Overview

- **Frontend:** HTML5, CSS3 (Custom properties & Animations), Vanilla JavaScript  
- **Backend-as-a-Service:** Supabase (Authentication, PostgreSQL Database, and Storage Buckets)  

### Libraries/Tools:
- **Supabase JS Client:** For real-time data fetching and file uploads  
- **Google Fonts:** 'Fredoka' and 'Nunito' for a soft, approachable UI  
- **FontAwesome / Emoji:** For intuitive, lightweight iconography  

---

## Key Features

- **Pinterest-Style Grid:** A responsive layout that dynamically adjusts to different fragment sizes  
- **Anonymous Identity System:** Automatically generates unique, celestial-themed names for every user  
- **Media Hosting:** A robust upload system that handles local files and converts them to permanent cloud URLs  
- **Real-Time Notifications:** A background polling system that alerts you to new collaboration offers instantly  

---

## Future Improvements

We’re excited to add more "magic" to the Vault:  

- **Audio Visualizers:** Real-time wave effects for voice fragments using the Web Audio API  
- **Fragment Remixing:** A feature allowing users to directly branch or "remix" a fragment into a new one  
- **Nested Vaults:** Organization folders for users with large collections  
- **Night-Sky Customization:** Allow users to earn "stars" for their sky based on community engagement  

---

## Challenges We Faced

- **File Upload Logic:** Managing the transition from a local file to a Supabase Storage bucket and then linking that URL back to a database row  
- **UI Persistence:** Ensuring the "Notification Bell" and "My Profile" buttons appeared and stayed active correctly across different login sessions  
- **Anonymous UX:** Balancing the need for user accounts (for security) with the desire for total anonymity  
- **Real-time Polling:** Implementing a notification system that feels live without overloading the database  

---

## Acknowledgements

A HUGE thank you to the Supabase team for their incredible documentation. We are also grateful for the open-source community that makes building modern web apps accessible to everyone.

---

## Conclusion

VinShare is more than just a gallery; it’s a sanctuary for the unfinished and the unpolished. By removing the pressure of identity, we aim to make the internet a little more imaginative, one fragment at a time.  

**Thank you for exploring our Vault!**

