---
title: "Dataset"
# date: 2020-09-15T11:30:03+00:00
weight: 2
# aliases: ["/first"]
tags: ["RAVDESS"]
categories: ["Dataset"]
# author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: true
hidemeta: false
comments: false
summary: "Dataset information"
description: "RAVDESS dataset"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: false
# ShowBreadCrumbs: true
ShowPostNavLinks: true

editPost:
    URL: "https://github.com/S-E-D-A-N/website/tree/main/content/"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

Ryerson Audio-Visual Database of Emotional Speech and Song ([RAVDESS](https://smartlaboratory.org/ravdess/))
Contains 1440 files: 60 trials per actor x 24 actors = 1440. The RAVDESS contains 24 professional actors (12 female, 12 male).
Speech emotions includes calm, happy, sad, angry, fearful, surprise, neutral and disgust expressions. (8 emotions)

## Filename identifiers 


    1. Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
    2. Vocal channel (01 = speech, 02 = song).
    3. Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
    4. Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the ‘neutral’ emotion.
    5. Statement (01 = “Kids are talking by the door”, 02 = “Dogs are sitting by the door”).
    6. Repetition (01 = 1st repetition, 02 = 2nd repetition).
    7. Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).


## Filename example 

**```02-01-06-01-02-01-12.mp4```** 
    
    1. Video-only (02)
    2. Speech (01)
    3. Fearful (06)
    4. Normal intensity (01)
    5. Statement “dogs” (02)
    6. 1st Repetition (01)
    7. 12th Actor (12)
    8. Female, as the actor ID number is even.
