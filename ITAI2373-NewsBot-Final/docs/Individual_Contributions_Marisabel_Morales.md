# Individual Contributions – Marisabel Morales

**Team:** Purple Berries (Marisabel Morales, Khalida Bestani, Sadea Saeed)  
**Course:** ITAI 2373 – Natural Language Processing Final Project

## Team Division of Work

| Member | Main Responsibilities |
|---|---|
| **Khalida Bestani** | Module A – Advanced Content Analysis; collaboration on Module D and overall NLP integration |
| **Sadea Saeed** | Module B – Summarization and Semantic Search |
| **Marisabel Morales** | Module C – Multilingual Intelligence; collaboration on Module D; Streamlit Web Application development, integration, testing, and deployment |

## My Contribution in Detail

### Individual Contribution – Marisabel Morales

My main contributions to NewsBot Intelligence System 2.0 focused on **Module C (Multilingual Intelligence)** and the **development of the Streamlit web application**. I also collaborated on Module D, the conversational interface.

For the multilingual component, I worked on the project's language detection and translation workflow, which allows news articles written in different languages to be translated into English and processed by the NLP system. This feature helps users analyze content beyond English-language news.

I also took responsibility for turning our working Google Colab project into a browser-based application. Using **Python and Streamlit**, I brought the four existing NLP modules into one interface: **Analyze News, Summarize & Search, Multilingual Analysis, and Chat with NewsBot**. I developed the purple-and-blue interface, integrated the modules into the web experience, tested the main workflows, and prepared the project for deployment through GitHub and Streamlit Community Cloud.

One important part of the deployment was separating the data used for our academic evaluation from the public demonstration. Our original academic project used **1,440 BBC News articles after duplicate removal**. The public web app uses **300 attributed Wikinews excerpts** instead. Because the application models operate on the active corpus, the academic BBC evaluation scores should not be presented as performance measurements for the public demo.

The application is publicly accessible here:

- **Live Web Application:** https://newsbot2-webapp.streamlit.app/
- **GitHub Repository:** https://github.com/Mari-XR/NewsBot2-WebApp

## Challenges I Solved

My biggest challenge was moving from a notebook that worked in Google Colab to a complete web application that other people could open and use. I needed to connect the existing NLP functionality to interactive pages while keeping the original behavior intact.

I also worked through Python dependency and deployment issues, tested that the four modules functioned correctly, and verified that translation and follow-up questions in the chatbot continued to work in the web interface. Preparing a separate dataset for the public demonstration was another important step.

## What I Learned

Through this project, I learned how different NLP techniques can work together in one application and how to make those capabilities accessible to users who do not write Python code.

I strengthened my understanding of multilingual text processing, the connection between a model and a user interface, application testing, and deployment with GitHub and Streamlit Community Cloud. Most importantly, I learned how to take a class project beyond the notebook and turn it into a working interactive demonstration that people can access through a browser.
