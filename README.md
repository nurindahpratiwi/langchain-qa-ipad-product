# Question-Answering with NotionDB based on LangChain

🤖Ask questions to iPad product in natural language based on NotionDB🤖

💪 Built with [LangChain](https://github.com/hwchase17/langchain)

# 🌲 Environment Setup

In order to set your environment up to run the code here, first install all requirements:

```shell
pip install -r requirements.txt
```

Then set your OpenAI API key. OpenAI API should work only if you set your paid payment methods.

```shell
export OPENAI_API_KEY=....
```

# 📄 What is in here?
- Example data from iPad Technical Specification
- Python script to query Notion with a question
- Code to deploy on StreamLit
- Instructions for ingesting your own dataset

## 📊 Example Data
This repo uses the [iPad Technical Specification Product](https://www.notion.so/nurindahpratiwi/iPad-8d1d01c0935b48cfae4971470303b5be?pvs=4) created on May, 08 2023/

## 💬 Ask a question
In order to ask a question, run a command like:

```shell
python qa.py `What is iPad?`
```

You can switch out `What is iPad?` for any question of your like, such as `What is the lates iPad version?`

## 🚀 Code to deploy on StreamLit

The code to run the StreamLit app is in `main.py`. 
