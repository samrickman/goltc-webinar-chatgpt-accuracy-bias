# GOLTC Data Science Interest Group: Webinar 23rd May 2023

This is the repo for the meeting of the [Global Observatory of Long-Term Care Data Science interest group](https://goltc.org/interest-group/data-science/). It contains links to the papers being presented and their respective GitHub repos. It also the Quarto and html files for the introductory presentation.

## Analysing accuracy, balancing bias: Can ChatGPT be used to ease the care documentation burden?

Care managers dedicate 6 hours per week transcribing handwritten notes from meetings into electronic databases. LLMs are now being used to automatically generate audio recordings of case management meetings into case notes, freeing up workers to spend more time assessing needs and arranging care. We saw an example of this in Magic Notes, a product from [Beam](https://beam.org/), that they presented at our webinar on 23rd May 2023 ([video](https://goltc.org/videos/beyond-words-can-chatgpt-ease-the-care-documentation-burden-12-march-2024-webinar-recording/)).

But how reliable are these tools? There can be racial disparities in automatic speech recognition. They can record false information, including harmful and violent hallucinations. And how do we quantify the accuracy of free text summaries generated from these transcriptions?

Webinar details:

-	Date: Thursday 23 May 2024
-	Time: 15:30 – 16:45 BST | 10:30 – 11:45 EDT (check your local time here)
-	Link: Register to join us on Zoom.

The webinar will cover:

1. Disparities in automated speech recognition ([Allison Koenecke](https://koenecke.infosci.cornell.edu/#research), Cornell Department of Information Science)
2. Adapted large language models can outperform medical experts in clinical text summarization ([Dave Van Veen](https://davevanveen.com/), Stanford Center for Artificial Intelligence)

## Links to papers

1. Koenecke, A., Nam, A., Lake, E., Nudell, J., Quartey, M., Mengesha, Z., Toups, C., Rickford, J.R., Jurafsky, D. and Goel, S., 2020. [Racial disparities in automated speech recognition. Proceedings of the National Academy of Sciences](https://www.pnas.org/doi/full/10.1073/pnas.1915768117), 117(14), pp.7684-7689.
2. Koenecke, A., Choi, A.S.G., Mei, K., Schellmann, H. and Sloane, M., 2024. [Careless Whisper: Speech-to-Text Hallucination Harms](https://arxiv.org/abs/2402.08021). arXiv preprint arXiv:2402.08021.
3. Van Veen, D., Van Uden, C., Blankemeier, L., Delbrouck, J.B., Aali, A., Bluethgen, C., Pareek, A., Polacin, M., Reis, E.P., Seehofnerová, A. and Rohatgi, N., 2024. [Adapted large language models can outperform medical experts in clinical text summarization](https://www.nature.com/articles/s41591-024-02855-5). Nature Medicine, pp.1-9.

## Links to GitHub repos

1.	[Racial Disparities in Automated Speech Recognition](https://github.com/stanford-policylab/asr-disparities)
2.	[Careless Whisper: Speech to Text Hallucinations](https://github.com/koenecke/hallucination_harms)
3.	[Clinical Text Summarization by Adapting LLMs](https://github.com/StanfordMIMI/clin-summ)


## Bibtex citations of papers


```
@article{koenecke2020racial,
  title={Racial disparities in automated speech recognition},
  author={Koenecke, Allison and Nam, Andrew and Lake, Emily and Nudell, Joe and Quartey, Minnie and Mengesha, Zion and Toups, Connor and Rickford, John R and Jurafsky, Dan and Goel, Sharad},
  journal={Proceedings of the National Academy of Sciences},
  volume={117},
  number={14},
  pages={7684--7689},
  year={2020},
  publisher={National Acad Sciences}
}

@article{koenecke2024careless,
  title={Careless Whisper: Speech-to-Text Hallucination Harms},
  author={Koenecke, Allison and Choi, Anna Seo Gyeong and Mei, Katelyn and Schellmann, Hilke and Sloane, Mona},
  journal={arXiv preprint arXiv:2402.08021},
  year={2024}
}

@article{van2024adapted,
  title={Adapted large language models can outperform medical experts in clinical text summarization},
  author={Van Veen, Dave and Van Uden, Cara and Blankemeier, Louis and Delbrouck, Jean-Benoit and Aali, Asad and Bluethgen, Christian and Pareek, Anuj and Polacin, Malgorzata and Reis, Eduardo Pontes and Seehofnerov{\'a}, Anna and others},
  journal={Nature Medicine},
  pages={1--9},
  year={2024},
  publisher={Nature Publishing Group US New York}
}
```