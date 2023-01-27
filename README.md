# Python samples for Azure Cognitive Search

This repository contains Python code samples used in Azure Cognitive Search documentation. Unless noted otherwise, all samples run on the shared (free) pricing tier of an [Azure Cognitive Search service](https://learn.microsoft.com/azure/search/search-create-service-portal).

| Sample | Description |
|--------|-------------|
| azureml-custom-skill | This sample is a Jupyter Python3 .ipynb file. It's used in the [Tutorial: Build and deploy a custom skill with Azure Machine Learning](https://docs.microsoft.com/azure/search/cognitive-search-tutorial-aml-custom-skill). This sample provides an end-to-end walk through for training and deploying an aspect-based sentiment model to an Azure Kubernetes cluster for consumption as a custom skill in a Cognitive Search enrichment pipeline. Azure Machine Learning is used to train and deploy the model. |
| image-processing | This sample is a Jupyter Python3 .ipynb file that shows how to work with image skills in a skillset. Although the skillset performs useful operations, including Optical Character Recognition (OCR) and redaction of personally identifying information, the sample's purpose is to demonstrate the coordination of image file handoffs from one skill to the next. |
| quickstart | "Day One" introduction to the fundamental tasks of working with a search index: create, load, and query. This sample is a Jupyter Python3 .ipynb file. The index is modeled on a subset of the Hotels dataset, widely used in Cognitive Search samples, but reduced here for readability and comprehension. |
| tutorial-ai-enrichment | This sample is a Jupyter Python3 .ipynb file used in the [Python Tutorial: Call Cognitive Services APIs in an Azure Cognitive Search indexing pipeline](https://docs.microsoft.com/azure/search/cognitive-search-tutorial-blob-python). This sample demonstrates cognitive search functionality, adding AI enrichments from Cognitive Services to extract, detect, and analyze information from image files or large unstructured document files. |
| search-website-functions-v4 | Shows how to create, load, and query a search index in Python using the Azure.Search.Documents library in the Azure SDK for Python. It also includes application code and sample data so that you can see search integration in the context of a full app. The data is from [https://github.com/zygmuntz/goodbooks-10k](https://github.com/zygmuntz/goodbooks-10k). The app is an Azure Static Web app, using the React library for user interaction, and Azure Function to handle the query requests and responses in the application layer. |
