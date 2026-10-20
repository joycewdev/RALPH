# RALPH - Rapid Assessment for Little Patients in Healthcare
### Inspiration
Early warning signs are often the hardest to catch in young patients because they struggle to articulate what they are feeling, leaving critical risks hidden in busy waiting rooms.

### What it does
RALPH is an interactive, AI-driven pediatric triage and continuous monitoring companion that bridges the communication gap between young children and care teams and turns unproductive waiting room time into life-saving clinical oversight.  
- A friendly conversational raccoon does patient intake and assessment, accepting text, speech, and built-in response options
- Once information is gathered, patient is provided with waitroom games (gamified cognitive and motor check-up) and periodic check-ins
- Clinical AI triage flags crucial symptoms and structured details are sent to the staff dashboard displaying the queue and patient profiles
- No diagnosis, ultimately up to the medical professional

### How we built it
Frontend: React, TypeScript, Vite, Tailwind CSS  
Backend: Node.js, Fastify, TypeScript  
AI and voice: Google Gemini and browser speech APIs as a fallback  
Database: PostgreSQL with Tiger Data  
Other features: Socket.IO for live updates, i18next for multilingual translations, Framer Motion for animation  
Hosting plan: Vercel with GoDaddy Domain  
