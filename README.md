<p align="center">
<a href=https://github.com/sohomx/LCEL target="_blank">
<img src='/placeholder.jpg' width="100%" alt="Banner" />
</a>
</p>



<p align="center">
<img src="https://img.shields.io/github/contributors/sohomx/LCEL" alt="GitHub contributors" />
<img src="https://img.shields.io/github/discussions/sohomx/LCEL" alt="GitHub discussions" />
<img src="https://img.shields.io/github/issues/sohomx/LCEL" alt="GitHub issues" />
<img src="https://img.shields.io/github/issues-pr/sohomx/LCEL" alt="GitHub pull request" />
</p>

<p></p>
<p></p>

## 🔍 Table of Contents

* [💻 Stack](#stack)

* [📝 Project Summary](#project-summary)

* [⚙️ Setting Up](#setting-up)

* [🚀 Run Locally](#run-locally)

* [🙌 Contributors](#contributors)

* [📄 License](#license)

## 💻 Stack

Include a concise explanation about the Tech Stack employed.

## 📝 Project Summary

## ⚙️ Setting Up

#### Your Environment Variable

- Step 1

- Step 2

## 🚀 Run Locally
1.Clone the LCEL repository:
```sh
git clone https://github.com/sohomx/LCEL
```
2.Install the dependencies with one of the package managers listed below:
```bash
pip install -r requirements.txt
```
3.Start the development mode:
```bash
python app.py
```

## 🙌 Contributors

<table style="border:1px solid #404040;text-align:center;width:100%">
<tr><td style="width:14.29%;border:1px solid #404040;">
        <a href="https://github.com/sohomx" spellcheck="false">
          <img src="https://avatars.githubusercontent.com/u/84140043?v=4?s=100" width="100px;" alt="sohomx"/>
          <br />
          <b>sohomx</b>
        </a>
        <br />
        <a href="https://github.com/sohomx/LCEL/commits?author=sohomx" title="Contributions" spellcheck="false">
          11 contributions
        </a>
      </td></table>

## 📄 License

[**Add Your License**](https://choosealicense.com)



------------

# LCEL
intro to langchain expression langchain

# LangChain components and the Runnable Protocol

Standard Interface
1. stream: stream back chunks of response
2. invoke: invoke chain with an input
3. batch: invoke chain with a list of input

---------

Input Types

1. Prompt: dictionary
2. Retriever: Single String
3. LLM, ChatModel: Single String, message list or PromptValue
4. Tool: single string and dictionary (which tool you are using)
5. OutputParser: depends on the parser

-------------

Output Types
1. LLM: string
2. Retriever: List of Documents
3. ChatModel: Chat Message
4. Prompt: PromptValue
5. OutputParser: depends on the parser
6. Tool: Depends on the tool
   
