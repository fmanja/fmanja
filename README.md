# About Me

I’m Frank Manja — I am obsessed with applying Generative AI to real world applications. My career journey has included Dept. of Justice, Dept. of Energy, IBM, Emory University and The World Bank. 

I’m building a suite of HR + AI tools fully open source. If you’re working on AI in government, HR tech, or regulated enterprise environments, I’d love to connect and compare notes. Feel free to connect with me on LinkedIn, https://www.linkedin.com/in/frank-manja-b6986617/. 

### Open Source Project Summaries
- AI-Position Description Generator to produce OPM compliant position descriptions for job vacancies using Claude 3.5.
- AI-Personnel Action Request Form Generator to produce OPM compliant SF-50 forms for any type of federal personnel action using Claude 3.5.
- Fine-tuned meta-llama/Llama-3.2-3B model to recommend Nature of Action (NOA) codes for processing personnel action requests for federal employees based on common scenarios in accordance with OPM standards using QLoRA.

Disclaimer: All views and opinions expressed here are my own and do not represent those of my employer, past or present, or any affiliated organizations. Any work shared is personal and created outside my professional duties.

---

# AI Position Description Generator (Open Source)

An AI-powered tool to generate professional federal government job descriptions using AWS Bedrock with Claude 3.5 Sonnet. Built with Next.js 16, TypeScript, and deployable on AWS EC2, Vercel, or other Node.js hosted environments. 

This project is intended to be a comprehensive project for any Human Resource Department and Office of the Chief Information Officer that wants to get a quick win with mininal risk - all code is open source and can be easily deployed to GovCloud. 

This project is an Open Source and available at https://github.com/fmanja/nextjs-hrpdgenerator.

### Screenshots
<b>Position Description Form</b>
<img width="1251" height="686" alt="PD_Generator_Form" src="https://github.com/user-attachments/assets/3b7565b7-9219-42b9-bc72-5cd4b636d55e" />

<b>AI Generated Position Description</b>
<img width="1251" height="686" alt="PD_Generator_Results" src="https://github.com/fmanja/nextjs-hrpdgenerator/blob/main/images/PD_Generator_Results.png" />

### Features

- Generate professional federal government job descriptions using Claude AI via AWS Bedrock
- OPM (Office of Personnel Management) job family and series data integration
- Support for multiple pay scales (GS, SES, ES, SL, ST, and others)

---

# AI-Personnel Action Request Form Generator (Open Source)

A focused, standalone Next.js application that demonstrates the AI Assistant functionality for generating SF-50 (Standard Form 50) personnel action form recommendations for the federal government. This application uses AWS Bedrock with Claude models to recommend appropriate Nature of Action (NOA) codes based on employee scenarios.

This project is intended to be a comprehensive project for any Human Resource Department and Office of the Chief Information Officer that wants to get a durable win with mininal risk - all code is open source and can be easily deployed to GovCloud. 

This project is an Open Source and available at https://github.com/fmanja/nextjs-sf50generator.

### Screenshots
<b>Employee Scenario Form</b>
<img width="1512" height="782" alt="Get_Recommendation" src="https://github.com/user-attachments/assets/596ef6ca-cdbc-4696-869b-cd7c99419b05" />

<b>AI Recommendations and Follow-ups</b>
<img width="1512" height="782" alt="Get_Recommendation" src="https://github.com/fmanja/nextjs-sf50generator/raw/main/images/Initial_Recommendation_FollowUps.png" />

<b>Features</b>

- Generate professional SF-50 (Standard Form 50)
- Enter realistic scenarios using Natural Language
- AI recommendations for NOA Codes, Legal Authority Codes, OPM NOA Remarks and Remark Codes
- Interactive Chatbot for follow-up and clarifying questions
- Real-time Refinement provides more accurate recommendations as you provide additional information
- PDF Generation with employee information and AI recommendations automatically populated in the downloadable PDF

# Fine-tuned meta-llama/Llama-3.2-3B (Open Source)

In this project the meta-llama/Llama-3.2-3B model was finetuned using QLoRA to recommend Nature of Action (NOA) for processing personnel action requests for federal employees based on common scenarios. NOA codes are unique numerical identifiers for every personnel action (like promotions, appointments, or retirements) in the U.S. Federal government, used for data processing on forms like the SF-50, with categories 000-899 for standard actions and 900-999 for agency-specific matters, all detailed in OPM's Guide to Processing Personnel Actions (GPPA).

This project is an Open Source and available at https://huggingface.co/fmanja/llama-3.2-3b-qlora-finetuned-hr.

### Screenshots
<b>Model Card</b>
<img width="1503" height="815" alt="NOA-FineTuned Model" src="https://github.com/user-attachments/assets/c345fa91-e504-4e0d-8d36-5043bf4c3a94" />

<b>Training Data</b>
<img width="1503" height="815" alt="NOA-Training Data" src="https://github.com/user-attachments/assets/a5e5b764-f202-439a-a8aa-a95d20cd293b" />

<!--

---

## Project 4. AI Magazine Marketing (Level: Advanced)

A modern Next.js application for managing magazine marketing operations with advanced AI assistance, real-time database analytics, and comprehensive business intelligence. This platform provides complete tools for sales representatives, customer management, magazine portfolio tracking, proposal management, analytics, dynamic KPI management, RAG-powered content search, and real-time AI-powered business analysis.

### Screenshots
<b>AI Magazine Marketing Dashboard</b>
<img width="864" height="456" alt="AIMM-1" src="https://github.com/user-attachments/assets/16624cee-545a-48df-b004-b86b1eff822c" />

<b>Advanced AI Assistant</b>
<img width="960" height="540" alt="AIMM-2" src="https://github.com/user-attachments/assets/3f292e35-9870-4bc1-b336-9635219f0b87" />

<b>Features</b>
- Advanced AI Assistant with LLM Tools, Query Classifier, RAG, Cache, Logging, and Evaluations.
- Role Based Access for Administrators, Sales Managers, and Sales Reps
- File Uploads for data refreshes
- CRUD operations for a production application
- Authentication system for all users and protected API routes

<b>Architecture</b>

The AI Magazine Marketing Application uses the most cutting-edge LLM, LLM Caching, RAG, Programming Frameworks and Agentic Development tools: ChatGPT, Pinecone, Redis, Postgres, Next.js, React, GitHub, Cursor AI, TypeScript, and Prisma.


<img width="544" height="332" alt="AIMM-3" src="https://github.com/user-attachments/assets/c727cc28-7c99-4def-91a9-42b3b592a3b6" />
--> 
