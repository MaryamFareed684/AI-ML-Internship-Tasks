○ Task objective 
 Create a chatbot that can answer general health-related questions using an LLM (Large Language Model). 
 
○ Dataset used 
No traditional dataset was used.
The chatbot relies on pre-trained language models (FLAN-T5) from Hugging Face.
Knowledge comes from the model’s pre-trained data on general health information.
 
○ Models applied 
FLAN-T5-Base (Google) via Hugging Face Transformers pipeline.
Text2text-generation pipeline for answering questions.
Framework: PyTorch (pt).
 
○ Key results and findings 
The chatbot successfully answers general health questions in a friendly and understandable way.
Prompt engineering ensures the model follows instructions and avoids giving direct medical prescriptions.
Responses are concise, safe, and suitable for general guidance.
Example outputs:
Question: “What causes a sore throat?” → Model explains causes like viral infection, allergies, etc., without giving prescriptions.
Question: “Is paracetamol safe for children?” → Model provides general safety guidance and advises consulting a doctor.

Limitation: The model cannot replace professional medical advice; it only provides general guidance.

