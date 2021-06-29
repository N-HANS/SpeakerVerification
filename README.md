# SpeakerVerification
Speaker Verification Using Deep Learning

This repository is consistent with https://github.com/HarryVolek/PyTorch_Speaker_Verification

Instead of using TIMIT, we aim at use a large database, i.e., Librispeech/VoxCeleb, folowing the introduction in the above link (Preprocessing part). Without changing anything else, we replace "audio_path" to our speaker_ids list. The speaker_ids list is given in pickle file: create_audio_path_vox_lbr/audio_path_other.pkl

We used create_pkls.py to create the .pkl files that are consistent with the rest of the code. In another word, the new audio list are in the same format as that for TIMIT after loading in the .pkl files.

Then you can easily follow the "Training" section in above link, the default settings are ready for training. 

