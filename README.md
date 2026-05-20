# PitchPilot AI – Real-Time Voice Pitch Practice Platform

## Overview

PitchPilot AI is an interactive voice coaching platform that helps users improve their public speaking and pitch delivery through real-time AI feedback. Built with cutting-edge voice AI technology, it provides instant coaching, performance analysis, and actionable insights to help speakers gain confidence and polish their delivery.

Built for the **Google Gemini Live Agent Challenge (March 2026)**, PitchPilot AI evolved into a full product demonstrating real-time voice AI capabilities and interactive coaching.

---

## My Role

**Co-Founder & Lead Full-Stack Developer**

I architected and built PitchPilot AI across the entire stack, handling complex real-time voice processing, AI integration, and infrastructure challenges:

- Full-stack development (frontend, backend, voice processing)
- Real-time voice interaction architecture with WebSockets
- AI integration with Google Gemini Live API
- Backend infrastructure with Node.js and Google Cloud Run
- Voice Activity Detection (VAD) optimization and configuration
- Docker containerization and cross-platform deployment
- Phase management and state synchronization
- Production deployment and scaling

**Co-Founder:** [Gaby Estrella](https://github.com/gabyestrella) – Collaborator on core architecture and feature implementation

---

## Key Features

**Real-Time Voice Interaction**
- Live voice streaming with bidirectional WebSocket communication
- Sub-100ms latency for responsive coaching
- Seamless audio input/output handling

**AI-Powered Coaching**
- Google Gemini Live API integration for intelligent feedback
- Real-time coaching based on speech patterns and delivery
- Performance insights and improvement suggestions
- Custom voice personality ("Charon") for consistent coaching tone

**Voice Activity Detection (VAD)**
- Intelligent silence detection with optimized sensitivity settings
- Automatic phrase detection and processing
- Configurable silence duration thresholds
- Reduces latency and improves user experience

**Performance Feedback**
- Real-time analysis of pitch, pacing, and clarity
- Immediate coaching suggestions during practice
- Cumulative feedback and progress tracking
- Personalized recommendations for improvement

**Session Management**
- Phase-based workflow (introduction, practice, feedback)
- State synchronization across components
- Connection reliability with automatic reconnection handling
- GoAway protocol handling for stable sessions

---

## Tech Stack

**Frontend:**
- React 18
- TypeScript
- Real-time audio streaming
- WebSocket client integration

**Backend:**
- Node.js + Express
- TypeScript
- Custom WebSocket proxy architecture
- Google Cloud Run for serverless deployment

**AI & APIs:**
- Google Gemini Live API (model: gemini-2.5-flash-native-audio-preview-12-2025)
- Real-time voice streaming
- Custom voice personality configuration

**Infrastructure:**
- Google Cloud Run for scalable backend
- Vercel for frontend deployment
- Docker containerization with cross-platform support (Apple Silicon compatibility)
- WebSocket proxy for bidirectional communication

**Voice Processing:**
- Web Audio API for client-side audio capture
- VAD (Voice Activity Detection) optimization
- Audio codec handling and streaming

---

## Development Highlights

✅ **Real-Time Architecture** – Designed WebSocket proxy system for reliable voice streaming  
✅ **GoAway Reconnection Handling** – Solved connection stability challenges  
✅ **VAD Optimization** – Fine-tuned voice detection for natural conversation flow  
✅ **Cross-Platform Deployment** – Docker Apple Silicon support for seamless development  
✅ **Production-Ready** – Deployed and tested with real users  
✅ **AI Integration** – Seamless Gemini Live API integration for intelligent coaching  
✅ **Infrastructure as Code** – Cloud Run setup for scalable, serverless operation  

---

## Technical Challenges Solved

- **Reconnection Logic:** Implemented robust GoAway protocol handling for stable WebSocket connections
- **Latency Optimization:** Achieved sub-100ms response times for real-time coaching
- **Voice Detection:** Tuned VAD configuration (`END_SENSITIVITY_HIGH`, `silenceDurationMs: 500`) for natural interactions
- **Cross-Compilation:** Built Docker images for Apple Silicon development environment
- **State Management:** Implemented phase-based state synchronization for reliable sessions

---

## Repository

The complete source code is maintained privately in the [zaaby-app organization](https://github.com/zaaby-app).  
Feel free to reach out to discuss the real-time voice architecture, WebSocket implementation, or any technical aspects of the project.

---

## Connect

- **Portfolio:** [donatohernadnez.dev](https://donatohernandez.dev) *(coming soon)*
- **Email:** manueldonato9921@gmail.com
- **LinkedIn:** [manuel-donato-hernandez](https://www.linkedin.com/in/manuel-donato-hernandez/)
- **GitHub:** [@donatohernandez](https://github.com/Donatohernandez)
