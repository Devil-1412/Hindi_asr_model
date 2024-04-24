# Hindi_asr_model
This is an asr model implemented using whisper module from openai, it transcripts the hindi audio files into hindi transcriptions text files containing audio files and their respective transcription.
Also this repository has asr evaluation file which can be used to compute the WER of the asr transcriptions when compared to referenced transcriptions, Though i was given the task to use the asr-evaluation but it couldn't be accomplished because of the codec formats required by the model, therefore i used the jiwer module to import wer and used it to compute the wer.
The transcription provided by the model greatly depends on the model used that can range between small, medium, large, large-v2, large-v3 (base and tiny model doesn't yield significant results). Better models get us better results but it obviously takes lot of time 10+ hours for 1000 files for medium+ models in an 8 gb ram system.
I've computed the wer score for Kathbath hindi audios using small model which yielded around 56.19170415889388% score which is very high but I've used small model so it's justified.
In the end I learned a lot about the need of efficient systems which ccan greatly increase the performance and reduce the time consumed at the same time
