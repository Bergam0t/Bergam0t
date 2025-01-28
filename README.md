### Hi there - I'm Sammi! 🚵 🏸 🎷 👩‍💻

I'm currently a trainer on the [Health Service Modelling Associates Programme](https://hsma.co.uk).

I was previously a data analyst, and later data scientist, in a mental health trust in the NHS. 

I completed my BA in Biological Sciences at the University of Oxford in 2011-14, and my MSc in Health Data Science at the University of Exeter in 2020-21, with a focus on web app development for healthcare service improvement.

I'm currently working on
- animated outputs for discrete event simulation event logs
- user-friendly visualisation of large graph networks in Streamlit (including adding extra features to the excellent [st-cytoscape extension](https://github.com/Bergam0t/st-cytoscape-extra))
- open-source teaching materials on
  - python for beginners
    - [book](https://hsma-programme.github.io/hsma6_intro_to_python_book/)
    - [course proof of concept](https://bergam0t.github.io/intro_to_python_course_proof_of_concept/)
  - discrete event simulation for healthcare pathway simulation
    - [book](https://hsma-programme.github.io/hsma6_des_book/)
    - [interactive playground](https://hsma-programme.github.io/Teaching_DES_Concepts_Streamlit/)
  - [geographical visualisation, travel time lookups and service location optimisation](https://hsma-programme.github.io/hsma6_geographic_optimisation_and_visualisation_book/intro.html)
  - machine learning, including
    - [decision trees and random forests](https://github.com/hsma-programme/h6_4d_decision_trees_random_forests)
    - [gradient boosting methods - XGBoost, Catboost, LightGBM](https://github.com/hsma-programme/h6_4e_boosted_trees)
    - [explainable AI - SHAP; ICE and PDP plots](https://github.com/hsma-programme/h6_4g_explainable_ai)
    - [reinforcement learning](https://github.com/Bergam0t/ReinforcementLearningGame)
  - beginner statistics (coming soon!)
  - web app development with Streamlit
      - [book](https://bergam0t.github.io/streamlit_book/)
      - [session 1 - introduction to Streamlit; displaying dataframes, charts and maps; getting user input; laying out apps with tabs, columns and expanders](https://github.com/hsma-programme/h6_7b_web_apps_1)
      - [session 2 - discrete event simulation apps, multipage apps, theming, run buttons, caching, partial reruns, session state, deployment](https://github.com/hsma-programme/h6_7c_web_apps_2)
  - [reproducible outputs with Quarto](https://hsma.co.uk/hsma_content/modules/current_module_details/8_modern_analytics.html)
  - and more...   

My current favourite things to work with are
- [Streamlit](https://streamlit.io/) (particularly serverless deployment with the amazing [stlite](https://github.com/whitphx/stlite) package)
- [Quarto](https://quarto.org/) and the fantastic [webexercises](https://github.com/Bergam0t/webexercises) and [quarto-pyodide](https://github.com/coatless-quarto/pyodide) extensions for adding interactivity to Quarto ebooks
- [Godot](https://godotengine.org/) 

I'd love to chat about
- how to use routinely collected data better to improve mental healthcare services
- how to make it easier for analysts and data scientists to securely deploy custom web apps in their organisations
- improving data literacy in the NHS and helping stakeholders understand the amazing potential of R, Python, advanced analytics, operational research and data science
- how to teach coding, data science and operational research effectively

Here are a couple of the things I've created:

## Animated event logs for discrete event simulation
*This video intermittently fails to load - try refreshing the page if it's showing an error!*

https://github.com/hsma-programme/Teaching_DES_Concepts_Streamlit/assets/29951987/1adc36a0-7bc0-4808-8d71-2d253a855b31

Play around with a live demo of this [here](https://playground.hsma.co.uk) - note that it won't load in Firefox!

This work has been released as the [vidigi package](https://bergam0t.github.io/vidigi/vidigi_docs/) to allow people to visualise their own systems.

Further example visualisations can be found in [this web app](https://simpy-visualisation.streamlit.app/), with the code available in [this repository](https://github.com/hsma-programme/simpy_visualisation/tree/main/examples).

## Ebook: Simpy for healthcare modelling

Co-authored with Dr Daniel Chalk (modifying and building on materials from the HSMA programme), this ebook takes users from being complete beginners in discrete event simulation through to being able to create complex simulation models with the simpy package.

You can read the ebook [here](https://hsma-programme.github.io/hsma6_des_book/).

## Ebook: Python for beginners

Co-authored with Dr Daniel Chalk (modifying and building on materials from the HSMA programme), this ebook takes users from being complete beginners in Python through to being able to use many of the key features of the language.

You can read the ebook [here](https://hsma-programme.github.io/hsma6_intro_to_python_book/).

## Ebook: Geographic Visualization and Optimization

This HSMA book complements the geographic module on the programme, covering visualisation of geographic data in QGIS (with thanks to Dr Kerry Pearn) and Python. In Python, we look at both static and interactive maps. The book then goes on to retrieving travel times from APIs and calculating the optimal position of sites based on demand or population figures. 

In future, the book will be expanded to cover additional topics including multiobjective optimization and geospatial statistics (hotspots, coldspots, spatial outliers). 

You can read the ebook [here](https://hsma-programme.github.io/hsma6_geographic_optimisation_and_visualisation_book/intro.html).

## Ebook: Web Apps with Streamlit

This HSMA book helps with turning your code into an interactive tool, with a special focus on building front ends for discrete event simulation models.

You can read the ebook [here](https://webapps.hsma.co.uk).

## Health and Social Care Service Use Timelines (Theographs/Pearn Charts) for PowerBI
[This custom PowerBI visual](https://github.com/Bergam0t/community_service_timelines) takes a simple, routinely collected dataset of patient history and displays it in a clear format. 

Long-term referrals as well as individual interactions with services can be shown, with customisable tooltips, allowing clinicians to get an overview of a patient's history in a quick glance and spot repeated patterns of service interaction. Designed initially for use in mental health services, where clients can have more than a decade of data, thousands of contacts, and systems which display these details as rows of text rather than in a way that allows easy interpretation.

![image](https://github.com/Bergam0t/Bergam0t/assets/29951987/d8434477-7ea3-4043-93b8-7bb8ab5d98c7)

A [second visual](https://github.com/Bergam0t/inpatient_timelines) is designed specifically for non-overlapping data.

![image](https://github.com/Bergam0t/Bergam0t/assets/29951987/7623cde5-cc5c-4572-a856-db0c569ce94e)


## SPC charts for PowerBI (based on code from the NHSRPlotTheDots project)
[This custom PowerBI visual](https://github.com/Bergam0t/nhs_ptd_power_bi) allows SPC charts to be created within PowerBI that automatically adhere to the making data count guidance. 

![image](https://github.com/Bergam0t/Bergam0t/assets/29951987/9400203f-927c-471e-b56c-179576ae931a)

Extensive customisation is available through built-in menus. 
Multiple output types are possible, including faceted graphs, metric cards, and several summary tables.
