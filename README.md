PROJECT REPORT / SOLUTION SUMMARY
Team Information
Team Name: Praxis
Team Members:
1.	Mayanglambam Premananda Singh (Backend Developer)
2.	Naoroibam Thajaba (Model Evaluation)
3.	Korounganba Thokchom (Frontend Developer) 

________________________________________
Selected Problem Statement
AI-Based Environmental & Disaster risk Forecasting (Governance & Social Impact)
Design an AI-driven platform that analyses weather, satellite, and historical disaster data to predict risks such as floods, landslides, or heatwaves and provide actionable alerts for communities and local administrations.
________________________________________
Core Problem
Communities and local administrations lack timely, accurate, and localized disaster risk predictions, leaving them unable to take preventive action before environmental disasters strike.
Specific Problem That Has Been Addressed
1.	Delayed or Inadequate Warning Systems
2.	Lack of Hyperlocal Risk Assessment
3.	Fragmented Data Sources
4.	Limited Predictive Capacity for Cascading Events
5.	Communication Gap with Vulnerable Populations
6.	Reactive Rather Than Proactive Governance
Our Solution: GeoGuard (Mobile Application) 
GeoGuard Mobile is a Mobile App designed to assist in the early recognition of potential dangers and providing support in making decisions based on Artificial Intelligence (AI). The app uses only one input from the user (the user's current location) to provide meaningful and accurate information back to the user in an easy-to-use way.
The Insurance Provider and GeoGuard have aggregate weather reports, satellite images and other public information from Governments and organizations which is processed through AI Models to increase accuracy and relevant information but does not instil fear during the process of alerting users.
GeoGuard delivers different outputs custom to the following groups:
-Government Officials receive specific information about the types of emergency response equipment (amount, location and status) that are available.
-Community members receive a clear action plan with safety tips and procedures tailored to their risk level and location.
AI is also implemented in the interaction process using the LLaMA AI Assistant to provide:
-A calm, clear, instructive way to reduce panic and provide a suggested source of action during any emergency
-A means of coordinating activities and communication between users and Government Authorities
GeoGuard intends to provide accurate, timely information and an opportunity for a coordinated response via a simple mobile application that is easy for users to find, produce, and act upon.
________________________________________
Artificial Intelligence and Technology Stack
AI Implementation:
Risk Analysis & Forecasting Models:
•	Built using Machine Learning and Deep Learning models for risk classification and forecasting
•	Trained on historical disaster records, weather datasets, satellite-derived indicators, and geospatial data
•	Uses feature engineering on parameters such as rainfall intensity, temperature anomalies, terrain elevation, and past disaster frequency
•	Generates location-based risk scores and probability estimates for disasters such as floods, landslides, and heatwaves
Computer Vision (Satellite & Visual Analysis):
•	Processes satellite imagery and environmental visual data to detect terrain changes, water accumulation, and vegetation stress
•	Uses Convolutional Neural Networks (CNNs) with transfer learning from pre-trained vision models
•	Enhances raw satellite outputs to improve interpretability for non-technical users and authorities
Natural Language Processing (Using LLaMA 3.2):
•	Powered by LLaMA 3.2 for intelligent interaction and decision support
•	Converts complex AI outputs into clear, calm, and non-alarming explanations
•	Generates personalized action plans based on user role (citizen or government official)
•	Supports context-aware responses, guiding users step by step during emergencies
•	Helps reduce panic by providing reassuring, actionable, and situation-specific guidance
Decision Support & Coordination Engine:
•	Dynamically adapts responses based on user type, location, and risk severity
•	Provides:
o	Government officials with equipment availability, operational status, and resource allocation insights
o	Common users with safety instructions, evacuation guidance, and precautionary steps
•	Enables better coordination between authorities and communities through AI-driven insights
Data Sources and Integration:
•	Weather APIs and meteorological reports
•	Publicly available satellite datasets
•	Government and open disaster databases
•	Real-time and historical geospatial information
Technology Stack
Mobile Application Layer
•	Frontend Framework: React Native
•	App Platform: Expo
o	Single codebase deployed as:
	Android application
	iOS application
	Web application
	Desktop application
•	UI Design Focus:
o	Lightweight and user-friendly interface
o	Optimized for low-bandwidth and disaster-prone regions
•	Input Model:
o	Single primary input: User location
o	Role-based experience (Citizen / Authority / Organization)
________________________________________
Backend & System Architecture
Core Backend (Controller Layer – The Brain)
•	Language: Python
•	Architecture: Modular, controller-driven system
•	Acts as the central decision-making unit, not the AI model itself
•	Responsibilities:
o	Input validation and location resolution
o	Hazard selection and workflow orchestration
o	Coordination between prediction branches
o	Output aggregation and delivery
________________________________________
AI & Prediction Pipeline
Branch-Based Intelligence Architecture
Branch 1: Risk Assessment (Prediction Layer)
•	Focuses on hazard detection and probability estimation
•	Uses:
o	Weather data
o	Geospatial and spatiotemporal indicators
o	Historical disaster datasets
•	Outputs:
o	Hazard type (flood, landslide, heatwave, etc.)
o	Risk probability scores
o	Severity classification
Branch 2: Preparedness & Response Planning
•	Focuses on readiness analysis and action planning
•	Evaluates:
o	Infrastructure capacity
o	Resource availability
o	Community preparedness indicators
•	Outputs:
o	Preparedness index
o	Response templates
o	Recommended actions for different stakeholders
________________________________________
Orchestration & Workflow Management
•	Workflow Engine: Controls the end-to-end flow of execution
•	Branch Router: Dynamically routes data to Branch 1 and Branch 2
•	Data Contracts: Ensures strict input–output schema consistency
•	Caching Mechanism: Stores recent assessments for faster response
________________________________________
Output & Communication Layer
•	Readiness Score Generator: Produces final preparedness and risk scores
•	Action Generator: Converts predictions into actionable steps
•	Report Builder: Generates structured reports and dashboards
•	Alert Adapter: Sends alerts through:
o	Mobile app notifications
o	SMS
o	Messaging platforms (future extensibility)
________________________________________
Natural Language Intelligence (Using LLaMA 3.2)
•	Model: LLaMA 3.2
•	Integrated at the controller output stage
•	Responsibilities:
o	Enhances raw AI outputs into clear, human-readable explanations
o	Tailors responses based on:
	User role
	Risk severity
	Location context
o	Reduces panic by ensuring:
	Calm language
	Step-by-step guidance
	Actionable and coordinated instructions
LLaMA 3.2 acts as the intelligent communication layer, not the prediction engine, ensuring that complex risk data is transformed into trustworthy, understandable, and actionable insights.
________________________________________
Innovation and Uniqueness
Our solution goes beyond traditional risk prediction by providing actionable solutions in the form of step-by-step action plans and coordinated response guidance, rather than only presenting risk scores.
Artificial Intelligence is implemented at the interaction and communication level, where it delivers the greatest impact. We use LLaMA 3.2, chosen for its large context window and open-source nature, enabling the system to understand complex, multi-source outputs and generate coherent, situation-aware responses.
The system leverages publicly available weather and geospatial data, ensuring transparency, accessibility, and scalability. These datasets are used to strengthen and refine existing models, rather than replacing them. Additionally, we plan to incorporate research-backed geospatial satellite analysis techniques to further improve risk estimation accuracy.
A key innovation of our approach is the selective and responsible use of AI. AI is not applied where it is unnecessary; instead, it is used only in areas where meaningful improvement can be achieved. The core prediction logic remains intact, while AI is used to enhance interpretation, communication, and decision support.
This design ensures reliable predictions, clearer guidance, reduced panic, and improved coordination—making the system both trustworthy and effective in real-world disaster scenarios.
________________________________________
Scalability
•	The prediction system can be implemented using traditional, proven forecasting approaches, ensuring reliability from the initial deployment.
•	The platform is designed to be geographically scalable, allowing dynamic integration of data from new regions without redesigning the core system.
•	As coverage expands, additional datasets can be incorporated to improve accuracy and regional relevance.
•	With increased investment, the system can support offline and on-device prediction capabilities, enabling continued operation during network or power disruptions.
•	This ensures that risk assessment and decision support remain available even in low-connectivity or emergency conditions, making the solution robust and resilient.

