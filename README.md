Public Health Dictionary & Communications Simplification Device 
1. Includes a comprehensive public health dictionary
2. Includes a Python script for replacing complex jargon with simplified definitions to enhance readability for the general public
   
Background: 
Public health information is vital for making informed health decisions. However, the dissemination of this knowledge is often hindered by complex language, over-the-top jargon, and unfamiliar acronyms and concepts, creating a barrier for the average layperson in accessing health data and research findings. To ensure populations have equitable access to scholarly literature and health information, I plan to make a device using python language learning models to translate complex text to decode and simplify scholarly public health texts. 

Project Components
The project will compile a dictionary with common public health terms, concepts, and acronyms. This will include statistical terms, methodologies, and the names and functions of key public health organizations. Each entry will be paired with a definition that is easily understood by the average reader. 
The project will integrate language simplification techniques to restructure complex sentences into simpler, more readable sentences. 
The device will return a text that replaces acronyms and complex jargon with the translated definitions, offering a more simplified text to read. 

The goal of this project is to allow people from all backgrounds to equitably access scholarly health texts, regardless of their academic background. This will help reduce knowledge gaps due to a mismatch in complex research findings and public reception and understanding. Furthermore, by providing a simpler translation of research data, the project aims to mitigate misinterpretations of research findings to prevent misinformation. Overall, this project aims to simplify public health communications and overcome barriers to accessing quality information. 

INSTALL: 
1. 'transformers' library by Hugging Face (BartForConditionalGeneration, BartTokenizer, pipeline)
2. 'nltk' Natural Language Toolkit (nltk.corpus, nltk.tokenize) 
4. 'string' module 

No external datasets are required as the data is already embedded as code within the Python dictionary. 

Check .gitbug/workflows/blank.yml for full code and commit history 
