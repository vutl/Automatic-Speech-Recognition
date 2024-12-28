# Automatic-Speech-Recognition
Automatic Speech Recognition using wav2vec2 xlsr-large-53 model for Vietnamese using [VIVOS](https://www.kaggle.com/datasets/kynthesis/vivos-vietnamese-speech-corpus-for-asr) dataset

#Note: There are other models. Including for gender vocal classification and our own finetuned model for Vietnamese.
For details: see the link below:
[Model](shttps://docs.google.com/spreadsheets/d/1hMqu_Xkp29MqBc26DFGs4Y-D06vITc7r3ZR0oe1rKxA/edit?gid=0#gid=0)

XLSR version:
We use [xlsr-large-53](https://huggingface.co/facebook/wav2vec2-large-xlsr-53) model from facebook. The xlsr model is finetuned from the base wav2vec2 model for multiple languages. We create our own [vocab.json](https://github.com/vutl/Automatic-Speech-Recognition/blob/main/vocab.json) file which containes all Vietnameses letters.

The result can be seen in the image below
![Screenshot 2024-11-11 101728](https://github.com/user-attachments/assets/78957128-1f8c-46bd-b599-245877b37668)



Vietnamese Version:
We use [CuongLD](https://huggingface.co/CuongLD/wav2vec2-large-xlsr-vietnamese?fbclid=IwY2xjawGb_TBleHRuA2FlbQIxMAABHUr9zrZQMK7sqo_NOPgqTaWDTkkFqVjUFCA_FeL2mCMp9GWoxAf_egZvgw_aem_MJlIrNT7HykJ33nz2aoFCw) model which is finetuned from the  wav2vec2-large-xlsr-53 on Vietnamese using the Common Voice, Infore_25h dataset.

The checkpoints for the XLSR version are in the [wav2vec2-vivos](https://github.com/vutl/Automatic-Speech-Recognition/tree/main/wav2vec2-vivos) folder
