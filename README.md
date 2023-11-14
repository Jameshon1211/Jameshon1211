- 👋 Hi, I’m @Jameshon1211
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Jameshon1211/Jameshon1211 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- The pre-trained model
!pip install transformers
!conda install -c huggingface transformers
!pip install torch 
!pip install chardet

from transformers import pipeline

classifier = pipeline("sentiment-analysis")
classifier("I am impressed how long this ink last and how fast the seller sent it to me. Not a hitch at all, fantastic.")
