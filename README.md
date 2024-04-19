# DAT255 Summarization

Welcome to our DAT255 course project! Visit our blog at http://www.norakristiansen.no/dat255-summarization/

The blog contains information about our project and research, with notebook like blogposts for each type of summarization explored.

This blog is made using Quarto, a publishing system that allows us to write blog posts in a Jupyter Notebook-like format.

### Setup and local rendering

- Follow the [Quarto Get Started guide](https://quarto.org/docs/get-started/) to install the Quarto CLI and set up Quarto in your favorite tool.

- Create a file called _environment.local in the root of the project, and add your OpenAI API key in a OPENAI_API_KEY field, like this:

```OPENAI_API_KEY=<your-key-here>```

- Run ```pip install -r req.txt```in the root of the project to install all required packages.

- The blog posts may be previewed locally by executing the preview command in your tool of choice, or by running the command below:

```quarto preview path/to/blogpost.qmd --no-browser --no-watch-inputs```