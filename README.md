
# Project Documentation: Personalized Chatbot with Dynamic Responses
  ## Graduation Project of Generative AI Professional Track 🎓
  
# Team Members
## Esraa Samir Amin
## Rahma Abdulla Ramadan Ahmed
## Mohamed Hesham Ismail
## Ahmed Abdelrahman Abdelfattah Azab
## Mariam Essam Abdelaziz
## Mostafa Ebrahim Abdelrahman

# ⦁ Project Idea  
This project aims to build a Personalized Chatbot with Dynamic Responses using fine-tuning techniques on Hugging Face datasets. Specifically, it is a Multilingual Medical Assistant with LoRA-Optimized FastLanguageModel (Gemma-7B PEFT). The chatbot leverages efficient inference techniques like 4-bit quantization for performance optimization and RoPE scaling to handle extended conversations.

## ⦁	Brief Description of the Problem Being Solved:
In the medical field, patients, healthcare providers, and professionals frequently encounter complex medical terminology and abbreviations that are not easily understood without specific expertise. Moreover, accessing accurate and up-to-date medical information across different languages can be challenging, especially in multilingual environments. This can lead to misunderstandings, incorrect diagnoses, or a delay in obtaining proper medical advice. The issue is further compounded by the lack of user-friendly platforms capable of providing real-time, accurate medical information in a way that is accessible to both professionals and the public.

## ⦁	Overview of the Proposed Solution (High-Level Idea):
This project proposes a multilingual medical chatbot that leverages Generative AI to respond to medical inquiries in real-time, providing accurate, context-aware explanations of medical terminology, abbreviations, symptoms, diagnoses, and treatments. The system is built on top of the Gemma-7B model—a powerful language model fine-tuned using the MeDAL   dataset (Medical Dataset for Abbreviation Disambiguation)—and is optimized using LoRA (Low-Rank Adaptation) to reduce memory usage and speed up processing. The chatbot is integrated with a Streamlit-based user interface, which allows users to input queries in multiple languages and receive comprehensive medical information instantly.

## ⦁	 Unique Value Proposition:
The project's unique value lies in its ability to:
   ### ⦁	Medical Expertise and Abbreviation Disambiguation: 
   Unlike general-purpose chatbots, this system is trained specifically on MeDAL, a specialized dataset focused on medical abbreviations 
   and terminology, ensuring high accuracy when dealing with complex medical jargon.
   
