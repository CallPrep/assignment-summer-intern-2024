## Semantic Search Assignment: Summer 2024

This assignment evaluates your ability to learn and apply concepts in building a semantic search system . We'll be focusing on frameworks suitable for beginners like FastAPI, making it easier to jump in. It is compulsory to use a Python framework. If you are new to this, FastAPI is easiest to learn.

**The Objective:**

Develop a web application that performs semantic search on case study documents related to a fictitious company, MindTickle. The system should prioritize relevant results based on meaning and context, not just exact keyword matches.

**Here's what you'll build:**

1. **APIs:**
    - `POST: /upload`: This API allows uploading new case study documents to the system. The file will be uploaded as form-data in PDF format.
    - `GET: /docs?q=<query>`: This API takes a search query and returns a list of relevant case study **document names**, not the entire documents.

2. **Data:**
    - Sample case studies are provided in the `/samples` folder, focusing on various industries, geographies, and use cases (e.g., healthcare CRM, training remote sales teams).
    - You can assume additional case studies will be uploaded for testing.
    - It is available in HTML format for readibilty, decide how you want to clean it.
**Optional Enhancements:**

- **Large Language Model (LLM) Integration:** Explore ways to leverage LLMs to improve search accuracy. We will like to see your creativity of how can keep the use of LLMs to minimum while improving the accuracy. Their are various platoforms which provide apis for open souce LLM models free to a great extent. You dont have to train your models but if you can finetune any of embeddings or LLM, that will be a huge plus. You can focus on optimizing queries for the following aspects:

    - **Industry:** Search results should effectively identify case studies relevant to specific industries (e.g., healthcare, CRM).
    - **Use Case:** The system should prioritize studies that address particular use cases (e.g., training remote sales teams).
    - **Geography:** Search should consider the geographical focus of case studies (e.g., Asia, India).

**Evaluation Criteria:**

- **Functionality:** Successful implementation of the `/upload` and `/docs` APIs.
- **Accuracy:** Ability of the system to return relevant case study names based on the search query's intent and meaning. This will be tested automatically using a script.
- **Bonus:** Dockerizing the application for easy deployment (not mandatory).

**Hints To Get Started Started:**


1. **Explore Semantic Search Libraries**

2. **Document Embedding** 

3. **Search Implementation** 

6. **Database Selection:** Choose a database of your choice (e.g. PineCone, ElasrticSearch etc.) to store the document embeddings and potentially document metadata (optional). How and which db you choose will also be an interesting thing. 


**Example:**

* **Query:** "How can we train our remote sales team in Asia?"
* **Expected Results:** The system should return a list of relevant case study names, potentially including "Training Strategies for Remote Sales Teams in APAC" or "Onboarding New Sales Reps in a Remote Setting."

**Further Questions?**

If you have any doubts or require clarification, reach out to Nikhil at nikhil@callprep.io with the subject line "Assignment Summer 2024".

**Remember:** 
- This assignemnt mentions a lot of terms you all will be hearing for the first time, but if you take some time to learn, it will be a breeze. **Remember:** Its not testing your AI skills but how fastg you can learn and implement.
- Start with a basic implementation and gradually improve it.
- Focus on learning and applying new concepts throughout the assignment.
- Don't hesitate to reach out for help if needed.
