<h1 align="center">Integrate LLMs with applications</h1>
<div align="center">
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/Anaconda-3670A0?style=for-the-badge&logo=anaconda&logoColor=white">
<img src="https://img.shields.io/badge/IBM%20Cloud-005C8E?style=for-the-badge&logo=ibmcloud&logoColor=white">
<img src="https://img.shields.io/badge/Streamlit-FF4B5C?style=for-the-badge&logo=streamlit&logoColor=white">
<img src="https://img.shields.io/badge/License-MIT-yellowgreen?style=for-the-badge&logo=opensource&logoColor=white">
</div>

## 🚀 Requirements
   - load_dotenv==0.1.0
   - ibm_watson_machine_learning==1.0.345
   - ibm-cloud-sdk-core==3.16.7
   - streamlit==1.31.0
   - python-dotenv==1.0.0

     
Contoh Hasil
 ```bash
python demo_wml_api.py
   --------------------------------------------------------------------------- 
   Question/request: Write a paragraph about the capital of France.
Answer: The capital of France is Paris, a city of culture and politics. It is the seat of the French Government and of the French Parliament, and the country's largest city, with an area of 814 km2 . The city is located on the banks of the Seine, the administrative centre of the Île-de-France region.
---------------------------------------------------------------------------
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\ibm_watson_machine_learning\foundation_models\utils\utils.py:101: LifecycleWarning: Model 'meta-llama/llama-2-13b-chat' is in deprecated state from 2024-08-26 until None. IDs of alternative models: None. Further details: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-model-lifecycle.html?context=wx&audience=wdp
  warnings.warn(default_warning_template.format(
---------------------------------------------------------------------------
Prompt: 
    From the following customer complaint, extract 3 factors that caused the customer to be unhappy. 
    Put each factor on a new line. 

    Customer complaint:
            I just tried to book a flight on your incredibly slow website.  All 
            the times and prices were confusing.  I liked being able to compare 
            the amenities in economy with business class side by side.  But I 
            never got to reserve a seat because I didn't understand the seat map.  
            Next time, I'll use a travel agent!


    Numbered list of all the factors that caused the customer to be unhappy:

    
List of complaints: 1. Slow website
    2. Confusing times and prices
    3. Lack of understanding of the seat map
---------------------------------------------------------------------------
--------------------------Invocation with REST-------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Paris (; ; ) is the capital and largest city of France. Paris is located on the left bank of the Seine and covers an area of . It is considered the world's most populous commune (city) with an estimated population of 2,4 million.
---------------------------------------------------------------------------
PS C:\NiaSemester4\magang\Bulan3\Integrate> 
