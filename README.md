I have used TVSUMM video dataset which includes videos from multiple genres such as news, documentaries, how-to videos, and user-generated content
Initially i processed the vidoes using AssemblyAI Library, from AssemblyAI Library, you have to login there and get the API key, you can transcribed text from audio of video, the code is not available here. 
Then we processed the transcribed text in petrained model and generate summary, but before that we actually fine tune the checkpoints of model on benchmark dataset.
And finally, we calculated the avg precison, recall and fmeasure.
