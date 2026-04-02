Evo2 DNA Mutation Predictor
Overview

This project is an AI-powered web application that analyzes DNA mutations and predicts their potential to cause disease. By leveraging the Evo2 model, the system classifies genetic variants as pathogenic or benign and compares predictions with known clinical data.

The goal is to make genomic analysis more accessible by providing a simple interface for exploring and interpreting DNA mutations.

Problem Statement

Interpreting DNA mutations is a complex and time-consuming process. While some variants are well-studied, many remain unclassified or labeled as “uncertain significance,” making it difficult to determine their impact on human health.

This project provides a scalable, AI-driven approach to:

Analyze genetic variants quickly
Predict their potential impact
Compare results with existing clinical classifications
Features
DNA Mutation Analysis
Input and analyze single nucleotide variants (SNVs)
AI-Powered Prediction
Predict whether a mutation is pathogenic or benign using Evo2
Comparison with Clinical Data
Compare predictions with known variant classifications
Confidence Estimation
Display confidence scores for predictions
Genome Exploration (Planned)
Browse genome assemblies and genes
Gene Search (Planned)
Search for specific genes and analyze mutations within them
System Architecture
Frontend
Next.js (React, TypeScript)
Tailwind CSS
Shadcn UI
Backend
FastAPI (Python)
REST API for mutation analysis
AI / Model
Evo2 large language model for genomic sequence analysis
Deployment
Modal (GPU-enabled serverless deployment)
H100 GPU for accelerated inference
How It Works
User selects or inputs a DNA mutation
The mutation is sent to the backend API
The Evo2 model analyzes the sequence
The system returns:
Prediction (Pathogenic / Benign)
Confidence score
Results can be compared with known clinical data
Project Structure
/frontend        # Next.js application
/backend         # FastAPI server
/model           # Model integration and inference logic
/utils           # Helper functions and API integrations
Learning Objectives

This project explores:

Application of AI in genomics
Building scalable AI systems
Full-stack development for scientific tools
Integrating machine learning models into real-world applications
Future Improvements
Add full genome browser interface
Improve model explainability
Support batch mutation analysis
Enhance visualization of predictions
Optimize API performance and latency
Inspiration & Acknowledgment

This project was developed by studying and extending existing approaches in AI-driven genomic analysis. The implementation has been adapted and enhanced with additional features, system design, and deployment strategies.

Author

Richmond Addo Afari
Computer Science Graduate
Interested in AI, Cloud Engineering, and Applied Machine Learning

Final Note

This project represents a step toward building intelligent systems that bridge AI and real-world scientific problems, particularly in healthcare and genomics.
