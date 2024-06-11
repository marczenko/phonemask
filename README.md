# Ph[]neMask

In this repository, Ph[]neMask experiments are published.

In /Inference/ folder, notebooks with evaluating the resulting models can be found. In /Stats/, the results of the MAPSSWE test are stored (.unified files contain statistics). 
In /Training_history/, notebooks with fine-tuning with different phone masking strategies can be found.

The resulting  models are stored on HuggingFace:


| **Model**                                                   |                         **Link**                         |
|-------------------------------------------------------------|:--------------------------------------------------------:|
| Fine-tuned with SpecAugment                                 | https://huggingface.co/marczenko/ft-sa                   |
| Fine-tuned with spectrograms with palatal consonants masked | https://huggingface.co/marczenko/ft-augmented-consonants |
| Fine-tune with spectrograms with mid vowels masked          | https://huggingface.co/marczenko/ft-augmented-vowels     |
| Tokenizer                                                   | https://huggingface.co/marczenko/whisper_tokenizer       |

Ph[]neMask.ipynb is a notebook that contains code for masking out specified groups of sounds. Data Preprocessing is a technical notebook that contains some steps of the preparation of the dataset.
