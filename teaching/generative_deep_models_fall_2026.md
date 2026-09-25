<a name="top"></a>

# DEEP GENERATIVE MODELS FALL 2026

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Slides**](#slides)|  [**Readings**](#readings)| 

#### Location
Technological Institute LG68

#### Class Day/Time
Tue Thu 3:30pm - 5:00pm

#### Instructor
[Bryan Pardo](http://bryanpardo.com)
Office hours by appointment


## Course Description

WARNING: This course is about reading papers. A lot of papers. If you don't want to read and discuss papers, this is not the course for you.

DESCRIPTION: One of the most exciting areas of research in deep learning is that of generative models. This course is dedicated to understanding the inner workings of the technologies that underlie these advances. Students will primarily learn about how Transformers, Variational Autoencoders, Reinforcement Learning and Diffusion Models are used to create text documents, write code, create music, images, speech, and more. We'll also look at legal and ethical implications of these models.  This is an advanced course that presumes a good working understanding of traditional supervised neural network technology and techniques (e.g. convolutional networks, LSTMs, loss functions, regularization, gradient descent). 

PREREQUISITES: Course admission is by permission of instructor. The best Northwestern course to prepare for this class is CS 449 Deep Learning, although being a doctoral student in CS will likely get you in, even if you haven't taken CS 449. 
  
<a name="calendar"></a>
## Course Calendar
[**Back to top**](#top)


| Week|   Day and Date| Topic                                                                                                                                                                                           |Presenter        |Commentators            |
|----:|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|------------------------|
|  1  | Thu Sep 24    | NO CLASS: Read [Chapter 4 of Machine Learning](https://interactiveaudiolab.github.io/course-deep-learning/readings/chapter4-ml.pdf) as neural networks refresher                                | Pardo           | - |
|  2  | Tue Sep 29    | The evolution of language modeling: Attention, Embeddings                                                                                                                                       | Pardo           | - |
|  2  | Thu Oct  1    | Transformers: Positional Encoding, Autoregression: [Attention is all you need](https://arxiv.org/abs/1706.03762)                                                                                | Pardo           | - |
|  3  | Tue Oct  6    | Two big model families: Google's [BERT](https://arxiv.org/pdf/1810.04805.pdf) and OpenAI's [GPT](http://jalammar.github.io/illustrated-gpt2/)                                                   | Pardo           | - |
|  3  | Thu Oct  8    | Sampling strategies: [The Curious Case of Neural Text Degeneration](https://arxiv.org/abs/1904.09751) &  [A Watermark for Large Language Models](https://arxiv.org/pdf/2301.10226.pdf)          | Pardo           | - |
|  4  | Tue Oct 13    | Deep Reinforcement Learning: [PPO](https://arxiv.org/pdf/1707.06347.pdf)                                                                                                                        | Pardo           | - |
|  4  | Thu Oct 15    | Reinforcement Learning from Human Feedback: [RLHF](https://arxiv.org/pdf/2203.02155)                                                                                                            | Pardo           | - |
|  5  | Tue Oct 20    | [Your Brain on ChatGPT](https://collimateur.uqam.ca/wp-content/uploads/sites/11/2025/12/2506.08872v1_comp.pdf) & [...The Rise of Cognitive Surrender](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6097646)| Pardo           | - |
|  5  | Thu Oct 22    | [Moral Alignment for LLM Agents](https://proceedings.iclr.cc/paper_files/paper/2025/hash/f2b1bad4756ceee8f408e16b8e6e4383-Abstract-Conference.html) &  [Report on the OpenAI / Hugging Face hacking incident](https://metr.org/hugging-face-incident-report-aug-2026.pdf)| Pardo           | - |
|  6  | Tue Oct 27    | Autoencoders & Variational Autoencoders: [Tutorial on VAEs](https://arxiv.org/abs/1606.05908)                                                                                                   | Pardo           | - |
|  6  | Thu Oct 29    | NO CLASS: Work on your project proposal & hand in paper reviews                                                                                                                                 | N/A             | - |
|  7  | Tue Nov  3    | Quantized Variational Autoencoders: [VQ-VAE](https://arxiv.org/abs/1711.00937) &  [Dall-E](https://arxiv.org/pdf/2102.12092.pdf)                                                                | Pardo           | - |
|  7  | Thu Nov  5    | Neural Codecs: [SoundStream](https://arxiv.org/pdf/2107.03312.pdf) & [D-composer](https://interactiveaudiolab.github.io/assets/papers/oreilly2026ismir.pdf)                                     | Pardo           | - |
|  8  | Tue Nov 10    | Diffusion: [DDPM](https://arxiv.org/abs/2006.11239)                                                                                                                                             | Pardo           | - |
|  8  | Thu Nov 12    | Diffusion: [DDIM](https://arxiv.org/abs/2010.02502)                                                                                                                                             | Pardo           | - |
|  9  | Tue Nov 17    | Multimodal Embedding Models: [CLIP](https://arxiv.org/abs/2103.00020) & [CLAP](https://arxiv.org/pdf/2206.04769)                                                                                | Pardo           | - |
|  9  | Thu Nov 19    | [Guidance](https://benanne.github.io/2022/05/26/guidance.html)                                                                                                                                  | Pardo           | - |
| 10  | Tue Nov 24    | [Classifier-free Guidance](https://benanne.github.io/2022/05/26/guidance.html)                                                                                                                  | Pardo           | - |
| 10  | Thu Nov 26    | NO CLASS: HAPPY THANKSGIVING. Also, last set of paper reviews are due this week.                                                                                                                | N/A             | - |
| 11  | Tue Dec  1    | [Latent Diffusion](https://arxiv.org/pdf/2112.10752) & [Diffusion with Transformers](https://arxiv.org/abs/2212.09748)                                                                          | Pardo           | - |
| 11  | Thu Dec  3    | [Investigating Data Replication in Diffusion Models](https://arxiv.org/pdf/2212.03860.pdf) & [Allocating Ownership Rights in Computer Generated Works](https://www.law.berkeley.edu/wp-content/uploads/2024/01/Pam-Samuelson-Allocating-Ownership-Rights-in-Computer-Generated-Works.pdf)  | Pardo           | - |
| 12  | Fri Dec 12    | FINAL EXAM: One on one reading discussion                                                                                                                                                       | Students        | - |



## Course assignments

### Class Participation: 15 points
You will be a "commentator" for 3 papers throughout the term. To get the points you need to be there the day we discuss your paper, you need to understand the paper and be able to discuss it and answer questions about it interactively.

### Reading: 45 points 
You will submit 15 one-page reviews of readings from the course readings. Each written review is worth 3 points.

### Final Exam: 1-on-1 Reading discussion: 20 points
You and I will discuss 2 of the papers you submitted a written review for, one on one. If I feel like you really read the papers and had thoughts, you get full points.

### Final Project: 20 points
Possible projects:

1. Duplicate the result in a paper related to generative modeling

1. Do a domain-specific lit review for a paper on your own sub-area related to generative modeling.

1. Pick one or two of the topics/questions from the long reading list at the end of this web page. Do a deep dive by reading the papers in that topic and writing up your paper reactions. Give me at least 7 one-page-per-paper reactions, plus an overview of your synthesized knowledge from that.

1. Make a tutorial that explains a paper

1. Make an educational jupyter notebook to show how to do a genAI technique

1. Something else you convince me is worth doing


<a name="slides"></a>
## Lecture Slides and Notebooks

1. [Language Models](/generative_deep_models/0_RNNs_as_Langauge_Models.pdf)

1. [Attention Networks](/generative_deep_models/1_attention_networks.pdf)

1. [Embeddings](/generative_deep_models/2_embeddings.pdf)

1. [Positional Encoding, Attention and Embeddings Notebook](/generative_deep_models/Embeddings_Positional_Encoding_Attention.ipynb)

1. [Transformers](/generative_deep_models/3_transformers.pdf)

1. [Deep Reinforcement Learning: Q Learning](/generative_deep_models/4_deep_RL_1_Q_learning.pdf)

1. [Deep Reinforcement Learning: Policy Gradients](/generative_deep_models/5_deep_RL_2_policy_gradients.pdf)

1. [Deep Reinforcement Learning: Human Feedback](/generative_deep_models/6_deep_RL_3_human_feedback.pdf)

1. [Variational Inference](/generative_deep_models/7_variational_inference.pdf)

1. [Variational Autoencoders](/generative_deep_models/8_variational_autoencoders.pdf)

1. [Generative Adversarial Networks](/generative_deep_models/9_GANs.pdf)

1. [Diffusion/Score Models](/generative_deep_models/10_GM_Score-Diffusion_Models.pdf)

1. [Measures of Image Quality](/generative_deep_models/11_GM_measuring_image_quality.pdf)

[**Back to top**](#top)

### Lectures

<a name="readings"></a>
## Course Reading
[**Back to top**](#top)



### INFLUENTIAL AUTOREGRESSIVE MODELS 
1. [Pixel Recurrent Networks](http://proceedings.mlr.press/v48/oord16.html): A highly infulential autoregressive model for image generation

1. [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499): A highly infulential autoregressive model for audio generation


### TRANSFORMERS & LANGUAGE MODELS

#### Architectural elements that lead up to Transformers

1. [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/) This is a good starting point blog on attention models, which is what Transformers are built on. 

1. [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf): This is the paper that the link above was trying to explain.

1. [Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078.pdf): This introduces encoder-decoder networks for translation. Attention models were first built on this framework. 

1. [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf): This paper introduces additive attention to an encoder-decoder. 

1. [Effective Approaches to Attention-based Neural Machine Translation](https://arxiv.org/pdf/1508.04025.pdf): This paper introduces multiplicative attention, which is what Transformers use. 

1. [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385): This introduces the idea of "residual layers", which are layers that are skippable. This idea is used in Transformers.

#### Understanding Embeddings 

1. [The Illustrated Word2Vec](https://jalammar.github.io/illustrated-word2vec/): Transformers for text take word embeddings as input. So what's a word embedding? This is a walk through word embeddings, at a high level, with no math.

1. [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf): This is the Word2Vec paper.

1. [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/): The paper that describes the Glove embedding, which is an improvement on Word2Vec, and has downloadable embeddings to try. There is math here.

1. [Using the Output Embedding to Improve Language Models](https://arxiv.org/abs/1608.05859): In transformers, they actually learn their embeddings at the same time as everything else and tie the input embedding to the output embedding. This paper explains why.

#### The Transformer Architecture

1. [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/): A good initial walkthrough that helps a lot with understanding transformers  ** I'd start with this one to learn about transformers.**

1. [The Annotated Transformer](http://nlp.seas.harvard.edu/annotated-transformer/): An annotated walk-through of the "Attention is All You Need" paper, complete with detailed python implementation of a transformer. ** If you actually want to understand transformer implementation, you should read this in depth...and play with the code.**

1. [Attention is All You Need](https://arxiv.org/abs/1706.03762): The paper that introduced transformers, which are a popular and more complicated kind of attention network. 

#### About positional encoding

1. [Self-Attention with Relative Position Representations](https://arxiv.org/abs/1803.02155): The most frequently used alternative to absolute positional encoding

1. [Rotary Positional Encoding](https://paperswithcode.com/method/rope#:~:text=Rotary%20Position%20Embedding%2C%20or%20RoPE,dependency%20in%20self%2Dattention%20formulation.): claims to combine the benefits of both absolute and relative positional encoding 

1. [What Do Position Embeddings Learn? An Empirical Study of Pre-Trained Language Model Positional Encoding](https://arxiv.org/pdf/2010.04903): Why not learn your positional encoding? What happens if you do that?

#### How and why does model performance scale with size?

1. [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361) : This is the 2020 paper that forms basis of the argument for why AI is taking all the energy and all the chips. Note who the authors are...

1. [Supperposition Yields Robust Neural Scaling](https://proceedings.neurips.cc/paper_files/paper/2025/hash/e97ac22927560eb2de6b658498cbc575-Abstract-Conference.html): This 2025 paper basically argues that it is the size of the model's embedding representation that causes us to build bigger and bigger models. Maybe have a look at the parameter-efficient tuning papers for another lens on this.

#### Parameter Efficient Fine Tuning (PEFT) of langauge models

1. [LORA: Low-rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685.pdf): Microsoft's approach to fast, efficient retraining for downstream tasks.

1. [Parameter-Efficient Transfer Learning for NLP](https://proceedings.mlr.press/v97/houlsby19a.html): A well-cited clasic for fine-tuning language models.

#### BERT and GPT, two foundational architectures 

1. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf): A widely-used language model based on Transformer encoder blocks.

1. [The Illustrated GPT-2](http://jalammar.github.io/illustrated-gpt2/): A good overview of GPT-2 and its relation to Transformer decoder blocks.

1. [GPT-3:Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): This explores the range of things that you can do with a GPT model.

#### Why sampling strategies matter

1. [The Curious Case of Neural Text Degeneration](https://arxiv.org/abs/1904.09751): When you sample from the output of a language model, it matters a LOT just how you sample. Read this to understand why. 

1. [A Watermark for Large Language Models](https://arxiv.org/pdf/2301.10226.pdf): Can you use a sampling strategy to watermark generated text?


#### Symbolic Music Making with Transformers

1. [Music Transformer](https://arxiv.org/pdf/1809.04281): Applying Transformers to music composition. More [here](https://magenta.tensorflow.org/music-transformer)

1. [Anticipatory Music Transformer: A Controllable Infilling Model for Music](https://crfm.stanford.edu/2023/06/16/anticipatory-music-transformer.html)


#### Making Images with Transformers

1. [Image GPT](https://openai.com/blog/image-gpt/): Using a Transformer to make images. This isn't DALL-E, even though it's by OpenAI.

1. [Zero-Shot Text-to-Image Generation](https://arxiv.org/pdf/2102.12092.pdf): This is the original version of DALL-E, which generates images conditioned on text captions. It is based on Transformer architecture.

1. [MaskGIT: Masked Generative Image Transformer](https://openaccess.thecvf.com/content/CVPR2022/html/Chang_MaskGIT_Masked_Generative_Image_Transformer_CVPR_2022_paper.html)  This lets you generate in PARALLEL, not auto-regressively

1. [MaskBit: Embedding-free Image Generation via Bit Tokens](https://weber-mark.github.io/projects/maskbit.html): A 2024-SOTA image generator based on MaskGiT 


#### Making Transformers Efficient by Making Attention Efficient

1. [Reformer: The Efficient Transformer](https://arxiv.org/abs/2001.04451): This uses locality sensitive hashing to make attention much more efficient, moving it from taking O(n^2) and making it O(nlogn). 

1. [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135): This is a VERY popular paper and lots of people use this approach

1. [Longformer: The Long-Document Transformer](https://arxiv.org/pdf/2004.05150):  Longformer’s attention mechanism is a drop-in replacement for the standard self-attention and combines a local windowed attention with a task motivated global attention. This is a widely cited paper. 


#### Reasoning and Memory in Transformers

1. [Memory Transformer](https://arxiv.org/abs/2006.11527)

1. [Vision Transformers Need Registers](https://arxiv.org/abs/2309.16588)

1. [Think before you speak: Training Language Models With Pause Tokens](https://arxiv.org/abs/2310.02226)

1. [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://proceedings.neurips.cc/paper_files/paper/2022/file/9d5609613524ecf4f15af0f7b31abca4-Paper-Conference.pdf)

1. [Verbalizable Representations Form a Global Workspace in Language Models](https://transformer-circuits.pub/2026/workspace/index.html): A 2026 paper from Anthropic that claims they can study jacobians to find places in transformers that are working as a global workspace for thought, framed in language tokens. They don't go all the way to say it is "consciousness", but you can tell they kind of want to go there.


#### How to tokenize audio to allow language modeling of sound

1. [WAV2VEC: UNSUPERVISED PRE-TRAINING FOR SPEECH RECOGNITION](https://arxiv.org/pdf/1904.05862.pdf): This describes a way to build a dictionary of audio tokens that is used in MusicLM

1. [Wav2vec 2.0: Learning the structure of speech from raw audio](https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/): The 2nd iteration of wav2vec

1. [SoundStream: An End-to-End Neural Audio Codec](https://arxiv.org/pdf/2107.03312.pdf): Perhaps the top (as of 2023) audio codec. It is used in multiple audio langague models to tokenize the audio for the language model.

1. [High-Fidelity Audio Compression with Improved RVQGAN](https://arxiv.org/pdf/2306.06546): This is SOTA for audio encoders, as of July 2024


#### Using language models on audio tokens

1. [W2v-BERT: Combining Contrastive Learning and Masked Language Modeling for Self-Supervised Speech Pre-Training](https://arxiv.org/abs/2108.06209): Masked inference language model method to learn audio tokens. This is what is actually used in MusicLM

1. [AudioLM: A Language Modeling Approach to Audio Generation](https://google-research.github.io/seanet/audiolm/examples/): A language model for generating speech continuation

1. [MusicLM: Generating Music From Text](https://google-research.github.io/seanet/musiclm/examples/): A model generating music audio from text descriptions such as "a calming violin melody backed by a distorted guitar riff".

1. [Vampnet: Music Generation via Masked Acoustic Token Modeling](https://arxiv.org/abs/2307.04686): Generating non-autoregressively, similar to MaskGit


### Reinforcement learning for Model Alignment 

1. [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html): This is an entire book, but it is the one I learned RL from. 

1. [Policy Gradient Methods: Tutorial and New Frontiers](https://youtu.be/y4ci8whvS1E?t=2230): This is a video lecture that explains reinforcement learning policy grading methods. This is underlying tech used for training ChatGPT. Yes, this video is worth a "reading" credit. Yes, I started it 37 minutes into the lecture on purpose. You don't have to watch the first half of the lecture.

1. [Andrew K.s blog on Deep Reinforcement Learning](http://karpathy.github.io/2016/05/31/rl/): When combined with the video tutorial above, you'll more-or-less understand policy gradient methods for deep reinforcement learning

1. [Rank Analysis of Incomplete Block Designs: I. The Method of Paired Comparisons](https://www.jstor.org/stable/2334029): The 1952 paper that introduced the Bradley-Terry model, upon which most RLHF and its descendents depend.

1. [Proximal Policy Optimization Algorithms](https://arxiv.org/pdf/1707.06347.pdf): The paper that (mostly) explains PPO, the RL approach used in InstructGPT (the precursor to ChatGPT)

1. [This blog on RL from human feedback](https://openai.com/research/learning-from-human-preferences): read the paper linked at the start of the blog. It teaches how to learn a reward function from human feedback, so you can do RL.

1. [This blog on aligning language models to follow instructions](https://openai.com/research/instruction-following) together explain how ChatGPT is fine-tuned to do prompt answering by combining proximal policy optimization and RL from human feedback (the two previous papers on this list).

1. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290): This is the go-to option for people not doing RLHF. It skips having to train a separate reward model.

1. [KTO: Model Alignment as Prospect Theoretic Optimization](https://arxiv.org/pdf/2402.01306): Directly maximizes the utility of generations instead of maximizing the log-likelihood of preferences. Maybe better than DPO?

1. [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/pdf/2402.03300): This 224 paper introduce Group Relative Policy Optimization (GRPO), a variant of Proximal Policy Optimization (PPO), that the DeepSeek folks claim enhances mathematical reasoning abilities while optimizing the memory usage of PPO.

1. [Neural Thickets: Diverse Task Experts Are Dense Around Pretrained Weights](https://arxiv.org/html/2603.12228v1): New for 2026! No need for fine-tuning. Just randomly jiggle your weights...


### Multimodal Langauge Modeling

1. [GPT-4 with vision (GPT-4V)](https://openai.com/research/gpt-4v-system-card): enables users to instruct GPT-4 to analyze image inputs provided by the user, and is the latest capability we are making broadly available

1. [LLaVA: Large Language and Vision Assistant](https://llava-vl.github.io):a large multimodal model that combines a vision encoder and Vicuna for general-purpose visual and language understanding

1. [LLark: A Multimodal Foundation Model for Music](https://arxiv.org/abs/2310.07160): Mix Jukebox and Llama 2 and you get this.



### GENERATIVE ADVERSARIAL NETWORKS (GANS)

#### Creating adversarial examples
1. [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) : This paper got the ball rolling by pointing out how to make images that look good but are consistently misclassified by trained deepnets.

####  Creating GANs

1. [Generative Adversarial Nets](https://arxiv.org/pdf/1406.2661v1.pdf): The paper that introduced GANs

1. [2016 Tutorial on Generative Adversarial Networks](https://arxiv.org/pdf/1701.00160.pdf) by one of the creators of the GAN. This one's long, but good.

1. [DCGAN: Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434): This is an end-to-end model. Many papers build on this.

#### Advanced GANS

1. [PROGRESSIVE GROWING OF GANS FOR IMPROVED QUALITY, STABILITY, AND VARIATION](https://arxiv.org/pdf/1710.10196.pdf) This is used in StyleGAN and was state-of-the-art in 2018.

1. [StyleGAN: A Style-Based Generator Architecture for Generative Adversarial Networks](https://github.com/NVlabs/stylegan): As of 2019, this was the current state-of-the-art for GAN-based image generation.

1. [StyleGAN2-ADA: Training Generative Adversarial Networks with Limited Data](https://github.com/NVlabs/stylegan2-ada-pytorch): : As of 2020, this was the current state-of-the-art for GAN-based image generation.

1. [Cross-Modal Contrastive Learning for Text-to-Image Generation](https://arxiv.org/abs/2101.04702) As of 2021, this was the best GAN for text-conditioned image generation. Note it's use of contrastive loss. You'll see that again in CLIP.

1. [Adversarial Audio Synthesis](https://arxiv.org/abs/1802.04208): introduces WaveGAN, a paper about applying GANs to unsupervised synthesis of raw-waveform audio.

1. [MelGAN: Generative Adversarial Networks for Conditional Waveform Synthesis](https://github.com/descriptinc/melgan-neurips): Doing speech synthesis with GANs.

1. [HiFi-GAN: Generative Adversarial Networks for Efficient and High Fidelity Speech Synthesis](https://proceedings.neurips.cc/paper/2020/hash/c5d736809766d46260d816d8dbc9eb44-Abstract.html): Even better speech synthesis with GANs.

#### The GAN Revival
1. [The relativistic discriminator: a key element missing from standard GAN](https://arxiv.org/abs/1807.00734): This is the 2018 paper that introduces a way to stop mode collapse in GANs by changing the loss function to pair real and fake examples.

1. [The GAN is dead; long live the GAN! A Modern GAN Baseline](https://arxiv.org/abs/2501.05441): A 2025 paper that brings back GANs by addressing mode collapse and making them easier to train. This is the R3GAN paper.

1. [Scalable GANs with Transformers](https://arxiv.org/abs/2509.24935): The regularization used in the previous 2 GAN revival papers involves some hairy gradient calculation. This one substitutes an easy-to-calculate method to limit the curvature of the loss function by borrowing a trick from adversarial robustness...

### Variational Auto Encoders (VAEs)

#### Background needed for Variational Autoencoders

1. [The Deep Learning Book's Chapters on Probability and Linear Algebra](https://www.deeplearningbook.org). Read these before the Easy Intro to KL Divergence

1. [An Easy Introduction to Kullback-Leibler (KL) Divergence ](https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained). Read this before reading about ELBO 

1. [Jenson's Inequality (an example with code)](https://machinelearningmastery.com/a-gentle-introduction-to-jensens-inequality/). Read this before reading about ELBO

1. [A walkthrough of Evidence Lower Bound (ELBO)](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/lectures/variational-inference-i.pdf): Lecture notes from David Blei, one of the inventors of ELBO. ELBO is what you optimize when you do variational inference in a VAE.

1. [Categorical Reparameterization with Gumbel-Softmax](https://arxiv.org/abs/1611.01144): This is a way of allowing categorical latent variables in your model so you can run a differentiable gradient descent algorithm through them. This is used in Vector-Quantized VAEs.

1. [Probabilistic Graphical Models](https://ermongroup.github.io/cs228-notes/): Lecture notes from the class taught at Stanford.


#### Autoencoders

1. [A starter blog on AutoEncoders and VAEs](https://towardsdatascience.com/generating-images-with-autoencoders-77fd3a8dd368): Probably a good place to start.

1. [The Deep Learning Book's Chapter on Autoencoders](https://www.deeplearningbook.org/contents/autoencoders.html)

1. [From neural PCA to deep unsupervised learning ](https://www.sciencedirect.com/science/article/pii/B9780128028063000087): This paper introduces Ladder networks, which will come back when we get to VAEs

#### BASIC Variational Auto Encoders (VAEs)

1. [Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908): This is a walk-through of the math of VAEs. I think you should maybe start with this one.

1. [Variational Inference, a Review for Statisticians](https://arxiv.org/pdf/1601.00670.pdf): This explains the math behind variational inference. One of the authors is an inventor of variational inference.

1. [An introduction to variational autoencoders](https://arxiv.org/pdf/1906.02691.pdf): This is by the inventors of the VAE.

1. [Tutorial: Deriving the Standard Variational Autoencoder (VAE) Loss Function](https://arxiv.org/abs/1907.08956): This is the only paper I've found that walks you through all the details to derive the actual loss function.

#### ADVANCED VAEs

1. [VQ-VAE: Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937): This introduces the vector-quantized variational auto encoder

1. [Conditional VAE: Learning Structured Output Representation using Deep Conditional Generative Models](http://www.cs.toronto.edu/~bonner/courses/2020s/csc2547/papers/generative/conditional-image-generation/conditional-vae,-sohn,-nips2015.pdf): Making a controllable VAE through conditioning

1. [Beta-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework ](https://openreview.net/forum?id=Sy2fzU9gl): This is about making disentangled representations: making the VAEs latent variables meaningful to us.

1. [Isolating Sources of Disentanglement in VAEs](https://arxiv.org/pdf/1802.04942.pdf): More on disentangled representations in VAEs

1. [Ladder VAEs](https://arxiv.org/abs/1602.02282): Hierarchical VAEs 

1. [Adversarial Auto-Encoders](https://arxiv.org/abs/1511.05644): You can guess what this is.

1. [A Wizard's Guide to Adversarial Autoencoders](https://towardsdatascience.com/a-wizards-guide-to-adversarial-autoencoders-part-1-autoencoder-d9a5f8795af4): This is a multi-part tutorial that will be helpfup for understanding AAEs.

1. [From Autoencoder to Beta-VAE](https://lilianweng.github.io/posts/2018-08-12-vae/): Lilian Weng's overview of most kinds of autoencoders

#### VAE Applications

1. [MUSIC VAE: Learning Latent Representations of Music to Generate Interactive Musical Palettes](http://ceur-ws.org/Vol-2068/milc7.pdf): Making controllable music composition with VAEs

1. [Jukebox: A Neural Net that Generates Music](https://openai.com/blog/jukebox/)....with a combination of autoencoders and GANs

1. [Accelerated antimicrobial discovery via deep generative models and molecular dynamics simulations](https://www.nature.com/articles/s41551-021-00689-x): Using a WAE to generate new drugs


### Diffusion Models 

1. [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/): Lilian Weng's blog explaining diffusion models

1. [An Introduction to Diffusion Models](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/): A nice tutorial blog that has Pytorch code.

1. [Deep unsupervised learning using nonequilibrium thermodynamics](http://proceedings.mlr.press/v37/sohl-dickstein15.html): The 2015 paper where diffusion models were introduced. 

1. [Denoising Diffusion Probabilistic Models (DDPM)](https://arxiv.org/abs/2006.11239): This was a break-out paper from 2020 that got people excited about diffusion models.

1. [The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion): This provides a step-by-step walkthrough of the Denoising Diffusion Probabilistic Models, but with pytorch code

1. [Learning in Implicit Generative Models](https://arxiv.org/pdf/1610.03483): This 2017 paper explains what an implicit probabilistic model is. If you don't know what that is, read it before the DDIM paper. 

1. [Denoising Diffusion Implicit Models (DDIM)](https://openreview.net/forum?id=St1giarCHLP): This 2021 paper made it possible to change your step size in diffusion, allowing for far fewer diffusions steps.

1. [The Hugging Face DDIM Notebook](https://huggingface.co/learn/diffusion-course/en/unit4/2): Once you have DDIM Models, you can use it for image editing. Here's how...


### Score Models (The Yang Song section of this page)

1. [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.github.io/blog/2021/score/#connection-to-diffusion-models-and-others): This is a blog that explains how score-based models are also basically diffusion models.

1. [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456):This is the 2021 paper that explicitly bridges the gap between discrete diffusion models (like DDPM/DDIM), score matching, and continuous-time differential equations.

1. [The GitHub page for Score-Based Generative Modeling through SDEs](https://github.com/yang-song/score_sde): Here's the code for the paper.

#### Advanced Diffussion and Score Models

1. [DiffWave: A Versatile Diffusion Model for Audio Synthesis](https://arxiv.org/abs/2009.09761): A neural vocoder done with diffusion from 2021

1. [Universal Speech Enhancement With Score-based Diffusion](https://serrjoa.github.io/projects/universe/)

1. [Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise](https://arxiv.org/abs/2208.09392): Do we need to add noise at each step or would any transform do?


#### Latent Diffusion (as seen in Stability AI's image generator)

1. [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/pdf/2112.10752) : How to use an autoencoder to put images into a latent space so you can do diffusion with fewer resources

1. [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/): Stability AI made a great diffusuion model. Here's a high-level overview of how it works.

#### Combining Diffusion and Transformers

1. [Scalable Diffusion Models with Transformers](https://openaccess.thecvf.com/content/ICCV2023/html/Peebles_Scalable_Diffusion_Models_with_Transformers_ICCV_2023_paper.html): A 2023 paper that uses a Transformer architecture to do diffusion

1. [Long-form Music Generation with Latent Diffusion](https://arxiv.org/pdf/2404.10301): This is a 2024 paper that describes how to use DiT models to do music audio generation

1. [Stable Audio Open](https://arxiv.org/abs/2407.14358): A July 2024 paper that describes the architecture of Stability AI's open-source audio generation model


#### Making diffusion faster

1. [Progressive Distillation for fast sampling of Diffusion Models](https://arxiv.org/pdf/2202.00512): This 2022 ICLR paper introduces the v-prediction objective, which is a weighted sum of of x0 and eps (the two learning objectives typically used in diffusion)

1. [Consistency Trajectory Models](https://consistencytrajectorymodel.github.io/CTM/). For single-step diffusion model sampling, CTM offers diverse sampling options and balances computational budget with sample fidelity effectively.

#### Steerable diffusion (text conditioning)

1. [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/pdf/2105.05233.pdf): This paper describes many technical details used in the GLIDE paper...and therefore in DALL-E-2.  It introduces classifer guidance

1. [Classifier-free Diffusion Guidance](https://arxiv.org/abs/2207.12598): The 2021 paper that defined how we use text prompting w/o a classifier to guide diffusion. 

1. [Guidance: a cheat code for diffusion models](https://benanne.github.io/2022/05/26/guidance.html): if you want to understand DALL-E-2 and Imagen, you need to understand this. It's an easier-to-follow explanation of the Classifier-free Diffusion Guidance idea.

1. [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741): This is paper that lays the groundwork for  DALL-E-2. 

1. [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020): The CLIP representation. This is used in DALL-E-2.

1. [Hierarchical Text-Conditional Image Generation with CLIP Latents](https://arxiv.org/pdf/2204.06125.pdf): The DALL-E-2 paper. 

1. [Prompt-to-Prompt Image Editing with Cross Attention Control](https://arxiv.org/pdf/2208.01626): A 2022 paper that lead to InstructPix2Pix. 

1. [InstructPix2Pix: Learning to Follow Image Editing Instructions](https://arxiv.org/pdf/2211.09800): Made for interactive, editable (with text) image generation.

1. [Sketch2Sound](https://arxiv.org/pdf/2412.08550): A 2025 paper that expands the InstructPix2Pix control framework to use non-text-gestures. Controlling sound generation using other sounds as examples. 

1. [DITTO:Diffusion Inference-Time T-Optimization for Music Generation](https://ditto-music.github.io/web/)

### Raising Awareness about ethical and societal effects of GenAI

1. [Pam Samuelson's AI Meets Copyright](https://www.youtube.com/watch?v=6sDGIrVO6mo). This is a video lecture on generative AI and copyright law from one of top copyright scholars in the USA.

1. [Allocating Ownership Rights in Computer Generated Works](https://www.law.berkeley.edu/wp-content/uploads/2024/01/Pam-Samuelson-Allocating-Ownership-Rights-in-Computer-Generated-Works.pdf)

1. [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf): This is the paper that Timnit Gebru and Margaret Mitchell got fired from Google's Ethical AI team for publishing.

1. [Alignment of Language Agents](https://arxiv.org/abs/2103.14659): This is Deep Mind's critique of their own approach.

1. [Open AI's analysis of GPT-4 potential harms](https://cdn.openai.com/papers/gpt-4-system-card.pdf): Worth a serious read

1. [Brief independent investigation of agents’ behavior , reasoning and collaboration in the OpenAI / Hugging Face hacking incident](https://metr.org/hugging-face-incident-report-aug-2026.pdf): This is from August 2026

### Technological approaches to doing something about ethical and safety concerns

1. [Sociotechnical Safety Evaluation of Generative AI Systems](https://arxiv.org/pdf/2310.11986.pdf): A big overview paper on how to ensure your generative AI is going to minimize possible harms.

1. [Moral Alignment for LLM Agents](https://proceedings.iclr.cc/paper_files/paper/2025/hash/f2b1bad4756ceee8f408e16b8e6e4383-Abstract-Conference.html): a 2025 paper that argues explicitly rewarding cooperation on the Prisoner's dilema will make agents more "moral" 

1. [The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions](https://arxiv.org/pdf/2404.13208)

### How do people feel about Consuming and producing AI generated content?

1. [Foregrounding Artist Opinions: A Survey Study on Transparency, Ownership, and Fairness in AI Generative Art](https://arxiv.org/pdf/2401.15497): What do artists think about GenerativeAI?

1. [Understanding Fans' Attitudes Toward AI-generated Fan Content About Their Favorite Musician](https://dl.acm.org/doi/full/10.1145/3706370.3727855): This is about (mostly) American fans' attitudes to consuming AI-generated music and images, as opposed to using AI to produce them.

1. [Enabling Training Data Attribution for Users of Generative Music Models](https://interactiveaudiolab.github.io/assets/papers/barnett2026aies.pdf): Studies the comfort musicians, videographers, and casual creaters have with posting AI-generated music similar to existing human-generated music. 

### What does using AI do to our thinking?

1. [Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task](https://collimateur.uqam.ca/wp-content/uploads/sites/11/2025/12/2506.08872v1_comp.pdf) 

1. [Thinking—Fast, Slow, and Artificial: How AI is Reshaping Human Reasoning and the Rise of Cognitive Surrender](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6097646) 

### How bad is the memorization problem in generative models?

1. [Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646): Systematic experiments on how model size, prompt length, and frequency of an example in the training set impact our ability to extract memorized content.

1. [Extracting Training Data from Large Language Models](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting): Did GPT-2 memorize a Harry Potter book? Read this and find out.

1. [Extracting books from production language models](https://arxiv.org/html/2601.02671v1): According to this, if you want copyrighted material, just ask Claude.

1. [Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188): Exactly what it sounds like.

1. [Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models](https://arxiv.org/pdf/2212.03860.pdf): Just what it sounds like.


### OTHER TOPICS NOT COVERD IN CLASS (BUT THAT ARE WORTH LEARNING ABOUT)

#### Normalizing Flows

1. [Variational Inference with Normalizing Flows](http://proceedings.mlr.press/v37/rezende15.html): The 2015 paper that introduces a differentiable method to take a simple distribution and make it arbitrarily complex. 

1. [Normalizing Flows for Probabilistic Modeling and Inference](): A 2021 paper that discusses fundamental principles of flow design, expressive power and computational trade-oﬀs, all in a generative modeling context.

1. [An Introduction to Flow Matching and Diffusion Models](https://diffusion.csail.mit.edu/2026/docs/lecture_notes.pdf): Course notes from MIT Class 6.S184: Generative AI With Stochastic Differential Equations, 2026

#### FILM Layers

1. [FiLM: Visual Reasoning with a General Conditioning Layer](https://www.researchgate.net/publication/320014293_FiLM_Visual_Reasoning_with_a_General_Conditioning_Layer): Affine transformation of input layers that proves helpful in many contextx. Here's [the TL;DR version](https://ml-retrospectives.github.io/neurips2019/accepted_retrospectives/2019/film/). I'd start with the TL;DR.

#### Structured State Space Models

1. [Efficiently Modeling Long Sequences with Structured State Spaces](https://arxiv.org/abs/2111.00396)

1. [The Annotated S4](https://srush.github.io/annotated-s4/): This is a guided walk through (with code) of a structured state space model.

1. [It's Raw! Audio Generation with State-Space Models](https://arxiv.org/pdf/2202.09729.pdf)

1. [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752): Adds input-dependent "attention" (selectivity) to SSMs and claims to beat Transformers at their own game.


#### Mesauring quality

1. [MAUVE: Measuring the Gap Between Neural Text and Human Text using Divergence Frontiers](https://arxiv.org/pdf/2102.01454): An alternative to using Frechet distance. Basically, it is a mild generalization of Jenson Shannon divergence.

#### Mechanistic Interpretability

1. [Dissecting Recall of Factual Associations in Auto-Regressive Language Models](https://aclanthology.org/2023.emnlp-main.751.pdf) - How does information move through a transformer?

1. [Chris Olah's essay on mechanistic interpretability](https://www.transformer-circuits.pub/2022/mech-interp-essay)

1. [A list of mechanistic interpretability papers](https://transformer-circuits.pub/)

#### Pardo's latest random reads...

1. [SkillOpt: Executive Strategy for Self-Evolving Agent Skills](https://arxiv.org/pdf/2605.23904): A 2026 paper on an algorithm to learn to create better "skills.md" files as background information prompts.

1. [LVLMs and Humans Ground Differently in Referential Communication](https://arxiv.org/pdf/2601.19792): How do Language Vision Models find common ground?

1. [Causal Tracing of Audio-Text Fusion in Large Audio Language Models](https://arxiv.org/pdf/2603.13768): Where do Language Audio Models merge the language and the audio?

1. [Why AI systems don’t learn and what to do about it: Lessons on autonomous learning from cognitive science](https://arxiv.org/pdf/2603.15381): Yan LeCun's plan for the next stage of AI

1. [Stable Audio 3](https://arxiv.org/pdf/2605.17991): The latest generation of the most influential open-source audio generation models, as of May 2026.

1. [SAME: A semantically-aligned music autoencoder](https://arxiv.org/abs/2605.18613): The autoencoder that Stable Audio 3 uses.

1. [Live Music Diffusion Models](https://arxiv.org/pdf/2605.22717):a simple modification of the generative diffusion process that has the inference complexity of the discrete Live Music Models (LMMs).

