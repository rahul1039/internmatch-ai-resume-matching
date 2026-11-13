# InternMatch – AI-Powered Resume–Internship Matching Platform

An AI-powered platform that intelligently matches candidate resumes with relevant internship opportunities using Natural Language Processing (NLP), Sentence Transformers, and FAISS vector search.

## Overview

InternMatch simplifies the internship discovery process by analyzing candidate resumes and matching them with suitable internship opportunities based on semantic similarity rather than simple keyword matching.

The platform uses MiniLM embeddings and FAISS for efficient semantic retrieval, along with Google Gemini for AI-powered career guidance and skill-gap analysis.

## Key Features

- **Resume Analysis:** Extracts relevant information and skills from candidate resumes.
- **Semantic Matching:** Matches resumes with internship descriptions using Sentence Transformers.
- **Vector Search:** Uses FAISS for efficient similarity-based retrieval.
- **AI-Powered Career Guidance:** Integrates Google Gemini to provide career-related insights.
- **Skill-Gap Analysis:** Identifies potential skill gaps between candidate profiles and internship requirements.
- **Internship Recommendations:** Retrieves relevant opportunities from a collection of 120 internship postings.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Backend | FastAPI |
| Frontend | HTML, CSS, JavaScript |
| NLP & Embeddings | Sentence Transformers, MiniLM |
| Vector Database | FAISS |
| Generative AI | Google Gemini |
| Retrieval | Semantic Search, Vector Similarity |

## System Architecture

```text
       Candidate Resume
              |
              v
       Resume Processing
              |
              v
     Text & Skills Extraction
              |
              v
     MiniLM Embedding Model
              |
              v
       Vector Embeddings
              |
              v
        FAISS Retrieval
              |
              v
    Internship Recommendations
              |
       +------+------+
       |             |
       v             v
  Skill-Gap      Semantic
   Analysis       Matching
       |             |
       +------+------+
              |
              v
      Google Gemini
              |
              v
     Career Guidance
```

## Performance
