# WebSync

**WebSync** is an innovative, real-time web design collaboration platform that empowers users to create stunning, responsive websites effortlessly without writing any code.

## Introduction

WebSync redefines the way teams collaborate on web design projects. It eliminates the complexities of traditional web design by offering an intuitive no-code editor paired with powerful collaboration features. With WebSync, teams can work together in real-time, bringing their website visions to life seamlessly.

## Configuration & Installation

To get started with WebSync, ensure you have the following dependencies and tools installed:

- **Node.js**: Make sure you have Node.js installed on your system. [Download Node.js here](https://nodejs.org/).
- **Next.js**: WebSync is built using Next.js, a React framework for server-rendered applications. Install it globally using npm:
  ```bash
  npm install -g next
  ```
- **Convex Backend as a Service (BaaS)**: WebSync leverages Convex BaaS for backend services and real-time database functionality. Sign up for a Convex account and obtain your API key.

### Setup Instructions

1. **Clone the WebSync repository from GitHub:**
   ```bash
   git clone https://github.com/arka-kxqi/WebSync.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd websync
   ```

3. **Install project dependencies:**
   ```bash
   npm install
   ```

4. **Create a `.env` file in the root directory and add all environment variables:**
   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CONVEX_URL=
   REACT_APP_GOOGLE_API_KEY=
   NEXT_PUBLIC_PEXELS_API_KEY=
   
   # Deployment used by `npx convex dev`
   CONVEX_DEPLOYMENT=
   NEXT_PUBLIC_CONVEX_URL=
   ```

5. **Start the development server:**
   ```bash
   npm run dev
   ```

6. **Open your browser and navigate to** [http://localhost:3000](http://localhost:3000) **to access WebSync.**

## Details

WebSync is designed to make collaborative web design as simple as possible. Here's a look at its key features:

### 1. Real-Time Collaboration
- Collaborate in real-time with multiple users on the same project.
- Instant visibility of changes made by team members.

### 2. No-Code Editor
- Use the intuitive drag-and-drop editor to design websites without writing code.
- Add and customize elements like paragraphs, buttons, images, gradients, and more.

### 3. Scheduled Publishing
- Schedule your website's launch with ease.
- Plan and execute your releases with precise timing.

### 4. Integration with Convex BaaS
- Leverage Convex BaaS for backend services, authentication, data storage, and real-time updates.
- Ensure your projects are scalable, secure, and reliable.

## Inspiration

WebSync was born out of frustration with the traditional, complicated ways of web design collaboration. We wanted a platform where developers and designers could work together seamlessly, regardless of their coding skills. WebSync is the result of that vision—a tool that makes web design accessible, collaborative, and efficient.

## What It Does

WebSync offers a no-code editor with a range of customizable elements. Its real-time collaboration feature allows teams to accelerate project development. With responsive design, multiple-page navigation, and easy sharing through hosted links, WebSync is set to revolutionize your web design experience.

## How We Built It

WebSync combines the best of front-end and back-end technologies:
- **Frontend:** Built with Next.js and React, featuring a user-friendly editor interface.
- **Backend:** Powered by Convex BaaS, ensuring real-time collaboration and robust data management.
- **Security:** Clerk is integrated to provide secure access and safeguard user data.

## Challenges We Ran Into

Building WebSync came with its own set of challenges:
- Implementing real-time collaboration features.
- Optimizing drag-and-drop functionality for a smooth user experience.
- Ensuring the platform's performance, even for complex projects.

## Accomplishments That We're Proud Of

- Seamless drag-and-drop functionality.
- Successful real-time collaboration powered by Convex BaaS.
- Optimized performance for a responsive and efficient user experience.
- Integration of scheduled publishing to streamline website launches.

## What We Learned

Throughout the development of WebSync, we gained valuable insights:
- The intricacies of developing drag-and-drop features.
- Challenges in implementing real-time synchronization.
- The importance of continuous learning and team collaboration.

## What's Next for WebSync

- **Feature Expansion:** Add more components, templates, and customization options.
- **Enhanced Collaboration Tools:** Introduce commenting, version control, and user permissions management.
- **Mobile App Development:** Build a mobile app for managing websites on the go.
- **Community Engagement:** Develop an active community with resources, forums, and support.

## Built With

- **Clerk**
- **Convex**
- **Convex-Helpers**
- **Next.js**
- **React**
- **TailwindCSS**
- **TypeScript**