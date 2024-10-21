---
layout: about
title: about
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info:

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---


#### About Me
---

Hi, I'm Zach! 

I am a CS PhD student at the University of California, Davis interested in machine learning and natural language processing. 

I earned my B.S. in computer science at the University of Vermont (home state). At UVM, I conducted applied machine learning research under the guidance of [Prof. Byung Lee](https://bslee.w3.uvm.edu/) and [Prof. Chris Skalka](https://ceskalka.w3.uvm.edu/). I worked on methods for modeling multivariate time-series data and making predictions about the environment that generated said data.

#### Research Interests
---

`Multimodal Learning`

My overarching goal is to enhance the capabilities of machine intelligences by helping them learn better internal world models. I believe the primary way to achieve this is by improving multimodal learning techniques, enabling models to learn about the world from as many useful modalities as possible. 

Why mutlimodal learning? Language alone is limited in the information it can convey about the world. For example, while textual descriptions can tell an AI about the concept of gravity or the texture of an object, they can't fully express the actual embodied experience and feeling of these phenomena. I am skeptical that an AI learning only from human language will be able to understand the world in the same way humans do - especially when it comes to concepts like intuitive physics, which can't easily be inferred from text. Most of a human's (and all of an animal's) internal world model is automatically formed through sensory experience, not through language.  

Currently, I am thinking about how to unify the representation of objects and concepts across different modalities. For example, when I experience the ocean: I hear the ocean, I smell the ocean, I see the ocean, I feel the ocean, and I sometimes (accidentally) taste the ocean. Each of these modalities of experience provides valuable data that helps me form a more complete understanding of what the ocean is and how it behaves, allowing me to reason about it and make accurate predictions about it. The challenge for AI, then, is how to replicate this ability to integrate multiple sensory modalities into a unified understanding of the world. How can we develop machine intelligences that don’t just rely on text or a single form of data, but instead learn from the full spectrum of available information?

`Memory`

I am also interested in studying the memory of large foundation models. Current LLMs store their knowledge in a fixed, distributed manner, which is hard for humans to interpret and manipulate. When we want to teach the LM new information it requires costly retraining. How can we decouple the knowledge that models have access to from their training data? How can we easily edit specific knowledge within them without overwriting unrelated knowledge or damaging other capabilities?  How we can easily integrate new knowledge without the need for retraining/finetuning? 

<!-- 
Write your biography here. Tell the world about yourself.  

Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->