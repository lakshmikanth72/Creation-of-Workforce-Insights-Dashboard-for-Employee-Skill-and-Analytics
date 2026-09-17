# Creation of Workforce Insights Dashboard for Employee Skill and Analytics

## Project Overview

The **Creation of Workforce Insights Dashboard for Employee Skill and Analytics** is an AI-powered workforce analytics and talent intelligence solution developed to help HR teams understand employee data, analyze workforce trends, identify employee attrition risk, and support data-driven workforce decisions.

The project combines:

- Data Analytics
- Data Cleaning and Preprocessing
- PostgreSQL Database
- Power BI
- Machine Learning
- Employee Attrition Prediction
- Risk Classification
- Retrieval-Augmented Generation (RAG)
- Large Language Model (LLM)
- FastAPI
- AI HR Assistant
- Web Application Deployment

The system works with an HR employee dataset containing **1,470 employee records** and transforms the data into meaningful analytics, machine-learning predictions, risk insights, and an interactive AI assistant.

---

## Problem Statement

HR teams have large amounts of employee information related to performance, salary, satisfaction, experience, attendance, job roles, and attrition.

However, analyzing these different factors manually can make it difficult to identify important workforce patterns and potential attrition risks.

This project aims to provide a centralized workforce analytics solution that helps HR teams:

- Understand workforce composition
- Analyze employee attrition
- Analyze employee performance
- Study employee satisfaction
- Identify potential attrition risk
- Understand workforce trends
- Support employee retention strategies
- Ask workforce-related questions using an AI assistant

---

## Project Objectives

1. Clean and preprocess the employee dataset.
2. Perform exploratory data analysis to understand workforce patterns.
3. Store structured workforce information in PostgreSQL.
4. Create interactive Power BI dashboards.
5. Develop machine-learning models for employee attrition prediction.
6. Generate attrition probabilities and employee risk categories.
7. Implement Retrieval-Augmented Generation (RAG).
8. Integrate a Large Language Model for natural-language responses.
9. Develop an AI HR Assistant using FastAPI.
10. Deploy the AI assistant as a web application.

---

# Project Workflow

```text
Raw HR Dataset
      |
      v
Data Understanding
      |
      v
Data Cleaning & Preprocessing
      |
      v
Exploratory Data Analysis
      |
      +------------------------+
      |                        |
      v                        v
PostgreSQL Database       Machine Learning
      |                        |
      |                        v
      |                Attrition Prediction
      |                        |
      |                        v
      |                 Risk Classification
      |                  Low / Medium / High
      |
      v
Power BI Dashboard


                 AI HR Assistant
                       |
                       v
                    FastAPI
                       |
                       v
                 Question Router
                  /            \
                 /              \
                v                v
         PostgreSQL              RAG
             |                   |
             |             knowledge.txt
             |                   |
             |          TF-IDF + Cosine
             |             Similarity
             |                   |
             +--------+----------+
                      |
                      v
                 Gemini LLM
                      |
                      v
                AI Response
