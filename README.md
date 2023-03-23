# CausalEdu Dataset



## Introduction

We present the **CausalEdu** dataset, a collaborative effort between [Microsoft Research](https://www.microsoft.com/en-us/research/) and [Eedi](https://eedi.com/), a company specializing in online education. This dataset aims to provide a unique opportunity for the researchers to evaluate their model performance in real-world causal discovery and inference tasks. 

CausalEdu is derived from the online education platform, which captures the performance of school students aged 11 to 16 in multiple-choice questions related to mathematical concepts, referred to as constructs. To overcome the absence of real-world ground truth, A/B tests have been conducted on the learning platform, together with the expert opinions regarding the causal connections between constructs, to obtain ground-truth causal relationships and the CATE. This unique feature makes **CausalEdu** stand out among other benchmark datasets for timeseries causal evaluation



## Technical details and dataset description

For technical details including the detailed description of the dataset files, A/B testing procedure, and how we obtain the ground truth causal relations and CATE values, please refer to the [technical paper](https://github.com/Eedi/CausalEdu/blob/master/Clear_Datasets_causal_edu.pdf).