# Smile :)

Smile Classifier - The challenge is to create a classifier that can distinguish a smiling face.

## Setup 

Create an account at https://app.wandb.ai/login?invited if you don't have one.  Copy an api key from your [profile](https://app.wandb.ai/profile) and paste it after calling `wandb login` below.

In your AWS terminal run:

```
pip install -r requirements.txt --upgrade
wandb login
```

## Help

1. [Slack Channel](https://join.slack.com/t/doloreslabs/shared_invite/enQtMzExNjMzMDcwMzM4LTk4YTFjN2I0YWJkNTU5OGQ1YTI5NDU5ODU2MzUyYjVjM2Y0OTIyZDgwMmNiY2U3N2ZjNmQzOThmMzkwNjA0ODQ)
2. [Keras Docs](https://keras.io/getting-started/sequential-model-guide/)
3. [Previous Work](https://github.com/oarriaga/face_classification)

## Files

- smile.py - scaffolding to get you started
- smiledataset.py - loads the data
- master.zip - the face dataset, smiles are in the positive directory the rest are in the negative directory
