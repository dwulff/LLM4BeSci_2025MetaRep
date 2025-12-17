## LLM4BeSci at MetaRep, MPIB Berlin, Dec 2025

![cover image](cover_metarep.png)

The course introduces the use of open-source large language models (LLMs) from the Hugging Face ecosystem for research in the behavioral and social sciences. 

Help by [Dirk Wulff](https://www.mpib-berlin.mpg.de/person/93374/2549)<br>
Materials by [Dirk Wulff](https://www.mpib-berlin.mpg.de/person/93374/2549), [Zak Hussain](https://zak-hussain.github.io/), [Taisiia Tikhomirova](https://www.mpib-berlin.mpg.de/person/131137/2549), and [Valentin Kriegmair](https://www.mpib-berlin.mpg.de/person/valentin-kriegmair/63440)

### Schedule

#### Day 1
<font style="font-size:10">02:00 PM - 02:45 AM: Welcome & Intro<br>
02:30 PM - 03:45 PM: [Talk: Intro to LLMs]()<br>
03:45 PM - 04:00 PM: Break<br>
04:00 PM - 04:30 PM: [Talk: A gentle intro to Hugging Face and Python]()<br>
04:30 PM - 04:45 PM: Setup Colab<br>
04:45 PM - 05:30 PM: [Exercise: Running pipelines]()<br>
05:30 PM - 06:00 PM: Walkthrough<br>
           07:00 PM: Dinner (self-paid)<br> 

#### Day 2
09:30 AM - 10:00 AM: Recap quiz<br>
10:00 AM - 11:00 AM: [Talk: Intro to transformers & embeddings]()<br>
10:45 AM - 11:00 AM: Break<br>
11:00 AM - 12:00 PM: [Talk: Intro to transformers & embeddings (continued)]()<br>
12:00 PM - 01:00 PM: Discussion: Find applications in small groups<br>
01:00 PM - 02:00 PM: Lunch<br>
02:00 PM - 03:00 PM: [Exercise: Clarifying personality psychology]()<br>
03:00 PM - 03:30 PM: Walkthrough<br>
03:30 PM - 03:45 PM: Break<br>
03:45 PM - 04:45 PM: [Intro to classification and regression]()<br>
04:15 PM - 05:15 PM: [Exercise: Classifying media bias]() (combination of 3a and 3b)<br>
05:15 PM - 06:00 PM: Walkthrough<br>
           07:00 PM: Dinner (self-paid)<br> 

#### Day 3
09:30 AM - 10:30 AM: Recap quiz<br>
10:30 AM - 11:00 AM: [Talk: Intro to info extraction]()<br>
11:00 AM - 11:15 AM: Break<br>
11:00 AM - 12:00 PM: [Exercise: Info extraction from articles]()<br>
12:00 PM - 01:00 PM: Discussion: Find applications in small groups<br>
01:00 PM - 02:00 PM: Lunch<br>
02:00 PM - 03:00 PM: [Talk: Research applications]()<br>
03:00 PM - 04:00 PM: Open questions<br>


### Resources
<a href="https://doi.org/10.3758/s13428-024-02455-8">Hussain, Binz, Mata, & Wulff (2024). A tutorial on open-source large language models for behavioral science. *Behavior Research Methods*, 1-24.
</a>
```
@article{hussain2024tutorial,
  title={A tutorial on open-source large language models for behavioral science},
  author={Hussain, Zak and Binz, Marcel and Mata, Rui and Wulff, Dirk U},
  journal={Behavior Research Methods},
  pages={1--24},
  year={2024},
  publisher={Springer}
}
```

[Hugging face documentation](https://huggingface.co/docs)<br>
[Hugging face book](https://transformersbook.com/)<br>
[But what is a GPT (3Blue1Brown)](https://www.youtube.com/watch?v=wjZofJX0v4M&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=5)<br>

### Before the course

#### Hugging Face and Meta Llama License
1. Make sure you have a Hugging Face account (https://huggingface.co/join).
2. Go to the [`meta-llama/Llama-3.2-3B-Instruct` model page](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct) and fill in the 'COMMUNITY LICENSE AGREEMENT' form at the top of the page to get access to the model (this may take a day or so). 

#### Google Colab and GitHub Repository
3. If you do not have a Google account, you will need to create one (this can be deleted after the workshop).

### During the course
1. Navigate to Google Drive (https://drive.google.com/).
2. In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", 
search for 'Colaboratory,' and install it. Then click New > More > Colaboratory.
3. Copy the following code snippet into the first cell of the notebook. Run it (```shift + enter``` or click &#9658; button) to mount your Google Drive to the Colab environment.
A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab (unfortunately, this only works if you give Google full permissions).
```
from google.colab import drive
drive.mount("/content/drive")
```
4. Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive:
```
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/LLM4BeSci_StGallen2025
```
5. Go back to your Google Drive and navigate to the folder "LLM4BeSci_StGallen2025" (this is your own copy, so you can edit it how you like, and the changes won't affect anyone else's copies). You should see the directories `day_1`, `day_2`, `day_3` containing the relevant notebooks (.ipynb files) and data (it may take a couple of minutes for the files to appear) for each day's exercises.

You have now successfully set up your Google Colab environment and cloned the GitHub repository! 

You are now ready to work through all the exercises in the course!  
