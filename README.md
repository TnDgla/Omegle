### **Project Name: Google  Meet Clone**

The **Google Meet Clone** is a real-time video chatting application built using **WebRTC, React, Node.js, and Socket.IO**. It connects random users for one-on-one video calls, simulating the functionality of Omegle. The project demonstrates the use of peer-to-peer communication protocols and modern web technologies.

---

### **Mission and Objectives**

---

#### **Mission:**
To create a peer-to-peer video communication platform that allows random connections between users, showcasing WebRTC and real-time communication capabilities.

#### **Objectives:**
1. **Random User Connection:**
   - Match users randomly for video calls.
   - Ensure connections are established seamlessly.

2. **Real-Time Communication:**
   - Implement WebRTC for direct peer-to-peer communication.
   - Use Socket.IO for signaling and room management.

3. **Responsive Design:**
   - Ensure the platform works on both desktop and mobile devices.

4. **Scalability:**
   - Support multiple rooms with isolated connections.

5. **Deployment:**
   - Deploy the application on cloud platforms for public access.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**
   - **Why?**: Simplifies building dynamic user interfaces.
   - **Use Case**: Manages the video interface, room navigation, and user interactions.

2. **CSS Modules**
   - **Why?**: Enables scoped styling for components.
   - **Use Case**: Styles the layout and elements of the application.

#### **Backend**
1. **Node.js**
   - **Why?**: Provides an efficient runtime for building scalable server-side applications.
   - **Use Case**: Manages signaling servers and API endpoints.

2. **Express.js**
   - **Why?**: Simplifies API routing and server logic.
   - **Use Case**: Defines endpoints for signaling and communication.

3. **Socket.IO**
   - **Why?**: Facilitates real-time, bidirectional communication.
   - **Use Case**: Handles signaling for WebRTC connections and user matching.

#### **WebRTC**
- **Why?**: Enables peer-to-peer communication directly between browsers.
- **Use Case**: Handles video and audio streams between connected users.

#### **Database**
- **In-Memory Data Structures** (e.g., Arrays)
  - **Why?**: Temporary storage for active users and room information.
  - **Use Case**: Maintains the list of users waiting to connect and active room details.

#### **Deployment**
1. **Frontend Hosting:** Netlify or Vercel
   - **Why?**: Optimized platforms for React app hosting.
   - **Use Case**: Deploys the client-side application.

2. **Backend Hosting:** Heroku or AWS
   - **Why?**: Reliable platforms for backend services.
   - **Use Case**: Hosts the signaling server.

---

## **Workflow Overview**
The application workflow involves users entering the platform, being queued for matching, and then being connected to another user for a video call. Connections are managed using a signaling server to establish WebRTC peer-to-peer communication.

### **FlowChart**

![image](https://github.com/user-attachments/assets/39f1b471-115c-463e-925b-0839aff0ebfb)


---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

---

### **Week 1: Project Setup and UI Design**
- **Goal:** Set up the foundational structure and design the application interface.
- **Tasks:**
  1. Initialize a **React.js** project and configure WebRTC support.
     - **Reading:** [React.js Official Docs](https://reactjs.org/docs/getting-started.html)
     - **Video:** [React.js Crash Course](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
  2. Design the landing page with input fields for user details.
     - **Reading:** [CSS Modules Overview](https://github.com/css-modules/css-modules)
     - **Video:** [CSS Modules Tutorial](https://www.youtube.com/watch?v=K1DR3y9U2HY)

- **Deliverables:**
  - Basic UI with navigation and placeholders for video elements.

---

### **Week 2: Real-Time Communication Setup**
- **Goal:** Implement the signaling server and establish WebRTC connections.
- **Tasks:**
  1. Set up a Node.js server with Socket.IO for signaling.
     - **Reading:** [Socket.IO Documentation](https://socket.io/docs/)
     - **Video:** [Socket.IO Crash Course](https://www.youtube.com/watch?v=1BfCnjr_Vjg)
  2. Establish WebRTC connections between peers.
     - **Reading:** [WebRTC Overview](https://webrtc.org/getting-started/overview)
     - **Video:** [WebRTC Crash Course](https://www.youtube.com/watch?v=WmR9IMUD_CY)

- **Deliverables:**
  - Functional signaling server with user connections established.

---

### **Week 3: Peer-to-Peer Video Calls**
- **Goal:** Enable video and audio streams between connected users.
- **Tasks:**
  1. Implement WebRTC APIs for video and audio streaming.
     - **Reading:** [WebRTC APIs](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)
     - **Video:** [WebRTC Video Chat Tutorial](https://www.youtube.com/watch?v=VhSGUcuHAD8)
  2. Display video streams in React components.
     - **Reading:** [React State Management](https://reactjs.org/docs/hooks-state.html)
     - **Video:** [React State Hooks](https://www.youtube.com/watch?v=O6P86uwfdR0)

- **Deliverables:**
  - Fully functional video calling interface.

---

### **Week 4: Matching and Room Management**
- **Goal:** Implement user matching and room logic.
- **Tasks:**
  1. Create a queue system for user matching on the server.
     - **Reading:** [Node.js Queues](https://nodejs.dev/learn/understanding-the-event-loop)
     - **Video:** [Node.js Event Loop](https://www.youtube.com/watch?v=PNa9OMajw9w)
  2. Handle room creation and cleanup dynamically.
     - **Reading:** [Socket.IO Rooms](https://socket.io/docs/v4/rooms/)
     - **Video:** [Socket.IO Room Management](https://www.youtube.com/watch?v=8BtPKXgNC1Q)

- **Deliverables:**
  - Dynamic user matching with room-based isolation.

---

### **Week 5: Deployment and Final Testing**
- **Goal:** Deploy the application and perform end-to-end testing.
- **Tasks:**
  1. Deploy the frontend to Netlify or Vercel and the backend to Heroku.
     - **Reading:** [Netlify Deployment Guide](https://docs.netlify.com/)
     - **Video:** [Deploying React Apps](https://www.youtube.com/watch?v=17UVejOw3zA)
  2. Test WebRTC functionality across different browsers and devices.
     - **Reading:** [WebRTC Testing](https://webrtc.org/testing/)
     - **Video:** [WebRTC Troubleshooting](https://www.youtube.com/watch?v=Du77vczWfOY)

- **Deliverables:**
  - Deployed Omegle Clone accessible via a public URL.

---
### Screenshots

![image](https://github.com/user-attachments/assets/5c4c50d2-6939-474d-8ec7-0eeae25a1aba)

---
### **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [WebRTC Documentation](https://webrtc.org/)
3. [Socket.IO Documentation](https://socket.io/docs/)
4. [Node.js Documentation](https://nodejs.org/en/docs/)
5. https://youtube.com/watch?v=0MIsI2xh9Zk
6. https://github.com/hkirat/omegle

