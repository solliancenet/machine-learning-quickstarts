# Azure Machine Learning service Quickstarts

[Azure Machine Learning service](https://docs.microsoft.com/en-us/azure/machine-learning/service/overview-what-is-azure-ml) is a cloud service for machine learning that support training, deploying, managing, and operationalizing (MLOps) models in Azure using [Azure Machine Learning Python SDK](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/intro?view=azure-ml-py) and [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest). Azure Machine Learning service also provides [Azure Machine Learning Visual Interface](https://docs.microsoft.com/en-us/azure/machine-learning/service/ui-quickstart-run-experiment) (preview) to quickly, prepare data, and train machine learning models.

## 1.0 [Automated Machine Learning in Azure Portal](./quickstart-1.0/README.md)

Learn how to create, run, and explore automated machine learning experiments in the [Azure portal](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-create-portal-experiments) without a single line of code. You will also learn to register and deployed the best trained model, all within the Azure Portal.

## 2.0 [Automated Machine Learning in Azure Notebook VM](./quickstart-2.0/README.md)

This quickstart will show you how to use Automated Machine Learning with [Azure ML Python SDK](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-configure-auto-train) to train, deploy, and test the best model from within Azure Notebook VMs.

## 3.0 [Azure Machine Learning Visual Interface](./quickstart-3.0/README.md)

Azure Machine Learning Visual Interface gives you a cloud-based interactive, visual workspace that you can use to easily and quickly prep data, train and deploy machine learning models. It supports Azure Machine Learning compute, GPU or CPU. Machine Learning Visual Interface also supports publishing models as web services on Azure Kubernetes Service that can easily be consumed by other applications. To use Azure Machine Learning Visual Interface, you do not need programming experience and this quickstart will walk you through an exercise that will show how to process training data, create a model, train, score, and evaluate the model and finally deploy the trained model as a web service.
