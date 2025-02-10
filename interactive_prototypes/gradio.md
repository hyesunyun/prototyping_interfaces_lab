# Gradio with HuggingFace

[Gradio](https://www.gradio.app/) is one of the fastest way to demo your machine learning model with a friendly web interface.

## Tutorial

**Tutorial Source**: https://www.kdnuggets.com/2023/06/build-ai-chatbot-5-minutes-hugging-face-gradio.html

Learn to create a Gradio chatbot using low code techniques directly in your browser with this easy-to-follow tutorial.
This short tutorial will build a simple chatbot using Hugging Face Space and Gradio interfaces.

1. Go to https://huggingface.co/ and create a free account.
2. Click on your display image on top right and select "New Space" option. HuggingFace Spaces are Git repositories, meaning that you can work on your Space incrementally (and collaboratively) by pushing commits. Take a look at the [Getting Started with Repositories](https://huggingface.co/docs/hub/en/repositories-getting-started) guide to learn about how you can create and edit files before continuing.
3. Fill out the form with App name, Licence, Space hardware, and visibility. Space name can be `AI-ChatBot`, License can be `apache-2.0`, Space SDK to be `Gradio`, Gradio template to be `chatbot`, and Space hardware to be `CPU basic 2 vCPU 16GB Free`
4. Press "Create Space" to initialize the application. 
5. You can clone the repository and push the files from your local system or create and edit files on Hugging Face using the browser. 
6. We will click on the "Files" tab > `app.py` 
7. You will see how the [Gradio](https://www.gradio.app/) app was created. You can change the model, add additional UI, the behavior of the chatbot, or even the theme. You can browse [Gradio Theme Gallery](https://huggingface.co/spaces/gradio/theme-gallery) to select the theme according to your taste. You can look at the source code to find different ways of creating interfaces.

## Resources

More details on how to use Gradio for creating interactive demo applications: https://www.gradio.app/

Gradio's Playground can be a great way to create interactive interfaces and be able to see a preview: https://www.gradio.app/playground