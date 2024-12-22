---
title: Using TensorFlow and Dev Containers in Visual Studio Code for Neural Network Development
description: Learn how to set up and use TensorFlow with Visual Studio Code Dev Containers for efficient neural network development. This guide covers configuring a GPU-accelerated environment, integrating Jupyter notebooks, and optimizing your workflow for machine learning projects.
author: juanmcristobal
date: 2024-12-19 20:30:00 +0800
categories: [Development Environment, Visual Studio Code]
tags: [Machine Learning, TensorFlow, Neural Networks, Visual Studio Code, Dev Containers, Docker, GPU Acceleration, Jupyter Notebooks, Python, Artificial Intelligence, Deep Learning, Development Environment, VS Code Extensions, Data Science, Software Engineering]
pin: true
math: true
mermaid: true
image:
  path: /assets/img/2024-12-19/dev-containers.png
---


Those of us who have spent years in the world of programming are all too familiar with the infamous phrase: *"It works on my machine."* Thankfully, tools like [DevContainer](../../tags/dev-containers/) address this issue by providing fully configured, ready-to-use development environments.

Recently, I’ve revisited my studies in Machine Learning and Artificial Intelligence, and with my new laptop, I’ve decided to set up an optimized environment to apply everything I’m learning in this exciting field.

The idea is simple: create a template based on a well-structured Git repository and start working immediately. With this approach, all dependencies, configurations, and tools are pre-installed and ready to go. You no longer need to worry about mismatched Python versions, missing libraries, or broken dependencies.

This setup isn't just convenient; it's also scalable. Whether you're working solo on a personal project or collaborating with a team, everyone will have the same environment, reducing the classic "it works on my machine" headaches.

Stay tuned as I'll share more details about my projects, lessons learned, and some tips to make the most out of this setup. If you're curious, check out the video and let me know your thoughts!

## Steps for Installation

- ![template](/assets/img/2024-12-19/use_github_template.png){: .right } Go to [https://github.com/juanmcristobal/tensorflow-gpu-devcontainer](https://github.com/juanmcristobal/tensorflow-gpu-devcontainer) and click on Use this template to create your own repository based on it. 


- Clone the Repository
Once your repository is ready, open your terminal and run:

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

- Open in VSCode
Launch VS Code and open the cloned repository. If you have the DevContainer extension installed, it should automatically prompt you to **reopen in container**.

![template](/assets/img/2024-12-19/reopen.png)

- Reopen in Container
  
Click on Reopen in Container when prompted by VS Code. This will build the development environment based on the provided configuration.

![template](/assets/img/2024-12-19/terminal.png)

- Launch Jupyter Notebook
Run the following command to start Jupyter Notebook:

```bash
jupyter notebook
```

- Verify the Environment
  
Once the container is set up and all dependencies are successfully installed, open **test_devcontainer.ipynb** and run the notebook to verify its functionality.

![template](/assets/img/2024-12-19/jupyter.png)

- Start Experimenting!
Open your browser and navigate to the Jupyter Notebook interface to start coding.



To make things even easier, I've included a video walkthrough illustrating the setup process step-by-step. In the video, I demonstrate how to clone the repository, open it in a DevContainer-supported IDE (like VS Code), and start working with TensorFlow and Jupyter Notebook right away.

{% include embed/youtube.html id='u2L-y6wXQh0' %}
