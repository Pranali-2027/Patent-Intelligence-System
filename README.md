# Patent Innovation Predictor - Agentic AI Patent Trend Analysis System

## Overview

Patent Innovation Predictor is an agentic AI system that analyzes patent-related data to identify technology trends and forecast possible future innovation directions. The system uses a multi-agent workflow with CrewAI, local LLM inference using Ollama, and OpenSearch-based retrieval for patent intelligence analysis.

The project focuses on patent trend analysis, prior-art style retrieval, semantic search, and innovation forecasting for technology domains such as lithium battery innovation.

## Problem Statement

Patent research is time-consuming because users need to manually search large volumes of technical documents, compare prior-art information, identify technology trends, and summarize future innovation opportunities.

This project solves the problem by using AI agents that can retrieve patent information, analyze patterns, and generate structured insights for technology forecasting.

## Key Features

- Multi-agent patent research workflow
- Patent trend analysis for selected technology domains
- Semantic and hybrid search using OpenSearch
- Local LLM inference using Ollama
- CrewAI-based agent orchestration
- Embedding-based retrieval for patent intelligence
- Innovation forecasting based on retrieved patent patterns
- Structured text report generation
- Streamlit-based patent analysis application

## Tech Stack

- Python
- CrewAI
- Ollama
- OpenSearch
- RAG
- Embeddings
- Streamlit
- Docker
- LangChain-compatible workflows

## System Architecture

```text
User Query / Technology Domain
        |
        v
Patent Analyzer App
        |
        v
CrewAI Agent Orchestration
        |
        |-- Research Director Agent
        |-- Patent Retriever Agent
        |-- Data Analyst Agent
        |-- Innovation Forecaster Agent
        |
        v
OpenSearch Retrieval Layer
        |
        |-- Semantic Search
        |-- Hybrid Search
        |-- Iterative Search
        |
        v
Ollama Local LLM
        |
        v
Patent Trend Analysis Report