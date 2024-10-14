# AI @ Dartmouth for Research Use: Advanced Applications and Customization

Take your research to the next level with AI.Dartmouth.edu by exploring advanced AI applications tailored for those who integrate AI tools into existing systems or create entirely new ones. This session will guide you through the process of using AI.Dartmouth.edu’s APIs and Python libraries, including the LangChain framework and its Dartmouth-specific extension, empowering you to enhance your projects with innovative AI capabilities.

Whether you’re interested in embedding AI into your current workflows or developing customized AI models and tools, this workshop offers the resources and tutorials you need to maximize the potential of generative AI. Learn how to build and deploy innovative AI-driven solutions using the platform's extensive resources.

Ideal for researchers and innovators, this session will equip you to explore what’s possible with AI at Dartmouth.


## Contents

This repository contains all the materials for the workshop session, consisting of a slide deck in the directory `ppt`, and a collection of Jupyter notebooks with code demos in (`notebooks`)

## Getting Started
### Requirements

Some basic Python programming knowledge is required to fully understand the example code. Consider working through [Intro to Python](https://github.com/Dartmouth-Libraries/Intro-to-Python) and [Let there be Data! APIs in Python](https://github.com/Dartmouth-Libraries/apis-in-python) prior to this workshop.

The requirements for the Python code can be installed using the following command:

```
pip install -r requirements.txt
```

### API Access

The code in the example notebooks requires a valid Dartmouth API key. Some examples also require an OpenAI API key.

You can acquire these keys from the [Dartmouth Developer Portal](https://developer.dartmouth.edu) and the [OpenAI website](https://platform.openai.com/), respectively.

To use your keys in the code, follow these steps:

1. Create a text file called `.env` in the root directory of this repository.
2. Add the following lines to `.env`, replacing 'YOUR_KEY' with your actual key:
   ```
   DARTMOUTH_API_KEY="YOUR_KEY"
   OPENAI_API_KEY="YOUR_KEY"
   ```
3. Save and close `.env`.

That's it - your keys are set up for use in the example notebooks.


## Issues and feedback

If you run into any trouble working with these materials, have some questions about the content, or want to give general feedback, feel free to go through one of these channels to get in touch with us:

- [Open a new issue](https://github.com/Dartmouth-Libraries/ai-project-showcase/issues)
- [Send an email](mailto:simon.stone@dartmouth.edu)
- [Book an appointment](https://dartgo.org/meetwithsimon) (Dartmouth-members only)

## Licensing

<table>
<tbody>
  <tr>
    <td style="padding:0px;border-width:0px;vertical-align:center">
    Instructional materials created by Simon Stone for Dartmouth Libraries under <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons CC BY-NC 4.0 License</a>.
    </td>
    <td style="padding:0 0 0 1em;border-width:0px;vertical-align:center"><img alt="Creative Commons License" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></td>
  </tr>
</tbody>
</table>