# Streamlit with HuggingFace

[Streamlit](https://streamlit.io/) is an open-source python framework that can help us to build, deploy, and share our dashboard or web app for free.
You don't need any front-end experience.

Streamlit offers a free Community Cloud platform to deploy your web app. However, you can also connect with HuggingFace's ecosystem to deploy your app.

## Hot Dog Classifier

**Tutorial Source**: https://huggingface.co/docs/hub/en/spaces-sdks-streamlit

In the following sections, you’ll learn the basics of creating a Space, configuring it, and deploying your code to it. We’ll create a **Hot Dog Classifier Space** with Streamlit that'll be used to demo the `julien-c/hotdog-not-hotdog` model, which can detect whether a given picture contains a hot dog :hotdog:

1. Go to https://huggingface.co/ and create a free account.
2. Click on your display image on top right and select "New Space" option. HuggingFace Spaces are Git repositories, meaning that you can work on your Space incrementally (and collaboratively) by pushing commits. Take a look at the [Getting Started with Repositories](https://huggingface.co/docs/hub/en/repositories-getting-started) guide to learn about how you can create and edit files before continuing.
3. Fill out the form with App name, Licence, Space hardware, and visibility. Space name can be `Hot Dog Classifier`, License can be `apache-2.0`, Space SDK to be `Streamlit`, and Space hardware to be `CPU basic 2 vCPU 16GB Free`
4. Add the dependencies. For the Hot Dog Classifier we’ll be using Transformers pipeline to use the model, so we need to start by installing a few dependencies. This can be done by creating a `requirements.txt` file in our repository, and adding the following dependencies to it: transformers and torch
5. To create the Streamlit app, make a new file in the repository called `app.py` and add the code from `streamlit_app.py`
6. This Python script uses Transformers pipeline to load the `julien-c/hotdog-not-hotdog` model, which is used by the Streamlit interface. The Streamlit app will expect you to upload an image, which it'll then classify as hot dog or not hot dog. Once you’ve saved the code to the `app.py` file, visit the "App" tab to see your app in action!

## Resources

Streamlit has many different pre-built components you can use: https://streamlit.io/components