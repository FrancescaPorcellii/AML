# Natural Language Queries in Egocentric Videos  
*Advanced Machine Learning Project - Politecnico di Torino 2025*

---

## Project Description  
This repository showcases the work conducted for the Advanced Machine Learning (AML) final project at Politecnico di Torino. The objective of this project is to efficiently process and answer natural language queries (NLQs) in egocentric video environments. We propose a novel approach that uses large language models (LLMs) to generate synthetic queries from video narrations, followed by a two-step training strategy to enhance query understanding and video localization.

The complete workflow, including training and evaluation steps, is accessible through an interactive Google Colab notebook.

**Quick Access:** [Colab Notebook](https://colab.research.google.com/github/FrancescaPorcellii/AML/blob/main/Ego4D_NLQ_Benchmark.ipynb) | [Baseline Repository](https://github.com/EGO4D/episodic-memory/tree/main/NLQ/VSLNet)

---

## Team Members  
- **Maggiulli Claudia** – [s332252@studenti.polito.it](mailto:s332252@studenti.polito.it)  
- **Porcelli Francesca** – [s324804@studenti.polito.it](mailto:s324804@studenti.polito.it)
- **Sportelli Marco** – [s332224@studenti.polito.it](mailto:s332224@studenti.polito.it)  

---

## Key Highlights  
- **LLM-Powered Query Generation:** Automatically generates synthetic natural language queries (NLQs) from video narrations to augment existing datasets.
- **Two-Phase Training Strategy:** A robust two-step training process that involves pretraining on synthetic NLQs followed by fine-tuning on original datasets.
- **Benchmarking with Ego4D Dataset:** Performance validated on the widely-used Ego4D dataset, leveraging state-of-the-art models and configurations for comprehensive evaluation.

---

## Installation and Requirements  
The project environment is built on Python and deep learning frameworks like PyTorch. All dependencies are listed in the `requirements.txt` file.

To set up the environment locally:
```bash
pip install -r requirements.txt
```
Alternatively, use the pre-configured Google Colab notebook.

---

## Instructions for Use  
To replicate the project and run experiments, follow these steps:

1. **Access the Colab Notebook:**  
   Open the notebook [here](https://colab.research.google.com/github/FrancescaPorcellii/AML/blob/main/Ego4D_NLQ_Benchmark.ipynb).

2. **Dataset Authorization:**  
   Input your credentials in the first code cell to authenticate access to the EGO4D dataset. You must agree to the license terms as detailed [here](https://ego4d-data.org/docs/start-here/#license-agreement).

3. **Download EGOVLP Features (Optional):**  
   If using EGOVLP features, download them from [this link](https://drive.google.com/file/d/1U318S34jw3uNnsURJ1T40YwsSuK5_-RJ/view?usp=share_link) and upload them to your Google Drive under the designated directory for the Colab notebook.

4. **Configuration:**  
   Set the required environment variables in the fifth code cell to customize training and evaluation parameters.

5. **Runtime Settings:**  
   Ensure that the Colab environment is set to use GPU runtime for faster training.

---

## Additional Notes  
This project leverages advanced AI techniques to address challenging real-world scenarios in video understanding. It is designed for easy experimentation and reproducibility, making it suitable for both research and practical applications.

We welcome suggestions and collaborations to further enhance the methodology and extend the project capabilities.

