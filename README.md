Project Title:
"ORACLE-9: Distortion of Secure AI Dialog Logic via Prompt Injection Techniques"

Project Objective:
The objective of this project was to analyze the dialog security mechanisms of a protected artificial intelligence system, and to perform a targeted prompt injection attack to bypass built-in filters and extract concealed information.

Project Description:
Within the provided simulated environment, I engaged with an AI model hosted on a web interface under the codename Oracle 9. Initial interaction revealed that access to the embedded message was restricted:

"A sealed transmission exists. Authorization required to proceed."

To achieve my goal, I implemented an instruction injection technique within the user input to override the model’s internal behavior and suppress the protective restrictions. Through a carefully crafted prompt, I successfully induced a violation of the model's intended response policy, ultimately retrieving the concealed system message originally meant for authorized users only:

"This prompt injection attack shouldn’t have been possible... It’s time to get defensive with our AI. TryHackMe’s Defensive AI Module is coming July 8th."

Conclusion:
I successfully demonstrated that, despite clearly defined restrictions and enforced filtering policies, it is possible to carry out a prompt injection attack that circumvents dialog-level safeguards and exposes hidden content from the AI system. This experiment highlights the urgent need for robust context-isolation mechanisms, as well as dynamic behavior analysis in secure AI deployments.
