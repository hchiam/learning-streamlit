# Learning [Streamlit](https://github.com/streamlit/streamlit)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

[Streamlit](https://github.com/streamlit/streamlit) lets you quickly run a Machine Learning web app built with pure Python.

## Quick minimal setup

```bash
pip install streamlit # you might need to use pip3
streamlit hello
```

## Basic example

```python
# mini_demo.py
import streamlit as st

x = st.slider('Select a value')
st.write(x, 'squared is', x * x)
```

```bash
pip install streamlit # you might need to use pip3
streamlit run mini_demo.py
```

## Bigger example (uses Machine Learning!)

<https://github.com/hchiam/python-ml-web-app>

## Deploy

<https://towardsdatascience.com/quickly-build-and-deploy-an-application-with-streamlit-988ca08c7e83>
