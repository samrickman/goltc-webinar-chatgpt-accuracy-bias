# Analysing accuracy, balancing bias: Can ChatGPT be used to ease the care documentation burden?

## Leveraging AI for Care Management: A Look at Magic Notes

In the world of care management, efficiency and accuracy are paramount. Currently, care managers spend an average of six hours per week transcribing handwritten notes from meetings into electronic databases. This task, while crucial, is time-consuming and takes away from the essential responsibilities of assessing needs and arranging care for clients. However, advancements in artificial intelligence, particularly large language models (LLMs), are beginning to transform this process.

One notable innovation in this space is Magic Notes, a product from [Beam](https://beam.org/). As showcased in our webinar on 12th March 2024, Magic Notes utilizes AI to automatically convert audio recordings of case management meetings into comprehensive case notes. This automation not only saves time but also aims to enhance the quality of care by allowing care managers to focus more on their primary duties rather than administrative tasks. For those who missed the webinar, you can catch up by watching the recording [here](https://goltc.org/videos/beyond-words-can-chatgpt-ease-the-care-documentation-burden-12-march-2024-webinar-recording/).

## Addressing the Challenges of AI in Care Documentation

While the benefits of AI in care management are compelling, it's important to acknowledge the potential challenges and limitations. One significant concern is the reliability of these AI tools. For instance, automatic speech recognition systems can exhibit racial disparities, potentially leading to inaccuracies in transcriptions. Additionally, AI-generated text can sometimes include false information, including harmful and violent hallucinations.

Another critical issue is quantifying the accuracy of the free text summaries generated from these transcriptions. Ensuring that these AI-generated notes accurately reflect the original meetings is crucial for maintaining the integrity of care documentation. Ongoing research and development are essential to address these challenges and improve the reliability and accuracy of AI tools in care management.

But how reliable are these tools? There can be racial disparities in automatic speech recognition. They can record false information, including harmful and violent hallucinations. And how do we quantify the accuracy of free text summaries generated from these transcriptions?

The [GOLTC Data Science](https://goltc.org/interest-group/data-science/) webinar on May 23rd, 2024, included presentations on these topics. Below are links to relevant papers and their GitHub repositories, offering a deep dive into the latest advancements and research in this field.

## Webinar details:

The webinar covered:

1. Disparities in automated speech recognition ([Allison Koenecke](https://koenecke.infosci.cornell.edu/#research), Cornell Department of Information Science)
2. Adapted large language models can outperform medical experts in clinical text summarization ([Dave Van Veen](https://davevanveen.com/), Stanford Center for Artificial Intelligence)

## Links to papers

1. Koenecke, A., Nam, A., Lake, E., Nudell, J., Quartey, M., Mengesha, Z., Toups, C., Rickford, J.R., Jurafsky, D. and Goel, S., 2020. [Racial disparities in automated speech recognition. Proceedings of the National Academy of Sciences](https://www.pnas.org/doi/full/10.1073/pnas.1915768117), 117(14), pp.7684-7689.
2. Koenecke, A., Choi, A.S.G., Mei, K., Schellmann, H. and Sloane, M., 2024. [Careless Whisper: Speech-to-Text Hallucination Harms](https://arxiv.org/abs/2402.08021). arXiv preprint arXiv:2402.08021.
3. Van Veen, D., Van Uden, C., Blankemeier, L., Delbrouck, J.B., Aali, A., Bluethgen, C., Pareek, A., Polacin, M., Reis, E.P., Seehofnerová, A. and Rohatgi, N., 2024. [Adapted large language models can outperform medical experts in clinical text summarization](https://www.nature.com/articles/s41591-024-02855-5). Nature Medicine, pp.1-9.

## Links to GitHub repos

1. [Racial Disparities in Automated Speech Recognition](https://github.com/stanford-policylab/asr-disparities)
2. [Careless Whisper: Speech to Text Hallucinations](https://github.com/koenecke/hallucination_harms)
3. [Clinical Text Summarization by Adapting LLMs](https://github.com/StanfordMIMI/clin-summ)

# Links to newspaper articles

These are the articles mentioned in the introductory presentation:

1. Lohr, S., 2023. [A.I. May Someday Work Medical Miracles. For Now, It Helps Do Paperwork](https://www.nytimes.com/2023/06/26/technology/ai-health-care-documentation.html) New York Times, 26 June 2023.
2. Wilcock, D., 2024. [Civil servants will be replaced by AI chatbots](https://www.dailymail.co.uk/news/article-13141169/Civil-servants-replaced-AI-chatbots-Oliver-Dowden.html), Daily Mail, 29 February 2024.
3. Tapper, G., 2024 [Warning over use in UK of unregulated AI chatbots to create social care plans](https://www.theguardian.com/technology/2024/mar/10/warning-over-use-in-uk-of-unregulated-ai-chatbots-to-create-social-care-plans), The Guardian, 10 March 2024.

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
