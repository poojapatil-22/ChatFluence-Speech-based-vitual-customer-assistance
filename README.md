**Project Title: VoizAssist - A Speech-to-Speech Customer Virtual Assistant**

**Project Overview:**
VoizAssist is an innovative speech-to-speech chatbot designed to function as a Customer Virtual Assistant (CVA), aimed at enhancing the customer support experience for e-commerce platforms. Leveraging cutting-edge natural language processing (NLP) techniques and machine learning, VoizAssist provides a seamless and interactive communication channel between customers and businesses. The chatbot is specifically designed to manage and resolve order-related queries efficiently by utilizing advanced speech recognition and synthesis technologies.

**Key Features:**

1. **Speech Recognition:**
   - VoizAssist captures user input using the Google Speech-to-Text API, converting spoken language into text for processing.

2. **Text Classification:**
   - The chatbot classifies user intent through TF-IDF vectorization and an SVM (Support Vector Machine) classifier, trained on a labeled dataset. This enables accurate understanding and categorization of customer inquiries.

3. **Response Generation:**
   - Based on the classified intent, VoizAssist generates appropriate responses using a pre-trained model. The model maps the recognized intents to corresponding responses stored in a well-defined knowledge base.

4. **Text-to-Speech:**
   - VoizAssist delivers its responses audibly using the Google Text-to-Speech API, converting text-based replies into natural-sounding speech.

5. **User Interface:**
   - The chatbot features an intuitive and responsive front-end interface built with HTML, CSS, and Bootstrap, ensuring an engaging user experience.

**Technologies Used:**

- **Backend:**
  - **Python:** Core language for building the chatbot logic and backend functionalities.
  - **TensorFlow:** Employed for TF-IDF vectorization.
  - **scikit-learn:** Utilized for SVM classification of user intents.
  - **Flask:** Web framework for handling HTTP requests and serving the chatbot application.

- **Natural Language Processing (NLP):**
  - **TF-IDF Vectorization:** Technique for text classification.

- **Machine Learning:**
  - **Support Vector Machine (SVM) Classification:** Model used for classifying user intents.

- **Speech Services:**
  - **Google Speech-to-Text API:** Captures and transcribes user speech.
  - **Google Text-to-Speech API:** Converts text responses into speech.

- **Front-end:**
  - **HTML, CSS, Bootstrap:** Technologies used to create the user interface for interacting with the chatbot.
