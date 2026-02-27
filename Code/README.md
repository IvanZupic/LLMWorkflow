We provide Python code in the form of Jupyter notebooks to assist researchers implement the workflow. The notebooks use Open AI or Google Gemini API to process text data stored in a Google Drive folder. API Keys need to be acquired from the provider before calling API to process text. Researchers can run the code in Google Colab online environment. The process can be applied to any text data as long as it is provided in the form of pdf files. The only things researchers need to change in the code are (1) the prompt, (2) structure of the output file and (3) destinations of input/output files. 

The Jupyter notebook has four blocks, each can be run separately.
1.	Set up connection to the LLM and Google Drive. This block uses API Key set up in Colab secret variable. 
2.	Set up folders for input/output files.  Create output and processed list Excel files. Set up output table structure. This is the only block that needs changing when the process is applied on new data.
3.	Process all files in the designated Google Drive folder and write the results in the output Excel file. 
4.	Show the results in the output Excel file.

