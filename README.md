# awesome-speech-recognition-speech-synthesis-papers
automatic speech recognition/speech synthesis paper roadmap, including HMM, DNN, RNN, CNN, Seq2Seq, Attention

## Introduction
Automatic Speech Recognition has been investigated for several decades, and speech recognition models are from HMM-GMM to deep neural networks today. It's very necessary to see the history of speech recognition by this awesome paper roadmap. I will cover papers from traditional models to nowadays popular models, not only acoustic models or ASR systems, but also many interesting language models.

## Paper List

### Automatic Speech Recognition
- **An Introduction to the Application of the Theory of Probabilistic Functions of a Markov Process to Automatic Speech Recognition**(1982), S. E. LEVINSON et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6768244)

- **A Maximum Likelihood Approach to Continuous Speech Recognition**(1983), LALIT R. BAHL et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4767370&tag=1)

- **Heterogeneous Acoustic Measurements and Multiple Classifiers for Speech Recognition**(1986), Andrew K. Halberstadt. [[pdf]](https://groups.csail.mit.edu/sls/publications/1998/phdthesis-drew.pdf)

- **Maximum Mutual Information Estimation of Hidden Markov Model Parameters for Speech Recognition**(1986), Lalit R. Bahi et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1169179)

- **A Tutorial on Hidden Markov Models and Selected Applications in Speech Recognition**(1989), Lawrence R Rabiner. [[pdf]](https://pdfs.semanticscholar.org/fb04/6159dfb4a2beb95756fe1116056a6d922565.pdf?\_ga=2.37020706.362861000.1494045851-921183529.1494045851)

- **Phoneme recognition using time-delay neural networks**(1989), Alexander H. Waibel et al. [[pdf]](https://pdfs.semanticscholar.org/b554/da42487697cb0d01a4146858e966c1d2404f.pdf?\_ga=2.97032540.235965811.1494658719-1308334183.1494658711)

- **Speaker-independent phone recognition using hidden Markov models**(1989), Kai-Fu Lee et al. [[pdf]](http://repository.cmu.edu/cgi/viewcontent.cgi?article=2768&context=compsci)

- **Hidden Markov Models for Speech Recognition**(1991), B. H. Juang et al. [[pdf]](http://www.jstor.org/stable/1268779)

- **Connectionist Speech Recognition: A Hybrid Approach**(1994), Herve Bourlard et al. [[pdf]](https://www.researchgate.net/profile/Herve\_Bourlard/publication/230875873\_Connectionist\_Speech\_Recognition\_A\_Hybrid\_Approach/links/0deec5149eb889b8c7000000/Connectionist-Speech-Recognition-A-Hybrid-Approach.pdf)

- **A post-processing system to yield reduced word error rates: Recognizer Output Voting Error Reduction (ROVER)**(1997), J.G. Fiscus. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=659110)

- **Speech recognition with weighted finite-state transducers**(2001), M Mohri et al. [[pdf]](https://cs.nyu.edu/~mohri/pub/hbka.pdf)

- **Review of Tdnn (time Delay Neural Network) Architectures for Speech Recognition**(2014), Masahide Sugiyamat et al. [[pdf]](https://pdfs.semanticscholar.org/073b/6128f04fe4b88b88ae297615af289c308753.pdf?\_ga=2.103860032.1725061846.1494658711-1308334183.1494658711)

- **Framewise phoneme classification with bidirectional LSTM and other neural network architectures**(2005), Alex Graves et al. [[pdf]](https://pdfs.semanticscholar.org/83d6/1d9b71a838aa150d7ef232dc6d4c73e24250.pdf?\_ga=1.187838062.730356906.1493526584)

- **Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks**(2006), Alex Graves et al. [[pdf]](https://pdfs.semanticscholar.org/daed/0db4538e1a83b4680545b44e3083843168e7.pdf?\_ga=1.45211874.730356906.1493526584)

- **The kaldi speech recognition toolkit**(2011), Daniel Povey et al. [[pdf]](http://publications.idiap.ch/downloads/reports/2011/Povey\_Idiap-RR-04-2012.pdf)

- **Applying Convolutional Neural Networks concepts to hybrid NN-HMM model for speech recognition**(2012), Ossama Abdel-Hamid et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6288864)

- **Context-Dependent Pre-Trained Deep Neural Networks for Large-Vocabulary Speech Recognition**(2012), George E. Dahl et al. [[pdf]](http://ieeexplore.ieee.org/document/5740583/?part=1)

- **Deep Neural Networks for Acoustic Modeling in Speech Recognition**(2012), Geoffrey Hinton et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6296526)

- **Sequence Transduction with Recurrent Neural Networks**(2012), Alex Graves et al. [[pdf]](https://arxiv.org/pdf/1211.3711.pdf)

- **Deep convolutional neural networks for LVCSR**(2013), Tara N. Sainath et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6639347)

- **Improving deep neural networks for LVCSR using rectified linear units and dropout**(2013), George E. Dahl et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6639346)

- **Improving low-resource CD-DNN-HMM using dropout and multilingual DNN training**(2013), Yajie Miao et al. [[pdf]](https://pdfs.semanticscholar.org/a818/a229c70161d6e46f9861bb5b7d59065d3982.pdf?\_ga=1.187845614.730356906.1493526584)

- **Improvements to deep convolutional neural networks for LVCSR**(2013), Tara N. Sainath et al. [[pdf]](https://pdfs.semanticscholar.org/b299/c8878276d837f9417eb4760ad7b69edb0b58.pdf?\_ga=1.150662000.730356906.1493526584)

- **Machine Learning Paradigms for Speech Recognition: An Overview**(2013), Li Deng et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6423821)

- **Recent advances in deep learning for speech research at Microsoft**(2013), Li Deng et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6639345)

- **Speech recognition with deep recurrent neural networks**(2013), Alex Graves et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6638947)

- **Convolutional deep maxout networks for phone recognition**(2014), László Tóth et al. [[pdf]](https://pdfs.semanticscholar.org/0a24/5098455a6663f922a83d318f7b61d357ab1f.pdf?\_ga=1.218359519.730356906.1493526584)

- **Convolutional Neural Networks for Speech Recognition**(2014), Ossama Abdel-Hamid et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6857341)

- **Combining time- and frequency-domain convolution in convolutional neural network-based phone recognition**(2014), László Tóth. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6853584)

- **Deep Speech: Scaling up end-to-end speech recognition**(2014), Awni Y. Hannun et al. [[pdf]](https://arxiv.org/pdf/1412.5567.pdf)

- **End-to-end Continuous Speech Recognition using Attention-based Recurrent NN: First Results**(2014), Jan Chorowski et al. [[pdf]](https://arxiv.org/pdf/1412.1602.pdf)

- **First-Pass Large Vocabulary Continuous Speech Recognition using Bi-Directional Recurrent DNNs**(2014), Andrew L. Maas et al. [[pdf]](https://arxiv.org/pdf/1408.2873.pdf)

- **Long short-term memory recurrent neural network architectures for large scale acoustic modeling**(2014), Hasim Sak et al. [[pdf]](https://pdfs.semanticscholar.org/c85d/46a94768bdcf7ffcb844b47c5b8e8e8234a3.pdf?\_ga=1.8585459.730356906.1493526584)

- **Robust CNN-based speech recognition with Gabor filter kernels**(2014), Shuo-Yiin Chang et al. [[pdf]](https://pdfs.semanticscholar.org/1d34/0fe19026b0359bde23fcd7299a99a240bd15.pdf?\_ga=1.184683503.730356906.1493526584)

- **Stochastic pooling maxout networks for low-resource speech recognition**(2014), Meng Cai et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6854204)

- **Towards End-to-End Speech Recognition with Recurrent Neural Networks**(2014), Alex Graves et al. [[pdf]](https://pdfs.semanticscholar.org/0fa5/53cfa0cf3cbdf7a913aa2ae789a757dfb32f.pdf?\_ga=1.214035281.730356906.1493526584)

- **A neural transducer**(2015), N Jaitly et al. [[pdf]](https://arxiv.org/abs/1511.04868)

- **Attention-Based Models for Speech Recognition**(2015), Jan Chorowski et al. [[pdf]](https://pdfs.semanticscholar.org/b624/504240fa52ab76167acfe3156150ca01cf3b.pdf?\_ga=1.50080608.730356906.1493526584)

- **Analysis of CNN-based speech recognition system using raw speech as input**(2015), Dimitri Palaz et al. [[pdf]](https://pdfs.semanticscholar.org/31f5/36e48482fc273d521525604606f417638881.pdf?\_ga=1.213722706.730356906.1493526584)

- **Convolutional, Long Short-Term Memory, fully connected Deep Neural Networks**(2015), Tara N. Sainath et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7178838)

- **Deep convolutional neural networks for acoustic modeling in low resource languages**(2015), William Chan et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7178332)

- **Deep Neural Networks for Single-Channel Multi-Talker Speech Recognition**(2015), Chao Weng et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7122291)

- **EESEN: End-to-end speech recognition using deep RNN models and WFST-based decoding**(2015), Y Miao et al. [[pdf]](https://arxiv.org/pdf/1507.08240.pdf)

- **Fast and Accurate Recurrent Neural Network Acoustic Models for Speech Recognition**(2015), Hasim Sak et al. [[pdf]](https://pdfs.semanticscholar.org/9fca/2af9a0e3f2c5c3ed47abb3ebd21b7265ac2b.pdf?\_ga=1.222094174.730356906.1493526584)

- **Lexicon-Free Conversational Speech Recognition with Neural Networks**(2015), Andrew L. Maas et al. [[pdf]](https://pdfs.semanticscholar.org/55ee/875b9039febd378a3f8ac4e3d7603f83d57c.pdf?\_ga=2.128588684.1093285980.1494121465-1276580355.1494121465)

- **Online Sequence Training of Recurrent Neural Networks with Connectionist Temporal Classification**(2015), Kyuyeon Hwang et al. [[pdf]](https://arxiv.org/pdf/1511.06841.pdf)

- **Advances in All-Neural Speech Recognition**(2016), Geoffrey Zweig et al. [[pdf]](https://arxiv.org/pdf/1609.05935.pdf)

- **Advances in Very Deep Convolutional Neural Networks for LVCSR**(2016), Tom Sercu et al. [[pdf]](https://pdfs.semanticscholar.org/76b1/791f2d2776c4d3dd671b7e4f2a9fb3575703.pdf?\_ga=1.150210288.730356906.1493526584)

- **End-to-end attention-based large vocabulary speech recognition**(2016), Dzmitry Bahdanau et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7472618)

- **Deep Convolutional Neural Networks with Layer-Wise Context Expansion and Attention**(2016), Dong Yu et al. [[pdf]](https://pdfs.semanticscholar.org/8926/fa45d9fc76523766a9d65e2c3b4a9c3feb88.pdf?\_ga=1.37888869.730356906.1493526584)

- **Deep Speech 2: End-to-End Speech Recognition in English and Mandarin**(2016), Dario Amodei et al. [[pdf]](https://pdfs.semanticscholar.org/c2ba/9d550bbfb542e9fdd6e817e9be15585d0f47.pdf?\_ga=1.248137409.730356906.1493526584)

- **End-to-end attention-based distant speech recognition with Highway LSTM**(2016), Hassan Taherian. [[pdf]](https://arxiv.org/pdf/1610.05361.pdf)

- **Joint CTC-Attention based End-to-End Speech Recognition using Multi-task Learning**(2016), Suyoun Kim et al. [[pdf]](https://arxiv.org/pdf/1609.06773.pdf)

- **Listen, attend and spell: A neural network for large vocabulary conversational speech recognition**(2016), William Chan et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7472621)

- **Latent Sequence Decompositions**(2016), William Chan et al. [[pdf]](https://arxiv.org/pdf/1610.03035.pdf)

- **Modeling Time-Frequency Patterns with LSTM vs. Convolutional Architectures for LVCSR Tasks**(2016), Tara N. Sainath et al. [[pdf]](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/45401.pdf)

- **Recurrent Models for Auditory Attention in Multi-Microphone Distance Speech Recognition**(2016), Suyoun Kim et al. [[pdf]](https://pdfs.semanticscholar.org/b9fc/cd8bee6e6998b87b4efc671dbcee45917282.pdf?\_ga=2.168507874.235965811.1494658719-1308334183.1494658711)

- **Segmental Recurrent Neural Networks for End-to-End Speech Recognition**(2016), Liang Lu et al. [[pdf]](https://pdfs.semanticscholar.org/8477/ec32bc1dde071bed8174348da5cd6740dab0.pdf?\_ga=1.220546782.730356906.1493526584)

- **Towards better decoding and language model integration in sequence to sequence models**(2016), Jan Chorowski et al. [[pdf]](https://arxiv.org/pdf/1612.02695.pdf)

- **Very Deep Convolutional Neural Networks for Noise Robust Speech Recognition**(2016), Yanmin Qian et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7552554)

- **Very Deep Convolutional Networks for End-to-End Speech Recognition**(2016), Yu Zhang et al. [[pdf]](https://arxiv.org/pdf/1610.03022.pdf)

- **Very deep multilingual convolutional neural networks for LVCSR**(2016), Tom Sercu et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7472620)

- **Wav2Letter: an End-to-End ConvNet-based Speech Recognition System**(2016), Ronan Collobert et al. [[pdf]](https://arxiv.org/pdf/1609.03193.pdf)

- **WaveNet: A Generative Model for Raw Audio**(2016), Aäron van den Oord et al. [[pdf]](https://arxiv.org/pdf/1609.03499.pdf)

- **Attentive Convolutional Neural Network based Speech Emotion Recognition: A Study on the Impact of Input Features, Signal Length, and Acted Speech**(2017), Michael Neumann et al. [[pdf]](https://arxiv.org/pdf/1706.00612)

- **An enhanced automatic speech recognition system for Arabic**(2017), Mohamed Amine Menacer et al. [[pdf]](https://pdfs.semanticscholar.org/788e/b75befd9c2597f64e072cb2e86f9e7a877e4.pdf?\_ga=1.188540654.730356906.1493526584)

- **Advances in Joint CTC-Attention based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM**(2017), Takaaki Hori et al. [[pdf]](https://arxiv.org/pdf/1706.02737)

- **A network of deep neural networks for distant speech recognition**(2017), Mirco Ravanelli et al. [[pdf]](https://arxiv.org/pdf/1703.08002.pdf)

- **An online sequence-to-sequence model for noisy speech recognition**(2017), Chung-Cheng Chiu et al. [[pdf]](https://arxiv.org/pdf/1706.06428.pdf)

- **An Unsupervised Speaker Clustering Technique based on SOM and I-vectors for Speech Recognition Systems**(2017), Hany Ahmed et al. [[pdf]](https://pdfs.semanticscholar.org/f5be/2cb9d37e5e54c5d20644ff7025cdee14995f.pdf?\_ga=1.185419759.730356906.1493526584)

- **Attention-Based End-to-End Speech Recognition in Mandarin**(2017), C Shan et al. [[pdf]](https://arxiv.org/abs/1707.07167)

- **Building DNN acoustic models for large vocabulary speech recognition**(2017), Andrew L. Maas et al. [[pdf]](https://pdfs.semanticscholar.org/ff7b/9fbbbdc78d874fa93134d643a5a0295f648f.pdf?\_ga=1.242426692.730356906.1493526584)

- **Direct Acoustics-to-Word Models for English Conversational Speech Recognition**(2017), Kartik Audhkhasi et al. [[pdf]](https://arxiv.org/pdf/1703.07754.pdf)

- **Deep Learning for Environmentally Robust Speech Recognition: An Overview of Recent Developments**(2017), Zixing Zhang et al. [[pdf]](https://arxiv.org/pdf/1705.10874)

- **English Conversational Telephone Speech Recognition by Humans and Machines**(2017), George Saon et al. [[pdf]](https://arxiv.org/pdf/1703.02136.pdf)

- **ESE: Efficient Speech Recognition Engine with Sparse LSTM on FPGA**(2017), Song Han et al. [[pdf]](http://dl.acm.org/citation.cfm?id=3021745)

- **Exploring Speech Enhancement with Generative Adversarial Networks for Robust Speech Recognition**(2017), Chris Donahue et al. [[pdf]](https://arxiv.org/pdf/1711.05747)

- **Deep LSTM for Large Vocabulary Continuous Speech Recognition**(2017), Xu Tian et al. [[pdf]](https://arxiv.org/pdf/1703.07090.pdf)

- **Dynamic Layer Normalization for Adaptive Neural Acoustic Modeling in Speech Recognition**(2017), Taesup Kim et al. [[pdf]](https://arxiv.org/pdf/1707.06065v1.pdf)

- **Gram-CTC: Automatic Unit Selection and Target Decomposition for Sequence Labelling**(2017), Hairong Liu et al. [[pdf]](https://arxiv.org/pdf/1703.00096.pdf)

- **Improving the Performance of Online Neural Transducer Models**(2017), Tara N. Sainath et al. [[pdf]](https://arxiv.org/pdf/1712.01807)

- **Learning Filterbanks from Raw Speech for Phone Recognition**(2017), Neil Zeghidour et al. [[pdf]](https://arxiv.org/pdf/1711.01161)

- **Multichannel End-to-end Speech Recognition**(2017), Tsubasa Ochiai et al. [[pdf]](https://arxiv.org/pdf/1703.04783.pdf)

- **Multi-task Learning with CTC and Segmental CRF for Speech Recognition**(2017), Liang Lu et al. [[pdf]](https://arxiv.org/pdf/1702.06378.pdf)

- **Multichannel Signal Processing With Deep Neural Networks for Automatic Speech Recognition**(2017), Tara N. Sainath et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7859320)

- **Multilingual Speech Recognition With A Single End-To-End Model**(2017), Shubham Toshniwal et al. [[pdf]](https://arxiv.org/pdf/1711.01694)

- **Optimizing expected word error rate via sampling for speech recognition**(2017), Matt Shannon. [[pdf]](https://arxiv.org/pdf/1706.02776)

- **Residual Convolutional CTC Networks for Automatic Speech Recognition**(2017), Yisen Wang et al. [[pdf]](https://arxiv.org/pdf/1702.07793.pdf)

- **Residual LSTM: Design of a Deep Recurrent Architecture for Distant Speech Recognition**(2017), Jaeyoung Kim et al. [[pdf]](https://arxiv.org/pdf/1701.03360.pdf)

- **Recurrent Models for Auditory Attention in Multi-Microphone Distance Speech Recognition**(2017), Suyoun Kim et al. [[pdf]](https://pdfs.semanticscholar.org/b9fc/cd8bee6e6998b87b4efc671dbcee45917282.pdf?\_ga=2.162545140.93942331.1493904208-1691509212.1493904208)

- **Reducing Bias in Production Speech Models**(2017), Eric Battenberg et al. [[pdf]](https://arxiv.org/pdf/1705.04400.pdf)

- **Robust Speech Recognition Using Generative Adversarial Networks**(2017), Anuroop Sriram et al. [[pdf]](https://arxiv.org/pdf/1711.01567)

- **State-of-the-art Speech Recognition With Sequence-to-Sequence Models**(2017), Chung-Cheng Chiu et al. [[pdf]](https://arxiv.org/pdf/1712.01769)

- **Towards Language-Universal End-to-End Speech Recognition**(2017), Suyoun Kim et al. [[pdf]](https://arxiv.org/pdf/1711.02207)

- **Accelerating recurrent neural network language model based online speech recognition system**(2018), K Lee et al. [[pdf]](https://arxiv.org/pdf/1801.09866)


### Speaker Verification
- **Speaker Verification Using Adapted Gaussian Mixture Models**(2000), Douglas A.Reynolds et al. [[pdf]](http://www.sciencedirect.com/science/article/pii/S1051200499903615#)

- **A tutorial on text-independent speaker verification**(2004), Frédéric Bimbot et al. [[pdf]](https://dl.acm.org/ft\_gateway.cfm?id=1289376&ftid=464492&dwn=1&CFID=843437542&CFTOKEN=31448020)

- **Deep neural networks for small footprint text-dependent speaker verification**(2014), E Variani et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6854363)

- **Deep Speaker Vectors for Semi Text-independent Speaker Verification**(2015), Lantian Li et al. [[pdf]](https://arxiv.org/pdf/1505.06427)

- **Deep Speaker: an End-to-End Neural Speaker Embedding System**(2017), Chao Li et al. [[pdf]](https://arxiv.org/pdf/1705.02304.pdf)

- **Deep Speaker Feature Learning for Text-independent Speaker Verification**(2017), Lantian Li et al. [[pdf]](https://arxiv.org/pdf/1705.03670)

- **Deep Speaker Verification: Do We Need End to End?**(2017), Dong Wang et al. [[pdf]](https://arxiv.org/pdf/1706.07859)

- **Speaker Diarization with LSTM**(2017), Quan Wang et al. [[pdf]](https://arxiv.org/pdf/1710.10468)

- **Text-Independent Speaker Verification Using 3D Convolutional Neural Networks**(2017), Amirsina Torfi et al. [[pdf]](https://arxiv.org/pdf/1705.09422)


### Speech Synthesis
- **Signal estimation from modified short-time Fourier transform**(1993), Daniel W. Griffin et al. [[pdf]](https://pdfs.semanticscholar.org/ade8/d1511a61d78948bb0d43e207593389935421.pdf?\_ga=2.229355228.1725061846.1494658711-1308334183.1494658711)

- **Text-to-speech synthesis**(2009), Paul Taylor et al. [[pdf]](https://books.google.com/books?hl=zh-CN&lr=&id=BFnkm-FpBAUC&oi=fnd&pg=PR9&dq=Text-to-Speech+Synthesis&ots=ucm6pVQ0bW&sig=1ZoIFILLQLbdHtJu0MlLHkmPnqE#v=onepage&q=Text-to-Speech%20Synthesis&f=false)

- **A fast Griffin-Lim algorithm**(2013), Nathanael Perraudin et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6701851)

- **First Step Towards End-to-End Parametric TTS Synthesis: Generating Spectral Parameters with Neural Attention**(2016), Wenfu Wang et al. [[pdf]](http://doi.org/10.21437/Interspeech.2016-134)

- **Recent Advances in Google Real-Time HMM-Driven Unit Selection Synthesizer**(2016), Xavi Gonzalvo et al. [[pdf]](http://doi.org/10.21437/Interspeech.2016-264)

- **SampleRNN: An Unconditional End-to-End Neural Audio Generation Model**(2016), Soroush Mehri et al. [[pdf]](https://arxiv.org/pdf/1612.07837.pdf)

- **WaveNet: A Generative Model for Raw Audio**(2016), Aäron van den Oord et al. [[pdf]](https://arxiv.org/pdf/1609.03499.pdf)

- **Char2Wav: End-to-end speech synthesis**(2017), J Sotelo et al. [[pdf]](https://openreview.net/forum?id=B1VWyySKx)

- **Deep Voice: Real-time Neural Text-to-Speech**(2017), Sercan O. Arik et al. [[pdf]](https://arxiv.org/pdf/1702.07825.pdf)

- **Deep Voice 2: Multi-Speaker Neural Text-to-Speech**(2017), Sercan Arik et al. [[pdf]](https://arxiv.org/pdf/1705.08947)

- **Deep Voice 3: 2000-Speaker Neural Text-to-speech**(2017), Wei Ping et al. [[pdf]](https://arxiv.org/pdf/1710.07654)

- **Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions**(2017), Jonathan Shen et al. [[pdf]](https://arxiv.org/pdf/1712.05884)

- **Parallel WaveNet: Fast High-Fidelity Speech Synthesis**(2017), Aaron van den Oord et al. [[pdf]](https://arxiv.org/pdf/1711.10433)

- **Statistical Parametric Speech Synthesis Using Generative Adversarial Networks Under A Multi-task Learning Framework**(2017), S Yang et al. [[pdf]](https://arxiv.org/pdf/1707.01670)

- **Tacotron: Towards End-to-End Speech Synthesis**(2017), Yuxuan Wang et al. [[pdf]](https://pdfs.semanticscholar.org/a072/c2a400f62f720b68dc54a662fb1ae115bf06.pdf?\_ga=2.133718478.1725061846.1494658711-1308334183.1494658711)

- **Uncovering Latent Style Factors for Expressive Speech Synthesis**(2017), Yuxuan Wang et al. [[pdf]](https://arxiv.org/pdf/1711.00520)

- **VoiceLoop: Voice Fitting and Synthesis via a Phonological Loop**(2017), Yaniv Taigman et al. [[pdf]](https://arxiv.org/pdf/1707.06588)

- **Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions**(2017), Jonathan Shen et al. [[pdf]](https://arxiv.org/pdf/1712.05884)

- **Neural Voice Cloning with a Few Samples**(2018), Sercan O. Arık ,  Jitong Chen , 1 Kainan Peng , Wei Ping *  et al. [[pdf]](https://arxiv.org/pdf/1802.06006.pdf)


### Language Modelling
- **Class-Based n-gram Models of Natural Language**(1992), Peter F. Brown et al. [[pdf]](https://pdfs.semanticscholar.org/ce84/cf6160ab221d5ee67afad046d2b89560749d.pdf?\_ga=2.197138663.999867306.1494660639-1308334183.1494658711)

- **An empirical study of smoothing techniques for language modeling**(1996), Stanley F. Chen et al. [[pdf]](https://dl.acm.org/ft\_gateway.cfm?id=981904&ftid=567802&dwn=1&CFID=843437542&CFTOKEN=31448020)

- **A Neural Probabilistic Language Model**(2000), Yoshua Bengio et al. [[pdf]](https://pdfs.semanticscholar.org/8d43/4a90b68fd0f2592d6fe7acf67d232123ad67.pdf?\_ga=2.262836293.895163446.1494660654-1308334183.1494658711)

- **A new statistical approach to Chinese Pinyin input**(2000), Zheng Chen et al. [[pdf]](https://dl.acm.org/ft\_gateway.cfm?id=1075249&ftid=261667&dwn=1&CFID=843437542&CFTOKEN=31448020)

- **Discriminative n-gram language modeling**(2007), Brian Roark et al. [[pdf]](https://pdfs.semanticscholar.org/b258/5b3cdcb81db887f756b8f90fd0e04f9ef952.pdf?\_ga=2.103398592.1137797782.1494660710-1308334183.1494658711)

- **Neural Network Language Model for Chinese Pinyin Input Method Engine**(2015), S Chen et al. [[pdf]](https://pdfs.semanticscholar.org/1294/f49cf1a7397f0423ec617a78c7995139bc5b.pdf)

- **Efficient Training and Evaluation of Recurrent Neural Network Language Models for Automatic Speech Recognition**(2016), Xie Chen et al. [[pdf]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7533441)

- **Exploring the limits of language modeling**(2016), R Jozefowicz et al. [[pdf]](https://arxiv.org/pdf/1602.02410)

- **On the State of the Art of Evaluation in Neural Language Models**(2016), G Melis et al. [[pdf]](https://arxiv.org/pdf/1707.05589)

## Contact Me
For any questions, welcome to send email to :**zzw922cn@gmail.com**. Thanks!
