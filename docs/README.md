# WellNest

WellNest is a healthcare platform that aims to simplify the patient intake process. It focuses on Natural Language Consultation, allowing patients to describe their symptoms in plain English. This lets them receive immediate guidance on possible conditions and which specialists to see. It also displays the locations of some doctors registered to the website. Patient can book an offline appointment with the doctor.

## Technologies

- `Next.js`
- `Express`
- `Fast Api`
- `Tailwind CSS`
- `Typescript`
- `Google OAuth`
- `JWT`

## Features

Here's what you can do with WellNest:

- **Smart Consult** - ML-powered consultations that understand your health concerns
- **Find Doctors On Map** - Find nearby doctors that are registered on our website
- **Appointment Booking** - Schedule visits with doctors
- **Patient Dashboard** - Your health journey, beautifully organized
- **Feedback System** - Share your experience so we can keep getting better

## The Process

This project began as a simple idea: "What if healthcare felt more human?" I spent many late nights sketching wireframes and imagining how technology could connect patients and doctors.

The journey started with research; I spoke with doctors, patients, and healthcare workers to grasp their real challenges. Then I faced technical hurdles: creating a voice interface that feels natural, developing a backend that securely manages sensitive medical data, and designing a mobile app that operates as smoothly as the web version.

## How I Built It

Building WellNest was like conducting an orchestra; every piece needed to work in harmony:

### Phase 1: The Foundation
Every reliable medical tool starts with security. I began by creating a strong environment where patient privacy is a priority. By using JWT authentication, I made sure that the platform is as secure as a physical clinic's filing cabinet.

### Phase 2: The User Experience (Next.js)
Next.js served as my canvas for creating a "clean-room" interface. I moved away from the cluttered, intimidating look of traditional medical portals. Instead, I chose a high-contrast, accessible design. My goal was to reduce "white-coat syndrome" by using soft emerald tones and intuitive layouts that work for everyone, no matter their technical ability.

### Phase 3: The Engine Room (Express Backend)
To manage the heavy lifting of user data and consultation history, I built a Express.js backend. This layer acts as the orchestrator—managing the flow of information between the user's input and the diagnostic models, ensuring that every request is handled with low latency and high reliability.

### Phase 4: Smart Consult & FastAPI
This is the "brain" of WellNest. I developed a specialized FastAPI service to handle the Natural Language Processing (NLP) tasks. Instead of simple keyword matching, this model parses a patient’s everyday language to identify medical markers.

- The Logic: It maps vague symptoms (e.g., "stomach feels like it's tied in knots") to specific medical categories.
- The Result: The engine intelligently suggests potential conditions and immediately identifies the correct specialist—like a Gastroenterologist—to consult for next steps.

### Phase 5: The Deployment
The final phase was about bringing WellNest to the world. I deployed Next.js frontend on Vercel. I deployed Express.js and Fast API backend on Render.

## What I Learned Along the Way

This project taught me many important lessons:

- **Healthcare is deeply personal**: Every line of code impacts someone's health and well-being.
- **Security isn't optional**: Medical data requires the highest protection standards.
- **Accessibility matters**: Designing for everyone leads to better experiences for all.
- **Supervised Machine Learning**: Using supervised machine learning algorithms to make consultation system.

### Overall Growth:

Each part of this project helped me understand more about building apps, managing complex information, and improving user experience. It was more than just making a tool. It was about solving problems, learning new things, and improving my skills for future work.

## How It Could Be Improved

WellNest is evolving, and there’s always room for growth:

- **AI-Powered Diagnostics**: Adding ai agents for better symptom analysis.
- **Telemedicine Integration**: Enabling direct video consultations through the platform.
- **Wearable Device Sync**: Connecting with fitness trackers and health monitors.
- **Multi-language Support**: Breaking down language barriers in healthcare.

## Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository to your local machine.
2. Run `npm install` or `yarn` in the project directory to install the required dependencies.
3. Open `scripts/frontend.bat`, `scripts/backend-express.bat` and `scripts/backend-quart-api.bat` to run frontend, backend and fast api respectively.
4. Open [http://localhost:3000](http://localhost:3000) (or the address shown in your console) in your web browser to view the app.

## Video



## Preview

[Visit website](https://wellnestjs.vercel.app/)