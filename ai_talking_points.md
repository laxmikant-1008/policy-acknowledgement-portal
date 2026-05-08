AI Talking Points Card

What is Groq?

Groq is an AI inference platform used in this project to generate fast and intelligent responses. It processes user questions and returns policy explanations in natural language.

---

What are Prompts?

Prompts are instructions or questions given to the AI model.

Example:
"Explain the leave policy"

The AI reads the prompt and generates a meaningful response based on company policy information.

---

How Our AI System Works

1. User enters a question.
2. Flask API receives the request.
3. The system validates the input.
4. The prompt is sent securely to Groq AI.
5. AI generates a response.
6. The response is returned to the user.

---

Security Talking Points

JWT Authentication

Used to secure API access and verify authorized users.

Rate Limiting

Prevents excessive requests and protects the system from abuse.

SQL Injection Protection

Malicious SQL inputs are detected and blocked.

Prompt Injection Protection

Unsafe prompts attempting to manipulate AI behavior are rejected.

Input Validation

Empty or invalid inputs are handled safely.

API Key Protection

Sensitive keys are stored securely using environment variables.

---

Docker Deployment

The application was tested successfully in a Docker containerized environment for portability and deployment consistency.

---

OWASP ZAP Testing

OWASP ZAP security scans were performed to identify vulnerabilities and improve application security.

---

Simple Closing Line for Demo

"Our project combines AI functionality with strong security practices to provide safe, reliable, and user-friendly policy assistance."