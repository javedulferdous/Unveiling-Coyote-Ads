# Unveiling Coyote Ads: Detecting Human Smuggling Advertisements on Social Media

### Abstract
<div align="justify"> 

Human smuggling is a grave social issue that carries several negative ramifications for many countries across the globe. Human smugglers operating on the United States-Mexico border, known as ‘coyotes’, are increasingly relying on online social media to advertise their services, so automatically detecting such advertisements related to this illicit activity is crucial for devising effective countermeasures. However, identifying human-smuggling advertisements is not straightforward as they are often disguised as innocent travel or tourism-related adverts in regional languages. Moreover, there are no readily available datasets that can train models to recognize such adverts automatically. This paper addresses both these issues as follows. First, we built a novel dataset comprising both coyote ads and legitimate travel/tourism adverts by leveraging different sources, including the Web, NGOs, and regional connections in countries with high human-smuggling activities. Specifically, our dataset contained an equal number (1000 images plus 500 videos) of coyote ads and legitimate travel ads, all of which contained embedded textual information. Using this dataset, we trained and assessed several state-of-the-art baseline models, including GPT-4, Gemini, and CLIP. For the image ads, the highest F1 score achieved by a model was 0.92, and for the video ads, the highest achieved F1 score was 0.86. We also conducted an in-depth analysis of the model performances to gain comprehensive insights into their respective strengths and weaknesses.
</div>

### Dataset

Dataset can be found [here](https://drive.google.com/drive/folders/148ERleY0Vq6O2g75vAjhLfdNgomjno6i).

### Blog Post

2024-12-12: Unveiling Coyote Ads: Detecting Human Smuggling Advertisements on Social Media (https://ws-dl.blogspot.com/2024/12/2024-12-12-unveiling-coyote-ads.html)

### Bibtex

```
@inproceedings{kodandaram2024unveiling,
  title={Unveiling Coyote Ads: Detecting Human Smuggling Advertisements on Social Media},
  author={Kodandaram, Satwik Ram and Sunkara, Mohan and Ferdous, Javedul and Poursardar, Faryaneh and Ashok, Vikas},
  booktitle={Proceedings of the 35th ACM Conference on Hypertext and Social Media},
  pages={259--272},
  year={2024}
}
```
