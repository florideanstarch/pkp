---
title: What is this all about? 
authors: Satya
---

I was part of a bootcamp at work that took me through the fundamentals of AI/ML over a few months. This page is my attempt to record what I learned while studying core ML and DL concepts. The goal was to understand these ideas well enoug, and to familiarise myself with the code. Eventually, I would be required to apply these methods to problems in biology. I followed the resources mentioned below and took detours into prerequisites whenever needed.

Now, I’ve given myself a year to work through the additional material on this page, that was not covered during the bootcamp.

Legend:
- 📕: Book
- 🎥: Playlist/Video
- ⚙️: Framework
- 💻: Code
- ⛺️: Bootcamp Recommendations
- ⚠️⚠️: WIP
- ✅: Done


## Math
- 📕 Bayesian Statistics for Beginners: A Step-by-Step Approach (Donovan & Mickey): When I found Chapter 4 of ISLP difficult, this book helped.
- 📕 [mml, Deisenroth](https://mml-book.github.io/book/mml-book.pdf)
    - 🎥 [Yacine streams mml](https://www.youtube.com/@deeplearningexplained/streams): Yacine sat with some sections of the book for hours, now paywalled 😕.
- 📕 [Mathematics of Machine Learning, Tivadar Danka](https://github.com/cosmic-cortex/mathematics-of-machine-learning-book)
- 🎥 [Jon Krohn](https://www.youtube.com/@JonKrohnLearns/playlists): Not required for the bootcamp, but I went through Jon Krohn's lectures. The probability lectures were not free but were available on O'Reilly and were very helpful. 
    - Add a GitHub repo with the notebooks ⚠️⚠️ 
    - Revise and add notes here ⚠️⚠️ 
- 📝 [Linear Algebra, Pablo Insente](https://pabloinsente.github.io/intro-linear-algebra)
- 🎥📕 [Linear Algebra Course, Strang](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- 🎥📕 [Intro to Probability, Tsitsiklis](https://ocw.mit.edu/courses/res-6-012-introduction-to-probability-spring-2018/)
- 📕 [Seeing Theory: Probability Intro from Brown](https://seeing-theory.brown.edu/), [Notes](https://seeing-theory.brown.edu/doc/seeing-theory.pdf)
- 📝 [Arnuld’s Blog on MML](https://medium.com/data-science/how-i-learned-linear-algebra-probability-and-statistics-for-data-science-b9d1c34dfa56)
- 🎥 [Math for GenAI, IIT-M](https://youtube.com/playlist?list=PLZ2ps__7DhBa5xCmncgH7kPqLqMBq7xlu)
- 🎥 [Understand KDE](https://www.youtube.com/watch?v=6sGOMbC5xdE)
- 🎥 [Deep Dive into KL Divergence and Cross-entropy](https://www.youtube.com/watch?v=KHVR587oW8I&t=10s)
- 📕 [The Hundred Page ML Book](https://gzai.in/wp-content/uploads/2025/07/the-hundred-page-machine-learning-book_compress.pdf): Math fundamentals for ML explained in 100 pages
- 📕 [The Hundred Page Language Model Book](https://gzai.in/wp-content/uploads/2025/07/the-hundred-page-machine-learning-book_compress.pdf): Math fundamentals for LLMs explained in 100 pages


## Dimensionality Reduction
- 🎥 [StatQuest PCA](https://www.youtube.com/watch?v=FgakZw6K1QQ) 
- 🎥 [StatQuest t-SNE](https://www.youtube.com/watch?v=NEaUSP4YerM) 
- 🎥 [PCA by Prof. Bose, IIT-G](https://www.youtube.com/watch?v=Up46jS_Tb1s) 
- 🎥 [t-SNE by Prof. Bose, IIT-G](https://www.youtube.com/watch?v=HRbh-t2Uog4)
- ⛺️🎥 [tSNE from the person who made it](https://www.youtube.com/watch?v=bCkXxaoeFZ8) 
- ⛺️🎥 [Smitha Krishnaswamy on Magic, Manifold Reduction](https://www.youtube.com/watch?v=deUVFAOY0kU) 
- ⛺️🎥[Diffusion Maps, Smita Krishnaswamy](https://www.youtube.com/watch?v=pevW0L-TEbg)
- ⛺️🎥 [Meaningful 2D Visualizations of Biological Data, Patcher](https://www.youtube.com/watch?v=zg6vBHYMoKo)
- ⛺️🎥 [KNN for dimensionality reduction, a primer from Broad](https://www.youtube.com/watch?v=FlFYa79D4dc&t=4s)
- UMAP (to be added) ⚠️⚠️



## ML
- ⛺️📕 [ISLP](https://www.statlearning.com/)
    - Go through the book again and take notes in the second iteration (start with sections on Trees) ⚠️⚠️
    - 💻 [Labs](https://islp.readthedocs.io/en/latest/labs.html). Go through these chapters: 3, 4, 5, 6, 8, 10, 12 ⚠️⚠️  
    - Complete the exercises too ⚠️⚠️
- 📕 The StatQuest Illustrated Guide to Machine Learning!!!
- ⛺️⚙️ [Scikit-Learn Docs](https://scikit-learn.org/stable/)
- ⛺️⚙️ [NumPy and Broadcasting](https://numpy.org/doc/stable/user/basics.html)
- ⛺️📕 Agan-AI-ML-Guide
- 📝 [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)


## DL 
- 📕 [UDL](https://udlbook.github.io/udlbook/) ⚠️⚠️
    - 💻 PyTorch notebooks hosted on the book website ⚠️⚠️
    - [PyTorch Notebooks Solved](https://github.com/rlepsch/SOLUTIONS_NOTEBOOKS_UDL)
    - [Lectures (Chapter 1-12) from QatarUni](https://www.youtube.com/playlist?list=PLRdABJkXXytCz19PsZ1PCQBKoZGV069k3): The instructor has worked at Microsoft, PhD in CS from Maryland.
- 📕💻 [d2l](https://d2l.ai/) (alternate book to UDL, highly recommended by a lot of people)
- ⛺️📕 [neuralnetworksanddeeplearning](http://neuralnetworksanddeeplearning.com/): This was the preferred book, as it was not heavy on notation. Topics like backpropagation were explained well, but I abandoned it for other resources.
- ⛺️📕🎥💻⚙️ [ZTM PyTorch](https://www.learnpytorch.io/): Nitesh's recommendation ⚠️⚠️
    - Complete the lectures ⚠️⚠️
    - Add to Github ⚠️⚠️
    - [TF DL Visual Playground](https://playground.tensorflow.org/) 
- 📕⚙️ Hands-On Machine Learning with Scikit-Learn and PyTorch, Geron
- 📕⚙️ Hands-On Machine Learning with PyTorch and Scikit-learn, Raschka
- ⛺️📕 Agan-AI-ML-Guide
- 📕🎥💻 [UvA (Amsterdam) DL Course](https://uvadlc-notebooks.readthedocs.io/en/latest/index.html)
- 📕💻 The StatQuest Illustrated Guide to Neural Networks and AI, with hands-on examples in PyTorch!!! ⚠️⚠️
- 🎥💻 [Raschka, DL (up to GPT)](https://www.youtube.com/watch?v=1nqCZqDYPp0&list=PLTKMiZHVd_2KJtIXOW0zFhFfBaJJilH51)
- 🎥💻 [Karpathy, NN:Zero-To-Hero)](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
- 🎥 [LLMs, IIT-M](https://youtube.com/playlist?list=PLZ2ps__7DhBbaMNZoyW2Hizl8DG6ikkjo) 
- 🎥 [DL, IIT-M](https://www.youtube.com/playlist?list=PLZ2ps__7DhBZVxMrSkTIcG6zZBDKUXCnM)
- ⛺️🎥 [3Blue1Brown, NN](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
- 📕🎥💻 [fast.ai](https://course.fast.ai/)
- 📕 [Little Book of DL, Flueret](https://fleuret.org/public/lbdl.pdf)
- DL in Biology
    - 🎥💻 [Build AlphaFold from Scratch](https://www.youtube.com/watch?v=NSvp7RFegEs&list=PLJ0WcPQS7xJVJr6ceIPFSkAGAgrkmw1c9)
    - 🎥 [DL in Life Sciences, Kellis](https://www.youtube.com/watch?v=0jWOZoTsYzI&list=PLypiXJdtIca5sxV7aE3-PS9fYX3vUdIOX)
    - 🎥 [ML in Comp. Biology, Kellis](https://www.youtube.com/watch?v=1zZSPeKGRzw&list=PLypiXJdtIca4gtioEPLIExlAKvu64z7rc)
- CNNs
    - ⛺️🎥 [Brandon Rohrer makes CNNs click](https://www.youtube.com/watch?v=FmpDIaiMIeA)
    - 🎥📝 [Visual explainer for CNNs](https://poloclub.github.io/cnn-explainer/)
- LSTMs
    - 📝 [Colah's Blog on LSTMs](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- Transformers:
    - 📝 [Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
    - 📝 [Transformers From Scratch](https://peterbloem.nl/blog/transformers)
    - 📕 [Transformers (Speech and Language Processing Book)](https://web.stanford.edu/~jurafsky/slp3/9.pdf)
    - 📝 [Transformers Laid Out](https://goyalpramod.github.io/blogs/Transformers_laid_out/)
    - 📝 [Transformers by Brandon Rohrer](https://brandonrohrer.com/transformers.html)
    - 🎥 [RASA's Transformers](https://www.youtube.com/watch?v=yGTUuEx3GkA)
    - 🎥💻 [Karpathy Explains Transformers](https://www.youtube.com/watch?v=XfpMkf4rD6E)
    - 🎥📝 [Transformer Visual Explainer](https://poloclub.github.io/transformer-explainer/)
    - ⛺️🎥 Agan-TFD-Transformer-Session-Siva
- GNNs
    - ⛺️📝 [Gentle Intro to GNNs by Distill](https://distill.pub/2021/gnn-intro/)
    - ⛺️📝 [GCNs Distill Blog](https://distill.pub/2021/understanding-gnns/)
    - ⛺️🎥 [GNN Theoretical Foundations](https://www.youtube.com/watch?v=uF53xsT7mjc) 
    - ⛺️🎥 [Broad Institute's Primer to GNNs](https://www.youtube.com/watch?v=r5TB1d_rUxg&t=1072s)
    - 🎥 [Vizuara GNNs](https://www.youtube.com/watch?v=93FiLSxKr_U&list=PLPTV0NXA_ZSg4Pimkso0nHxwYMB6IGX7l): Manish's recommendation
- DDPMs
    - ⛺️🎥 [What are diffusion models?](https://www.youtube.com/watch?v=fbLgFrlTnGU)
    - ⛺️📝💻 [Akash Kumar Nain, DDPMs](https://github.com/AakashKumarNain/diffusion_models)
    - ⛺️🎥 Agan-TFD-DDPMs-Session

## LLMs
- 🎥📕 [LLMs from Scratch, Raschka](https://www.youtube.com/watch?v=yAcWnfsZhzo&list=PLTKMiZHVd_2IIEsoJrWACkIxLRdfMlw11)
- 🎥📕 [DeepSeek from Scratch, Vizuara](https://www.youtube.com/watch?v=QWNxQIq0hMo&list=PLPTV0NXA_ZSiOpKKlHCyOq9lnp-dLvlms)

## Agents 
(To be added) ⚠️⚠️
- [BAML](https://boundaryml.com/)
- [Claude Docs](https://platform.claude.com/docs/en/home): Manish's Recommendations
- Google Blogs 
- ⚙️ [ADK by Google](https://google.github.io/adk-docs/)
- [Google GenAI with GCP Course](https://cloud.google.com/learn/training/machinelearning-ai) 


## MLOps
- ⛺️🎥💻 [ClearML](https://www.youtube.com/watch?v=U7n9qXIBxEg)
- ⛺️📝 [CMU MLOps Guide](https://mlip-cmu.github.io/book/index.html)
- 🎥 [MLOps Zoomcamp](https://www.youtube.com/playlist?list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR)
- 📕💻 [Goku Mohandas' MLOps Course](https://madewithml.com/) 
- 📝 [Serverless ML](https://www.serverless-ml.org/blog/what-is-serverless-machine-learning)
- Databricks (to be added) ⚠️⚠️
- MLflow (to be added) ⚠️⚠️


## Cloud and Infra
(To be added) ⚠️⚠️
- [Skillbuilder by AWS, Cloud for ML](http://skillbuilder.aws/category/role/machine-learning-engineer)


## Misc.
- 🎥 [Zachary Huang](https://www.youtube.com/@ZacharyLLM/videos): AI-generated "will-make-you-click" videos on major ML/DL concepts, roughly 30 mins each
- 🎥 [Vizuara](https://www.youtube.com/@vizuara/courses): Has multiple courses but Manish recommends their GNN video.
- 🎥 [Julia Turc](https://www.youtube.com/@juliaturc1/videos): She has videos on the latest AI developments.
- 📝 [Colah's Blog](https://colah.github.io/): Writings on fundamental DL methods (not updated anymore)
- 📝 [Distill Blogs](https://distill.pub/): Basic DL workings from Google devs (not updated anymore)
- 📝 [Rachel's Blog on AI and Biology](https://rachel.fast.ai)
- 📝 [Brandon Rohrer](http://brandonrohrer.com/blog.html): Brilliant teacher, simplifies things (esp. CNNs)
- 📝 [Brandon Rohrer's Paid Platform, e2eML](https://end-to-end-machine-learning.teachable.com/) 
- 📝 [GraphRAG Explained](https://diamantai.substack.com/p/graph-rag-explained)
- 📝 [Lossfunk](https://lossfunk.com/), [Founder's Blog](https://invertedpassion.com/about/)
- 📝 [Blog on understanding GPUs](https://modal.com/gpu-glossary/host-software/cupti)
- 📝 [Anindya's X](https://x.com/anindyadeeps), [Anindya's Litefold](https://www.litefold.in/)
- 🎥 [FCC AI ML Guide 2025](https://www.youtube.com/watch?v=nYXVvK-Wmn0)
- 📝 [Antaripa Saha's DS Guide](https://antaripasaha.notion.site/Data-Science-All-in-one-f7b861fc69dd49439231b8c14a0e330b)
- 📝 [Antaripa Saha on Physics LLMs](https://antaripasaha.notion.site/Physics-of-Language-Models-understanding-hidden-reasoning-process-1045314a563980c68566e4ecc1e32ef6)
- 📝 [AI ML Biology Learning Path](https://www.iamtk.co/ai-ml-for-biology-and-healthcare-a-learning-path)
- 📝 [DL for Protein Function from Sequences](https://www.iamtk.co/deep-learning-for-biology-predicting-protein-functions-from-sequences)
- 💻 [AI/ML iQs](https://github.com/TidorP/MLJobSearch2025)
- 💻 [Leetcode-like site for ML/DL](https://www.deep-ml.com/)
- 💻 [Galaxy Training: Stats and ML](https://training.galaxyproject.org/training-material/topics/statistics/)


---

To Do:
- Should add Andrew Ng's courses
- Clean up notes on the drive