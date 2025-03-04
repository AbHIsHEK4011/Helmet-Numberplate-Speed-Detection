# Project Name

## Overview
An AI-driven interview assistant that automates candidate evaluation by analyzing resumes and job descriptions to generate tailored interview questions. It integrates with scheduling services, dynamically refines questions based on panel input, and ensures contextual relevance, enhancing recruitment efficiency.

## Features
- Upload a `.txt` file containing a job description.
- Upload a `.pdf` file containing a candidate's resume.
- Extract structured skills, topics, and subtopics relevant to the job description.
- Uses OpenAI's structured output format with Pydantic models.
- Returns the extracted information in a well-organized JSON format.

## Installation

### Prerequisites
- Python 3.10.11
- OpenAI API Key
- Dependencies: FastAPI, Uvicorn, PyPDF2, OpenAI


## Technologies Used
- **FastAPI** - Web framework
- **Uvicorn** - ASGI server
- **PyPDF2** - PDF text extraction
- **OpenAI API** - AI-driven structured data extraction
- **Pydantic** - Data validation and serialization

## License
This project is licensed under the MIT License.
