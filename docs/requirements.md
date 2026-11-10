# Requirements

## Functional requirements (what the system must DO)
- **FR1:** The system shall allow users to ask questions about traffic summonses in simple Bahasa Melayu or English through a natural language chat interface.
- **FR2:** The system shall retrieve real-time fine schedules, discount campaign rules, and offense details from an official PDRM knowledge base.
- **FR3:** The system shall classify summonses into compoundable fines (payable online) and non-compoundable offenses (requiring a court appearance).
- **FR4:** The system shall calculate the final payable penalty amount after applying active campaign discounts and time-based rules.
- **FR5:** The system shall provide official PDRM source references for every legal or fine explanation it generates.

## Non-functional requirements (how the system must PERFORM)
- **NFR1:** The system shall respond to user queries within 3.0 seconds under standard internet connectivity.
- **NFR2:** The system shall maintain an answer accuracy rate of at least 98% based on official PDRM guidelines, keeping factual errors below 2%.
- **NFR3:** The system shall mask sensitive personal details, including IC numbers and vehicle plate numbers, in all chat logs to protect user privacy.
