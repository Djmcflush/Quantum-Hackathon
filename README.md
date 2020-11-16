# Quantum-Hackathon


A joint collaboration hackathon using IBM Qskit

Idea behind our project is to reproduce the work of https://github.com/nikhilmaram/Show_and_Tell with Quantum Computing. A CNN - LSTM network capable of captioning images with detailed sentences. The portion of the work that we hope to reproduce is the CNN, the LSTM will stay classic combining for a hybrid Quantum-Classical model. We will then compare the results of our project to the orgininal paper. 

This neural system for image captioning is roughly based on the paper "Show and Tell: A Neural Image Caption Generatorn" by Vinayls et al. (ICML2015). The input is an image, and the output is a sentence describing the content of the image. It uses a convolutional neural network to extract visual features from the image, and uses a LSTM recurrent neural network to decode these features into a sentence. This project is implemented using the Tensorflow library, and allows end-to-end training of both CNN and RNN parts.

Large Parts of this repo are also derived from the work of https://github.com/Shedka/citiesatnight , Thanks for giving examples of how to implement FRQI and also Quantum State Overlap



Prerequisites:

IBM QISKIT 
Tensorflow
NumPy
OpenCV 
Natural Language Toolkit (NLTK) 
Pandas 
Matplotlib 
tqdm 


References

[1]https://arxiv.org/pdf/1411.4555.pdf. By Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan ICML 2015.
[2] Adapted from earlier implementation in Tensorflow https://github.com/DeepRNN/image_captioning
[3]Adapeted and inspired by https://github.com/nikhilmaram/Show_and_Tell 
[4] https://arxiv.org/pdf/1801.01465.pdf
[5] https://arxiv.org/pdf/1812.11042.pdf
[6] https://www.jstage.jst.go.jp/article/fss/25/0/25_0_185/_pdf
[7] https://www.researchgate.net/publication/333585825_Quantum_Image_Edge_Detection_Algorithm
[8] https://pdfs.semanticscholar.org/b1d1/e8a9d6173458687bdfdc5a654423444f15b0.pdf
[9] https://arxiv.org/abs/1803.04114
[10] https://github.com/Shedka/citiesatnight
