# MEDIC Dataset

## Overview

The MEDIC dataset is an invaluable resource for the computational analysis of empathy in psychotherapy. It is specifically designed to address the gap in datasets that focus on empathic interactions between counselors and clients, which are crucial for successful psychotherapeutic processes.

## Dataset Description

The MEDIC dataset is a multimodal collection derived from face-to-face psychological counseling sessions. It consists of 771 video clips, capturing the dynamic and complex nature of therapeutic interactions.

## Dataset Composition

The dataset is organized into five primary components within the MEDIC dataset folder:

1. **Text Folder**: Contains textual data corresponding to each sample.
2. **Audio Features Folder**: Includes audio features of each sample.
3. **2P Audio Features Folder**: Stores audio features with two-party (2p) interactions, where different speakers' features are separated.
4. **2P Keypoints Features Folder**: Consists of visual keypoints features related to two-party interactions.
5. **Labels.csv File**: Provides the labels corresponding to each dataset sample.

## Labels and Annotations

Three labels are proposed to describe the degree of empathy between counselors and their clients:

1. **Expression of Experience**: Assesses whether the client has expressed experiences that can trigger empathy.
2. **Emotional Reaction**: Indicates the counselor’s empathic emotional reaction.
3. **Cognitive Reaction**: Represents the counselor’s empathic cognitive reaction.

These labels are instrumental in analyzing and understanding the empathic interactions in the counseling sessions.

## Detailed Structure

- **Total Samples**: 771
- Each sample includes the following:
  - **Text**: Narrative or descriptive text data.
  - **Visual Features**: Data related to visual aspects.
  - **Audio Features**: Comprises complete MFCC (Mel-Frequency Cepstral Coefficients) features for each audio sample.
  - **Labels**: Specific labels associated with each sample for classification or identification purposes.

### Audio Features Specifics

- The audio features are further distinguished into individual and two-party (2p) components:
  - **Individual Audio Features**: Standard MFCC features for each sample.
  - **Two-Party Audio Features (2p_audio_feature)**: Includes MFCC features with the audio of different speakers separated for more nuanced analysis.
    - Filenames ending in '_con.npy' correspond to features associated with the counselor.
    - Filenames ending in '_cli.npy' correspond to features associated with the client.

### Visual Features Specifics

- **Two-Party Keypoints Features (2p_keypoints_feature)**: This folder contains visual keypoints data, particularly focusing on scenarios involving interactions between two parties (e.g., counselor and client).

## Usage

This dataset is ideal for research in fields such as conversational analysis, behavioral studies, and multimodal machine learning. It provides a rich source of data for training models that require a combination of textual, audio, and visual inputs.

## License and Agreement

To use the MEDIC dataset, users are required to sign an agreement, which encompasses the terms of use and licensing conditions. To download this database, you need to print the [agreement](https://nvie.ustc.edu.cn/doc/release_agreement_nvie.pdf), sign it and send it to us.

## Contact Us

For any inquiries about the MEDIC dataset, please contact:

- **Jiahe Wang** (In charge of the database): [wangjiahe317@mail.ustc.edu.cn](mailto:wangjiahe317@mail.ustc.edu.cn)
- **Shangfei Wang**: [sfwang@ustc.edu.cn](mailto:sfwang@ustc.edu.cn)

**Official Website of our Research Group**: USTC-AC

