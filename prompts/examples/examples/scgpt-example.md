# Example: scGPT

## Source

Cui, H. et al. *scGPT: toward building a foundation model for single-cell multi-omics using generative AI*. Nature Methods, 2024.

## Why I selected this paper

I chose this paper because it combines foundation models with single-cell biology. It is also relevant to my interest in how AI could make biological research and drug discovery more efficient.

## Plain-English summary

The researchers developed scGPT, a foundation model trained using data from more than 33 million cells. The aim was to test whether an AI model could learn general patterns about genes and cells and then apply this knowledge to several biological tasks.

## Biological problem

Single-cell research produces large and complex datasets. Researchers need methods that can identify cell types, combine data from different experiments and predict how cells may respond to changes.

## Methods

The authors created a generative pretrained transformer for single-cell biology. It was pretrained on a large collection of single-cell data and adapted through transfer learning for different tasks.

The abstract does not provide detailed information about the model architecture, training process or evaluation methods.

## Main findings

According to the abstract, scGPT was applied to:

* Cell-type annotation
* Integration of data from different batches
* Multi-omics integration
* Prediction of responses to perturbations
* Gene-network inference

The authors report that the model learned useful representations of genes and cells and performed strongly across these tasks.

## Possible relevance to drug discovery

The ability to analyse cell types, combine molecular datasets and predict cellular responses to perturbations could support biological research connected to target discovery or treatment development.

However, the abstract does not describe a direct drug-discovery application or show that the model can replace experimental validation.

## Limitations and unanswered questions

The abstract does not provide enough detail to assess:

* Which comparison methods were used
* How performance was measured
* How well the model works on completely unseen datasets
* The computing resources required
* Whether its predictions reflect causal biological relationships

These questions would require reviewing the full paper rather than the abstract alone.

## Verification checklist

A human reviewer should check:

* Whether the reported tasks match the original abstract
* Whether performance claims are supported by the full results
* Whether the evaluation data were separate from the pretraining data
* Whether possible drug-discovery relevance has been presented as a possibility rather than a proven outcome

## Human review

The first AI-generated response included useful observations, but it also introduced detailed criticisms about data leakage, computational costs and biological generalisation that were not stated in the abstract.

I shortened the output, separated facts from possible implications and clearly identified where the abstract did not provide enough information.

## Reflection

This test showed that AI can organise a technical abstract quickly, but it may add reasonable-sounding assumptions beyond the source. Human review was therefore necessary to keep the summary accurate and avoid overstating the paper’s relevance.
