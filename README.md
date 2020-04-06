# How Does Gender Balance In Training Data Affect Face Recognition Accuracy?
This repository contains all 42 trained models from the paper https://arxiv.org/abs/2002.02934.
The trained models vary in loss function, training dataset, and gender ratio.
It also contains the name of the images used to create the subset from the FRGC dataset.

Models are stored at https://drive.google.com/drive/folders/1BUpPkiUhnZ-tbfhd304Ttb-IFYTA_u3n?usp=sharing

To extract features using the models provided, use
https://github.com/vitoralbiero/face_matching/blob/master/insightface_feature_extraction.py

And to match features, use
https://github.com/vitoralbiero/face_matching/blob/master/mult_feature_match_list.py

You will need a copy of the InsighFace deploy folder from
https://github.com/deepinsight/insightface/tree/master/deploy

If you use any of the models or the FRGC subset please cite the paper below.

```
@misc{albiero2020does,
    title={How Does Gender Balance In Training Data Affect Face Recognition Accuracy?},
    author={Vítor Albiero and Kai Zhang and Kevin W. Bowyer},
    year={2020},
    eprint={2002.02934},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}
```
