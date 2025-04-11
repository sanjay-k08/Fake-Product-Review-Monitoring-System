# Fake-Product-Review-Monitoring-System
Online shopping platforms often host multiple versions of the same product from different sellers or manufacturers. Because reviews directly influence product reputation and sales, it's essential to filter out fraudulent or misleading reviews. Manually checking every review is impractical, hence the need for an intelligent, automated solution.
In the modern era of e-commerce, product reviews have become crucial in shaping purchasing decisions. However, the rise in fake or manipulated reviews poses a significant threat to both customers and platforms. Our Fake Product Review Monitoring System aims to address this issue by automatically detecting suspicious reviews using a combination of machine learning and rule-based checks.

# Detection Techniques

Dual View Reviews – Reviews that contain contradictory sentiments (both positive and negative).

User Bias – Detects users repeatedly promoting or demoting a specific brand.

IP Address Anomaly – Identifies promotion or demotion of a brand from the same IP address.

Flood Reviews – Detects a burst of reviews from the same user in a short span.

Time-Frame Clustering – Flags similar reviews posted within a narrow time window.

Meaningless Text Detection using LSA – Uses Latent Semantic Analysis to catch incoherent or low-value text.

# Machine Learning Model

 ML model uses Natural Language Processing (NLP) and statistical techniques to identify patterns of review fraudulence. It's built using Python and runs on a Jupyter Notebook.

# Installation Instructions

Make sure you have Python, Jupyter Notebook, Node.js, and MongoDB installed.

ML Model Setup
 
1. Clone the repository.

2. Open a terminal and install the required dependencies:
   
       pip install nltk pickle re pandas random

3. Run Jupyter Notebook:

        jupyter notebook

 # Fullstack Web App Setup

  Prerequisites
  
    MongoDB

    Node.js

    Cloudinary Account for media hosting

  Steps

  1. Clone the repository:
   
    bash
    git clone <repo-url>
    cd Wander-World
    npm install

  2. Set up environment variables by creating a .env file in the root directory:

         ini
         DATABASEURL='<your-mongodb-url>'
         API_KEY='<your-cloudinary-api-key>'
         API_SECRET='<your-cloudinary-api-secret>'

  3. Run MongoDB in a separate terminal:

         bash
         mangod

  4. Start the server:

         bash
         node app.js

  5. Visit the application at: http://localhost:3000


# TECH STACK 

Languages: Python, Node.js, HTML, CSS, EJS

Frontend: HTML, CSS, EJS Templating

Backend: Node.js, Express.js, MongoDB

ML/NLP: NLTK, Pandas, Pickle, Regular Expressions

Media Hosting: Cloudinary


# Features

Automated detection of fake reviews using six distinct logic checks

Real-time monitoring of review submissions

Fullstack web application for visualization and admin control

NLP integration to detect semantically meaningless content

Data stored securely with MongoDB

# Future Enhancements

Integrate with major e-commerce APIs for real-time review scraping

Deep learning models (BERT, LSTM) for improved language understanding

Enhanced UI for admin dashboard and analytics

User feedback integration for better classification accuracy
