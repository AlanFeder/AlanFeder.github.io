---
layout: page
title: Data Science Presentations & Publications
---

## Table of Contents

- [Presentations](#presentations)
  - [The Good, the Bad, and the Shiny: A Guide to Choosing Python Web App Frameworks](#dcr-2024)
  - [RAGtime in the Big Apple: Chat with a Decade of NYR Talks](#nyr-rag)
  - [RAGs to Riches: Using ChatGPT to Query Documents & Limit Hallucinations](#ragbethesda)
  - [NLP in Finance](#dssalon1)
  - [Categorical Embeddings](#rstudio)
  - [Machine Learning Interpretability](#dssalon2)
- [Publications](#publications)
  - [Stocks move on surprises](#riskreward)
  - [Q&A With Alan Feder](#blog1)


# Presentations

<!-- <div class="container">
	<div class="column" id="left"> -->
<a id="dcr-2024"></a>
<!-- <p><b><a href="https://www.youtube.com/watch?v=hFU60JpFKI0&ab_channel=LanderAnalytics">RAGtime in the Big Apple: Chat with a Decade of NYR Talks </a></b>, New York R Conference, May 2024</p> -->
<p><b>The Good, the Bad, and the Shiny: A Guide to Choosing Python Web App Frameworks </b>, Government & Public Sector R Conference, October 2024</p>

<div style="text-align:center;">
<!-- <iframe src="https://www.youtube-nocookie.com/embed/hFU60JpFKI0" title="YouTube video player" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen ></iframe> --> 


<div style="text-align: center;">
    <a href="https://www.alanfeder.com/dcr_rag" target="_blank">
        <iframe src="https://www.alanfeder.com/dcr_rag" frameborder="0" style="width: 65%; height: 450px; display: inline-block;" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    </a>
</div>

</div>
**Demo Apps**: [Streamlit](https://www.alanfeder.com/dcr_rag/streamlit_lite.html), [Shiny](https://www.alanfeder.com/dcr_rag/shinylive1/), [HTML](https://www.alanfeder.com/dcr_rag/html_app.html)  
<small>Shiny has long been the go-to for data scientists creating web applications in R, but Python offers a plethora of alternatives that can be overwhelming to choose from. This talk will demonstrate the creation of a single application using three popular Python tools: PyShiny, Streamlit, and Gradio. We'll explore the strengths and weaknesses of each framework, through a live demonstration of each. This comparison will provide you with a practical roadmap for selecting the ideal Python web app framework to suit your specific data science projects.</small>   


***

<!-- <div class="container">
	<div class="column" id="left"> -->
<a id="nyr-rag"></a>
<p><b><a href="https://www.youtube.com/watch?v=hFU60JpFKI0&ab_channel=LanderAnalytics">RAGtime in the Big Apple: Chat with a Decade of NYR Talks </a></b>, New York R Conference, May 2024</p>

<div style="text-align:center;">
<iframe src="https://www.youtube-nocookie.com/embed/hFU60JpFKI0" title="YouTube video player" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen ></iframe>

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTGCRGiDwfh3xvqbwU-Y939LOPUyXUSIQnBozF81e_uj6hRCq2k-rGaHfb035HczG6UDzXNydlH7b5B/embed?start=false&loop=false&delayms=3000" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>
**Demo App**: [Chat With a Decade of Previous NYR Talks](https://nyr.alanfeder.com/) <small>*Can be used even without OpenAI API Key*</small>    
<small>As the adoption of Large Language Models (LLMs) like ChatGPT has increased over the past year, there's been a growing excitement about using these technologies to query existing documents and datasets. However, training your own LLM chatbot from scratch is impossible for everyone except the largest tech companies. Retrieval-Augmented Generation (RAG) is a versatile method for addressing these challenges. I will show how this works with a live demo exploring the past 10 years of NYR talks.</small>   

<small>Intro music by <a href="https://www.udio.com/songs/e9YZScxFKB36PCz2yJu8EF">Udio</a></small>

***
<!-- <div class="container">
	<div class="column" id="left"> -->
<a id="ragbethesda"></a>
<p><b><a href="https://www.youtube.com/watch?v=0i_7Cn31VrU">RAGs to Richer Answers: Using ChatGPT to Query Documents & Limit Hallucinations</a></b>, Bethesda Data Science Meetup, November 2023</p>

<div style="text-align:center;">
<iframe src="https://www.youtube-nocookie.com/embed/0i_7Cn31VrU" title="YouTube video player" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen ></iframe>

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTwQ6qAwszS9-6W9ZyC7YqCoDPHTRsdUsGQyxn9CZuy9clIXVJra7oT6JiDZeUFZohdyMIr25pCU_Ft/embed?start=false&loop=false&delayms=3000" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>
**Demo App**: [Ask Questions of Previous Bethesda Data Science Speakers with ChatGPT!](https://rag-bethesda-ds.alanfeder.com/) <small>*Note: You need to input an OpenAI API Key to use it*</small>    
<small>As the adoption of Large Language Models (LLMs) like ChatGPT has increased over the past year, there's been a growing interest in using these technologies to query existing documents and datasets. However, a notable challenge with ChatGPT is its tendency to hallucinate (aka "make stuff up"), leading to reliability issues. Furthermore, developing a custom chatbot is impossible for everyone except the largest tech companies. This has brought Retrieval-Augmented Generation (RAG) to the forefront as a solution to these issues. In this presentation, I provide an overview of RAG, explain how it operates, and discuss the essentials for creating your own RAG system.</small>   

***

<!-- <div class="container">
	<div class="column" id="left"> -->
<a id="dssalon1"></a>
<p><b><a href="https://www.youtube.com/watch?v=LoivGTvydBo">NLP in Finance: Beyond Predicting Alpha</a></b>, Data Science Salon, February 2022</p>
<div style="text-align:center;">
<iframe src="https://www.youtube-nocookie.com/embed/LoivGTvydBo" title="YouTube video player" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen ></iframe>
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQOL0_rqLuH0jR_4MlE68KeglAxn0ka0gkzFIEUHs88PF9R85D10bLPOBjwyzDLIGDL6PCsjplwh0a3/embed?start=false&loop=false&delayms=3000" frameborder="0" style="width: 45%; height: 315px; display: inline-block;" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>
<small>As NLP has exploded within the world of Data Science and Machine Learning, it is now everywhere in finance as well. Many of us have heard about using NLP to try to outperform the market and predict stock prices. However, NLP is much more versatile than that, and has many other uses as well throughout the finance world. In this talk, I explore a number of methodologies within NLP, explaining how they are being used in finance to help professionals do their job more efficiently and effectively.</small>   

***
<!-- </div>
<div class="column" id="right">-->
<a id="rstudio"></a>
<p><b><a href="https://posit.co/resources/videos/categorical-embeddings-new-ways-to-simplify-complex-data/">Categorical Embeddings: New Ways to Simplify Complex Data</a></b>, rstudio::global(2021), January 2021</p>
<iframe src="https://fast.wistia.net/embed/iframe/6kt8p3tpuq" width="560" height="315" style="display: block; margin-left: auto; margin-right: auto" frameborder="0" allowfullscreen></iframe>
<p>Categorical embeddings are a relatively new method, utilizing methods popularized in Natural Language Processing that help models solve this problem and can help you understand more about the categories themselves.</p>
<small>When building a predictive model in R, many of the functions (such as `lm()`, `glm()`, `randomForest`, `xgboost`, or neural networks in `keras`) require that all input variables are numeric. If your data has categorical variables, you may have to choose between ignoring some of your data and too many new columns.</small>

<small>Categorical embeddings are a relatively new method, utilizing methods popularized in Natural Language Processing that help models solve this problem and can help you understand more about the categories themselves.</small>

<small>While there are a number of online tutorials on how to use Keras (usually in Python) to create these embeddings, this talk uses <a href="https://embed.tidymodels.org/reference/step_embed.html">`embed::step_embed()`</a>, an extension of the `recipes` package, to create the embeddings.</small>

***
<a id="dssalon2"></a>
<p><b><a href="https://www.youtube.com/watch?v=CfCHI8d8oYg">Machine Learning Interpretability: How to Understand what your ML Model is Doing</a></b>, Data Science Salon, January 2021</p>
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/CfCHI8d8oYg" title="YouTube video player" frameborder="0" style="display: block; margin-left: auto; margin-right: auto" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<small>When building predictive machine learning models, many data scientists feel a need to choose between a traditional regression model and a complex model that performs better but is more of an inscrutable black box.  In this talk, I will show a number of methods that let us understand what drives the complex models without having to sacrifice accuracy.</small>

<!--</div>
</div> -->
# Publications
<a id="riskreward"></a>
<p><b><a href="https://www.invesco.com/content/dam/invesco/emea/en/pdf/Risk_and_Reward_Q3_2022.pdf#page=21">
Stocks move on surprises: Using sentiment information for active portfolio management</a></b>, Risk & Reward, vol. Q3 2022, Invesco, 14 Oct. 2022, pp. 21-25</p>

***
<a id="blog1"></a>
<p><b><a href="https://www.mattstabile.com/blog/qampa-with-alan-feder-5-questions-for-a-data-scientist">
Q&A With Alan Feder // 5 Questions for a Data Scientist</a></b>, Matt Stabile Blog, January 8, 2021</p>
