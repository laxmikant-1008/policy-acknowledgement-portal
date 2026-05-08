Final Demo Script – Policy Acknowledgement Portal

Demo 1 – AI Recommendation

User Input:
"Explain the leave policy"

Expected Output:
The AI provides a simple explanation of leave rules, approvals, and employee responsibilities.

---

Demo 2 – Generate Report

User Input:
"Summarize the work from home policy"

Expected Output:
The system generates a short and clear summary report of the policy.

---

60-Second Explanation – Flask + Groq

"Our project is built using Flask and Groq AI integration. Flask is used as the backend framework to create API endpoints and manage user requests. When a user sends a policy-related query, Flask receives the request, validates the input, and securely forwards the prompt to the Groq AI model. Groq processes the prompt and generates a natural language response, which is then returned back to the user through the Flask API. We also implemented JWT authentication, rate limiting, and injection protection to improve security and reliability."

---

Show /health Endpoint

Open browser or Postman:

http://localhost:5000/health

Expected Output:

{
  "status": "healthy"
}

This endpoint confirms that the backend service is running correctly.

---

Security Talking Points

- JWT Authentication protects APIs
- Rate limiting prevents abuse
- SQL injection attempts are blocked
- Prompt injection inputs are rejected
- Docker used for containerized deployment
- OWASP ZAP used for security testing

---

Closing Line

"Our project combines AI-powered policy assistance with strong backend security and containerized deployment to deliver a reliable and user-friendly solution."