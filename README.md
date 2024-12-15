**ChatBot with Open AI, LanhChain and PlayHT**

- https://colab.research.google.com/drive/1LS-w4UuAWRQfX_zM1WHXdCfofleI91g0?usp=sharing

---

**Handbook for Troubleshooting Errors (If any)**

- [ChatBot with Open AI and LangChain Handbook](https://www.notion.so/36aee0b81838457e91a14c4ddf3378ce?pvs=21)
- [ChatBot with Open AI, LanhChain and PlayHT](https://www.notion.so/ChatBot-with-Open-AI-LangChain-and-PlayHT-b518566d30194da093bd1b21f82085a4?pvs=21) Handbook

---

## **Nutz and Bolts for Generative AI Applications**

- **Google Colab:** It is a cloud-based platform by Google designed for running and sharing Jupyter notebooks.
    - **Steps for** **creating Google Colab Notebook:**
        
        Creating a “Google Colab notebook” is a straightforward process. Here are the steps to create one:
        ****
        
        - Open - https://colab.research.google.com/
        - Login with your Google Account
        - Rename your Notebook and start writing the code
        - Click on File
        - From the results, select New Notebook

- **Open AI:** An AI-based chat service powered by Open AI's language model.
    - **Steps for creating Open AI Account:**
        
        Here are the general steps you can follow to create an “OpenAI” account:
        
        - Open https://openai.com/
        - Click on Sign Up
        - Click Sign In with Google
        - Below options will be show
            
            ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/00f2e3f9-9819-4e20-9e40-6d0920ca6361/Untitled.png)
            
        - Click on API

- **Pinecone:** A scalable vector database service designed for efficient similarity search in high-dimensional data.
    - **Steps for creating Pinecone Account:**
        
        Here are the general steps to create a Pinecone account:
        
        - Open https://www.pinecone.io/
        - Click on Sign Up Free Button
        - Click on continue with Google

- **PlayHT:** PlayHT is a platform that allows you to clone voices using artificial intelligence. The platform uses a deep learning model to train a voice clone that sounds almost exactly like the original voice.
    - **Steps for creating PlayHT Account:**
        
        Following are the steps for creating an account for “PlayHT Account”:
        
        - Open https://play.ht/
        - Click on Login
        - Since you don’t have an account, click on the Sign Up button
        - Click on Sign Up with Google
        - Account will be created
        - **How to Clone a Voice in PlayHT:**
            
            Here's a general outline of the steps involved in voice cloning in PlayHT:
            
            - Before cloning, get ready with a 45-seconds clean audio
            - Open https://play.ht/studio/voice-cloning
            - Click on Create a New Clone
            - Click on Instant
            - Enter Voice Name and Upload the File
            - Click on Create
            - Your voice will be cloned

- **HuggingFace:** An organization known for its popular library providing easy access to pre-trained models and natural language processing tools.
    - **Steps for creating HuggingFace Account:**
        
        To create a Hugging Face account, you can follow these general steps:
        
        - Open https://huggingface.co/
        - Click on Sign Up
        - Enter your details and Click on Sign Up
        - Enter Your Details and Submit
        - Click on your Profile, and you can create your spaces
        - **Steps for creating Access Token in Hugging Face:**
            - Login to Hugging Face
            - Open https://huggingface.co/settings/tokens
            - Click on New token
            - Add a name for Token
            - Choose Role for Token whether to Read or Write
            - Click on Create
            - **Adding Secret Variables in Hugging Face Account:**
                - Create a Space Or Open your existing Space
                - Click on Settings Button
                - Checkout to **Variables and secrets** section
                - Create New Secrets
                - To access, we can use the below format
                    
                    ```jsx
                    OPENAI_API_KEY = os.getenv('OPENAI_API_KEY')
                    ```
                    
        - **How to embed your Gradio App using Hugging Face in your Client Application:**
            - Open the the space
            - On Top Right Side you can see the icon
            
            ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/00c4bc8e-09d2-4ed9-a9da-9cfcee48cfb8/Untitled.png)
            
            - Click on Embed this space
            - You will get different options to embed
            
    
- **LangChain:** A library for building and training language models.
    
    Open: 
    

- **Gradio:** An open-source library for building and sharing customizable web interfaces for machine learning models.
    
    Open: https://www.gradio.app/
