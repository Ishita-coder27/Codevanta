# CodeVanta – Real-Time Collaborative Coding Platform

A full-stack collaborative coding platform that enables multiple developers to code together in real time, communicate through integrated video calling, solve DSA problems, and manage coding sessions seamlessly.

Designed to replicate modern collaborative development environments while providing features useful for coding interviews, pair programming, mentorship sessions, and technical learning.

---

##  Overview

CodeVanta is a real-time collaborative coding platform built to enhance team-based programming and technical interview preparation.

The platform provides a shared code editor with live synchronization, session management, integrated communication tools, and a DSA problem bank. Multiple users can join the same coding session, collaborate simultaneously, discuss solutions through video calls, and track session history.

---

##  Key Features

###  Real-Time Collaborative Coding

* Shared live code editor
* Instant code synchronization
* Multi-user collaboration
* Pair programming support
* Live session participation

### Multi-Language Code Support

* Java
* C++
* Python
* JavaScript
* Additional extensible language support

###  WebSocket-Based Synchronization

* Real-time code updates
* Low-latency collaboration
* Shared editing experience
* Consistent editor state across participants

###  Session Management

* Create coding sessions
* Join existing sessions
* Session tracking
* Collaboration history
* Persistent room management

###  Video Communication

* Integrated WebRTC video calling
* Real-time discussion
* Technical interview simulation
* Pair programming communication

### DSA Problem Bank

* Curated coding problems
* Interview-focused challenges
* Problem-solving environment
* Practice-based learning

###  Learning & Interview Preparation

* Collaborative interview practice
* Technical discussion environment
* Peer learning
* Coding assessment preparation

---

## Tech Stack

### Frontend

* React.js
* JavaScript
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Real-Time Communication

* WebSockets
* Socket.IO

### Video Calling

* WebRTC

### Code Editor

* Monaco Editor

### Database

* MongoDB

### Version Control

* Git
* GitHub

---

##  System Architecture

User A
↓
React Frontend
↓
WebSocket Server (Socket.IO)
↓
Node.js + Express Backend
↓
MongoDB Database
↓
React Frontend
↓
User B

Video Communication:
User A ↔ WebRTC ↔ User B

---

##  Workflow

1. User creates a coding session.
2. Session link is shared with collaborators.
3. Multiple users join the room.
4. Monaco Editor loads shared workspace.
5. Code changes are synchronized via WebSockets.
6. Participants communicate through WebRTC video calls.
7. DSA problems can be solved collaboratively.
8. Session data is stored for future reference.

---

##  Project Outputs

### Output 1 – Home / Landing Page

<img width="1895" height="852" alt="image" src="https://github.com/user-attachments/assets/be82d223-4f30-4844-92ae-2eeac101c4c9" />

Show the landing page highlighting platform features, session creation, and user onboarding.

---

### Output 2 – Collaborative Code Editor
<img width="1237" height="579" alt="image" src="https://github.com/user-attachments/assets/daf4db6c-298f-4527-a5f2-d6b83c0f6499" />


Demonstrate the Monaco Editor with real-time code synchronization between multiple users.

---

### Output 3 – Session Creation & Joining

<img width="1219" height="539" alt="image" src="https://github.com/user-attachments/assets/d716ca28-4caa-415c-9958-000162afa92b" />

Display the interface for creating coding rooms and joining existing collaborative sessions.

---

##  Use Cases

### Technical Interview Preparation

Practice coding interviews with peers in a real-time environment.

### Pair Programming

Collaborate on coding problems and projects with shared editing capabilities.

### Mentorship Sessions

Mentors and learners can code together while discussing concepts live.

### Team Collaboration

Develop software collaboratively without requiring local setup synchronization.

---

##  Project Highlights

* Real-time collaborative coding platform
* Live synchronization using WebSockets
* Integrated WebRTC video communication
* Monaco-based professional code editor
* DSA problem-solving environment
* Session history management
* Multi-user coding support
* Full-stack architecture

---

##  Research Foundation

### Empirical Studies of Pair Programming (John Grundy, 2011)

Key findings supporting CodeVanta:

* Improves problem-solving ability
* Enhances code quality
* Reduces development errors
* Encourages collaborative learning
* Strengthens communication skills

These findings directly support the design philosophy behind CodeVanta's collaborative coding module.

---

##  Future Enhancements

* AI-powered code review
* Real-time code execution
* Integrated compiler support
* Interview analytics dashboard
* Collaborative whiteboard
* Screen sharing
* Coding contest mode
* Team workspace management
* AI interview assistant

---

##  Author

**Ishita Singh**

Software Engineer Intern | Full Stack Developer | Computer Science Undergraduate

GitHub Repository:
https://github.com/Ishita-coder27/Codevanta

---

## ⭐ Support

If you found this project useful, consider starring the repository and sharing feedback.
