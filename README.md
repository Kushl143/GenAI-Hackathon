# GenAI-Hackathon

## 🧠 Inspiration

In a world where AI solves practical tasks, I wanted to explore how it could also support *emotional well-being*. Inspired by the idea of having a "digital twin" that truly understands your feelings and decision patterns, I envisioned **MindMate** – a GenAI-powered emotional twin that evolves with you.

As a student, I often wished for something (or someone) that could reflect my thoughts, help me communicate better, and offer emotional support without judgment. That need sparked the foundation of this project.

---

## 🛠️ What It Does

**MindMate** is a personalized AI companion that:

- Mirrors your tone, mood, and style
- Offers emotional journaling and reflections
- Helps with decision-making by learning your values
- Remembers your conversations and emotional context
- Generates supportive or empathetic responses in your own voice

---

## ⚙️ How we built it

1. **Frontend** with Flutter for cross-platform UI
2. **Backend** with Python (FastAPI) and Node.js
3. **AI Models** used:
   - GPT for natural language generation
   - Stable Diffusion for emotional visual journaling
   - AWS Transcribe + Whisper for voice inputs
4. **Data** is stored in AWS DynamoDB with memory graphs to track emotional evolution
5. Hosted on **AWS Lambda & S3**

---

## 💡 Challenges we ran into

- Personalizing LLM output to reflect the user's personality while keeping responses consistent.
- Building a memory system that stores both emotional context and factual timelines.
- Managing latency with GenAI calls for real-time feedback.
- Designing an empathetic UX that *feels* human but is still clearly AI.

---
## 🏅 Accomplishments That We're Proud Of

- Created a working prototype of an AI that mimics a user's emotional tone and communication style.
- Successfully integrated multiple GenAI models (text, image, and voice) into one coherent system.
- Built a lightweight emotional memory system that evolves with the user over time.
- Designed a user experience that feels emotionally aware, not robotic.
- Overcame technical and emotional challenges in building a product that’s deeply personal.
- Deployed key components on AWS, enabling scalability and serverless performance.


## 📚 What we learned

- Deep understanding of emotion modeling and user memory graphs.
- Prompt engineering and fine-tuning GenAI for emotionally aware responses.
- Cloud integration with AWS (especially Lambda, S3, and Transcribe).
- Importance of ethics and data privacy when dealing with sensitive emotional content.

---

## 🌍 What's next for MindMate – Your GenAI-Powered Emotional Twin

- Deploy the mobile app and test with users from different age groups.
- Add multi-lingual and cultural emotion adaptation.
- Include mental health check-ins powered by clinical datasets (non-diagnostic).
- Open API so other apps can integrate their own emotional AI twin.

---

## 🚀 Conclusion

**MindMate** isn't just a chatbot—it’s an emotional reflection engine. With the right AI, we can create more empathetic, human-centered digital tools that help people feel understood, supported, and seen.
