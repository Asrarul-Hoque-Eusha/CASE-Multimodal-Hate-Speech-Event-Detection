# CASE-Multimodal-Hate-Speech-Event-Detection
We **CUET_Binary_Hackers** have participated in CASE Multimodal Hate Speech Event Detection in CASE EACL 2024 securing promising positions. [**Check the results here**](https://codalab.lisn.upsaclay.fr/competitions/16203#results). Two screenshots of standings are added in the last section.

## Task Descriptions
Hate speech detection is one of the most important aspects of event identification during political events like invasions. In the case of hate speech detection, the event is the occurrence of hate speech, the entity is the target of the hate speech, and the relationship is the connection between the two. Since multimodal content is widely prevalent across the internet, the detection of hate speech in text-embedded images is very important. Given a text-embedded image, this task aims to automatically identify the hate speech and its targets. This task will have two subtasks.

### Sub-task A: Hate Speech Detection
The goal of this task is to identify whether the given text-embedded image contains hate speech or not. The text-embedded images, which are the dataset for this subtask, will have annotations for the prevalence of hate speech.

### Sub-task B: Target Detection

The goal of this subtask is to identify the targets of hate speech in a given hateful text-embedded image. The text-embedded images are annotated for "community", "individual" and "organization" targets.

## Our Approach
In these multimodal tasks organizers gave OCR texts of text embedded images. We have employed both textual and multimodal models to classify these text embedded images. In to train and get output from textual models we have only used OCR texts. While in multimodal (text+visual) models we trained and get output from the models using both text and images. At first we have explored the dataset through different visualization methods. We have gone through different preprocessing steps for text and images. Then we have fed this preprocessed data to the models for training purpose.
### Models We Have Experimented
#### Textual Model
+ **XLM-R**
#### Visual Models
1. **LSTM-ATTN + VGG16**
2. **XLM-R + VGG16**
##### Subtask A
![image](https://github.com/user-attachments/assets/6d30dc4f-55c7-45b7-9530-4559a083e1f5)

##### Subtask B
![image](https://github.com/user-attachments/assets/c13a6b16-a5e4-4282-be51-de97bb5abd9e)

