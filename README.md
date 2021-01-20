# NeuralQA Demo: Question Answering with BERT Models

NeuralQA is a prebuilt Python library that provides an easy to use API and visual interface for end-to-end extractive question answering (passage retrieval, query expansion, document reading, model explanation) on large datasets with BERT. This repository provides sample code demonstrating how to deploy NeuralQA as an application running on Cloudera Machine Learning (CML).

> To learn more about the NeuralQA library visit the [Github repo](https://github.com/victordibia/neuralqa) and for more information on the techniques behind extractive question answering, check out our blog series [FF14 Automated Question Answering](https://qa.fastforwardlabs.com/) 

![Neural QA Screenshot](docs/images/manual.jpg)

# Launch the Application on CML

There are two ways to launch the NeuralQA prototype on CML:

1. **From Prototype Catalog** - Navigate to the Prototype Catalog on a CML workspace, select the "Neural Question Answering" tile, click "Launch as Project", click "Configure Project"
2. **As ML Prototype** - In a CML workspace, click "New Project", add a Project Name, select "ML Prototype" as the Initial Setup option, copy in the [repo URL](https://github.com/cloudera/CML_AMP_NeuralQA), click "Create Project", click "Configure Project"

> Note: NeuralQA depends on several heavy libraries (Tensorflow, Pytorch, Transformers etc). A minimum of 6GB memory instance is recommended to run this template.
