AI-Driven Traffic Alert & Route Advisory System

This project is an AI-powered early warning and route advisory system built using Langflow and IBM watsonx.ai (Granite models).
It analyzes traffic scenarios in real time using user inputs such as location, time, weather, and congestion conditions, and generates clear alerts, risk assessments, and alternative route suggestions.

The system uses a multi-agent architecture:

Traffic Data Analysis Agent to analyze traffic density, speed trends, delays, and environmental factors

Congestion Risk Detection Agent to predict congestion severity and escalation risk

Alert & Route Planning Assistant to generate structured ALERT!!! messages with real, location-specific alternate routes

A Retrieval-Augmented Generation (RAG) pipeline enhances accuracy by grounding responses in traffic guidelines and reference documents stored in a vector database, ensuring responses are contextual and reliable.

The solution supports global locations, with precise, geographically accurate routing for Bangalore, making it suitable for smart city traffic management, commuter assistance, and early congestion warnings.
