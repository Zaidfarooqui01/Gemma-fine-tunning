# Gemma-fine-tunning
Fine tune Gemma model With Custom Data in Keras using LoRA

# To complete this tutorial, you will first need to complete the setup instructions at Gemma setup. The Gemma setup instructions show you how to do the following:

# Get access to Gemma on kaggle.com.
- Select a Colab runtime with sufficient resources to run the Gemma 2B model.
- Generate and configure a Kaggle username and API key.
- After you've completed the Gemma setup, move on to the next section, where you'll set environment variables for your Colab environment.

# Select the runtime
To complete this tutorial, you'll need to have a Colab runtime with sufficient resources to run the Gemma model. In this case, you can use a T4 GPU:

In the upper-right of the Colab window, select ▾ (Additional connection options).
Select Change runtime type.
Under Hardware accelerator, select T4 GPU.

# Configure your API key
To use Gemma, you must provide your Kaggle username and a Kaggle API key.

To generate a Kaggle API key, go to the Account tab of your Kaggle user profile and select Create New Token. This will trigger the download of a kaggle.json file containing your API credentials.

In Colab, select Secrets (🔑) in the left pane and add your Kaggle username and Kaggle API key. Store your username under the name KAGGLE_USERNAME and your API key under the name KAGGLE_KEY.
