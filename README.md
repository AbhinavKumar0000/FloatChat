FloatChat - AI-Powered Conversational Interface for ARGO Ocean Data Discovery and Visualization

Overview

FloatChat is an AI-powered conversational system designed to simplify access to and exploration of oceanographic data from the Argo program. By leveraging Large Language Models (LLMs), modern structured databases, and interactive visualization tools, FloatChat enables users to query and visualize Argo float data in NetCDF format using natural language. This project aims to democratize ocean data access, making it intuitive for researchers, students, and the public without requiring extensive domain knowledge or technical expertise.

Features





Natural Language Queries: Ask questions about Argo float data (e.g., temperature, salinity, or biogeochemical variables) in plain English.



Data Visualization: Generate charts, maps, and interactive dashboards based on user queries.



NetCDF Integration: Seamlessly processes Argo data stored in NetCDF format.



Scalable Database: Uses a structured database to efficiently handle large-scale oceanographic datasets.



User-Friendly Interface: Built with modern web technologies for accessibility and ease of use.

Installation

Prerequisites





Python 3.8+



Node.js 16+ (for frontend)



PostgreSQL or similar database



Libraries: netCDF4, pandas, numpy, transformers (Hugging Face), plotly, dash



API keys for LLM provider (e.g., OpenAI, Hugging Face)

Querying Data

Use the web interface to enter natural language queries like:





"Show me the temperature profile for Argo floats in the Pacific Ocean in 2024."



"Visualize salinity data for floats near the Gulf Stream."

The system processes the query using an LLM, retrieves relevant data from the database, and generates visualizations.

Visualizations





View interactive charts and maps powered by Plotly and Dash.



Export visualizations as images or data files for further analysis.

Acknowledgments





https://argo.ucsd.edu/ for providing open oceanographic data.



https://huggingface.co/ for LLM tools and models.



https://dash.plotly.com/ for interactive visualizations.
