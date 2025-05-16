import streamlit as st

st.set_page_config(page_title="Surprise 💖", page_icon="💌", layout="centered")

st.title("Hey you 😊")
if st.button("Tap Me 💕"):
    st.markdown("<h2 style='color: #e75480;'>I love you &lt;3 💖</h2>", unsafe_allow_html=True)
