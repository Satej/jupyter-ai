# jupyter-ai
How to Set Up Jupyter AI Locally?

This guide outlines the steps to set up Jupyter AI locally and run the course notebooks on your machine.
Installing Jupyter AI

This course uses Jupyter AI v3 beta (3.0.0b7), as Jupyter AI v3 is not yet officially released. To install the beta version, run this command in your terminal:

pip install "jupyter-ai==3.0.0b7"

Once installation is complete, navigate to your working directory and launch JupyterLab by typing jupyter lab. You should now see the chat bubble in the left sidebar.

Note: 3.0.0b8 beta version was released after the course was filmed. Feel free to explore the newest version as it has enhanced UI.
Setting Up the Model Provider in JupyterLab

Before you can start interacting with Jupyter AI, you need to configure the model provider and API key (this step was already set up in this course):

    Click Settings in the top menu bar
    Select AI Settings from the drop-down menu (in the newest version, it is Jupyternaut Settings)
    Under Chat model, select your preferred model (this course uses openai/gpt-5-chat-latest) and click Update Chat Model
    Under Secrets and API keys, enter your API key

Accessing Course Notebooks

To download the notebook for each exercise, select the exercise item in the course menu, click File in the top menu bar in JupyterLab, and select Download from the drop-down menu. Alternatively, you can access all notebooks at this repo.

    You can find the dependencies in this requirements file.
    For the third notebook, you can get the Serper API key by signing up for a free account at serper.dev

Additional Features - AI Personas

In the course, you mainly interacted with Jupyternaut, the default AI Persona. In the current beta version, the AI persona does not come with any additional tools to read, edit, or search for files. These features are currently being developed and will make the default AI persona more powerful.

You can also create your own custom AI persona to tailor the assistant's behavior to your specific needs and equip it with the tools you want. You can read more about AI personas here.