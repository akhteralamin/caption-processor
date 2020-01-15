### caption-processor
This is offline closed caption processor. This processor will linearize the caption text in different format of caption. Then feed the file into different caption analyzer such as ACE, SCLITE and others. Our goal is to analysis between ground truth and caption transcription.
### Caption Reader
1. Create a Python environment with python 3.6/3.7
2. Activate the environment before jumping into the code execution
3. Run the command below
Command: 

```python bulk_caption_file_converter.py -dir [Directory name where the srt files resides]```

As example: While reading srt files from "Hypothesis Caption SRT" directory our execution command will be like this:

```python bulk_caption_file_converter.py -dir Hypothesis```
