[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17663489.svg)](https://doi.org/10.5281/zenodo.17663489)

# Standardized Patient Avatar for Reflective Communication Practice (SPARC-P)

**Enhancing Clinician Communication Through Reflective AI Practice**

Conference: UF Health Cancer AI Symposium 2025

## Abstract
SPARC addresses the gap between evidence-based recommendations and real-world clinical communication. With an HPV vaccine use case, the project develops an AI-enabled training tool that simulates patient interactions to help clinicians practice communication strategies and receive real-time, evidence-based feedback.

### Key Features
* AI-driven 3D avatars simulate patient encounters
* Language models fine-tuned on clinician-patient dialogues
* Multi-agent AI architecture ensures accuracy, safety, and feedback
* Scalable, asynchronous, interactive learning environment

---

## The Challenge
The persistent gap between research and practice in cancer care is driven in part by limited integration of evidence-based clinician communication practices into routine care, despite decades of proven training approaches.

Developing scalable experiential communication skills training solutions—beyond resource-intensive live formats—could dramatically expand clinician reach and improve cancer outcomes at population scale.

## The Solution
SPARC introduces a flexible, AI-supported approach that expands access while maintaining educational rigor.
* Practice anytime, anywhere
* Objective, real-time feedback
* Pilot includes 10 clinicians

### Comparison: Traditional vs. SPARC

| Traditional Clinician Training | SPARC AI-Enabled Training |
| :--- | :--- |
| In-person standardized patients | Virtual patient powered by AI |
| Limited session availability | Asynchronous and online |
| Focus on observation and critique | Focus on reflection and skill-building |

---

## How SPARC Works
SPARC-P uses a network of agents to simulate dialogue and provide feedback.

**System Workflow:**
1.  **User (Medical Practitioner):** Input via Microphone/Webcam.
2.  **Agent 1 (SPARC-P Supervisor):** * Receives User Input.
    * Coordinates with Coach and Caregiver agents.
    * Outputs filtered AI Responses (Audio/3D Animations) to User.
    * Transcribes Audio to Text for other agents.
3.  **Agent 2 (CLEAR Coach):** * Provides Coach Output to Supervisor (UI Feedback, Grade).
    * Provides feedback to agents if a response is inappropriate.
4.  **Agent 3 (Caregiver):** * Provides Caregiver Output to Supervisor (Text Response, Audio Response, 3D Mouth Animations, 3D Gestures).

---

## Development & Technology

### AI Integration
SPARC uses advanced AI to simulate realistic patient encounters and provide instant, data-informed feedback. Speech, language, and animation technologies work together on UF's HiPerGator platform to create secure, scalable training that mirrors real clinical communication.

* **Speech Recognition & Synthesis:** NVIDIA Riva ASR & TTS
* **Language Models:** Fine-tuned OpenAI OSS 120B LLM hosted on HiPerGator
* **Safety & Ethics:** NVIDIA NeMo Guardrails & Multi-Agent reasoning
* **Avatar Emotion & Animation:** Reallusion and NVIDIA Audio2Face
* **Data Processing:** LangChain + Chroma for retrieval and contextual response generation

### 3D Modeling
SPARC's 3D avatars are designed to reflect authentic human emotion and behavior. Each character is modeled and animated to express empathy, tone, and body language—creating realistic, emotionally resonant encounters that enhance clinician engagement and learning.

* **Character Design:** Created in Maya, Blender, and Unity for realism and accessibility.
* **Rigging & Animation:** Facial expressions and gestures synced with speech.
* **Voice & Emotion:** Integrate NVIDIA Audio2Face and Reallusion for lifelike delivery.
* **Design Intent:** Diverse personas support inclusive, human-centered training.

### UX Design
SPARC clinicians engage in realistic conversations, view feedback, and track progress over time. The design supports intuitive navigation, minimal distractions, and seamless integration of dialogue, reflection, and skill evaluation.

* **Web-Based Access:** Simple browser interface for any device.
* **Reflection Dashboard:** Summaries and performance insights.
* **Real-Time Feedback:** Scoring and guidance during sessions (C-LEAR Guide).
* **User-Centered Design:** Streamlined layout tested for clarity and ease of use.

**Example Scenario (Parent Profile):**
* **Name:** Anne Palmer
* **Role:** Legal Guardian (maternal aunt)
* **Concerns:** No major health concerns; questions about vaccines.
* **C-LEAR Guide:** Counsel, Listen, Empathize, Acknowledge, Restate.

---

## Project Timeline

* **Stage 1: Define Vision:** Goals, workflows, and requirements established.
* **Stage 2: Early Concepts:** Interface wireframes and AI scripting begun.
* **Stage 3: Prototype Build:** Functional platform with data capture.
* **Stage 4: Internal Testing:** Evaluate usability and AI safety of application.
* **Stage 5: User Simulation:** Improve realism through pilot feedback.
* **Stage 6: Project Completion:** QA, reporting, and April 2026 presentation.

---

## Meet the Team

* **Carma Bylund, Ph.D.:** Co-Principal Investigator
* **Jason Arnold, Ed.D.:** Co-Principal Investigator
* **Stephanie Staras, Ph.D.:** Co-Principal Investigator
* **Jay Rosen:** AI Engineer/Development
* **Macy Geiger, Ed.D.:** Learning Experience Design
* **Eve Kung:** Front End Development
* **Kayla Sharp, MSM:** Project Manager
* **Jon Walker:** Web Development
* **Rachel West:** 3D Modeling
* **Kennan DeGruccio:** Standardized Patient Educator

---

## Affiliations
* UF College of Medicine - University of Florida
* UF College of Education - E-Learning, Technology and Communications
* UF Health - University of Florida Health
