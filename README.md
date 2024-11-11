# Automatic-Speech-Recognition
Automatic Speech Recognition using wav2vec2 xlsr-large-53 model for Vietnamese using [VIVOS](https://www.kaggle.com/datasets/kynthesis/vivos-vietnamese-speech-corpus-for-asr) dataset


XLSR version:
We use [xlsr-large-53](https://huggingface.co/facebook/wav2vec2-large-xlsr-53) model from facebook. The xlsr model is finetuned from the base wav2vec2 model for multiple languages. We create our own [vocab.json](https://github.com/vutl/Automatic-Speech-Recognition/blob/main/vocab.json) file which containes all Vietnameses letters.

The result can be seen in the image below
![image](https://github.com/user-attachments/assets/9f511330-2012-48c8-b17d-a24290127e94)


Vietnamese Version:
We use [CuongLD](https://huggingface.co/CuongLD/wav2vec2-large-xlsr-vietnamese?fbclid=IwY2xjawGb_TBleHRuA2FlbQIxMAABHUr9zrZQMK7sqo_NOPgqTaWDTkkFqVjUFCA_FeL2mCMp9GWoxAf_egZvgw_aem_MJlIrNT7HykJ33nz2aoFCw) model which is finetuned from the  wav2vec2-large-xlsr-53 on Vietnamese using the Common Voice, Infore_25h dataset.
