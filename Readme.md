# How to use this RAG AI Teaching assistant on your data
## step1 - Collect your videos
Move all your videi files to the videos folder 

## Step2 - Convert to mp3
converets all video files to mp3 by running video_to_mp3.py

## Step3 - Convert mp3 to json
Convert all mp3 files to json by running mp3_to_json.py

## Step4 - Convert the json files to vectors
Use the file process_json.py to convert the json files to a dataframe with Embeddings  and save it as a joblib pickle

## Step 5 - Prompt generation and feeding to LLM

Read the joblib file and load it into the memory. Then create a relavant prompt as perr the user query and feed it to the LLM

## step6 - Plz create videos folder, jsons folder, audios folder, before run all programs
