---

layout: post
category: product
title: "Import AI 229: Apple builds a Hypersim dataset; ways to attack ML; Google censors its research"
date: 2020-12-28 17:16:32
link: https://vrhk.co/3pyAge7
image: 
domain: jack-clark.net
author: "Jack Clark"
icon: https://s2.wp.com/i/webclip.png
excerpt: "Apple builds Hypersim, a dataset to help it understand your house:&hellip;High-resolution synthetic scenes = fuel for machine learning algorithms&hellip;Apple has built Hypersim, a dataset of high-resolution synthetic scenes with per-pixel labels. Hypersim consists of 77,400 images spread across 461 distinct indoor scenes; Apple bought the synthetic scenes from artists, then built a rendering pipeline to help it generate lots of detailed, thoroughly labeled images of the different scenes, including per-pixel data to help with tasks like segmentation.



How much does a dataset like this cost? The authors put the cost of this dataset in perspective by comparing it to the cost to train Megatron-LM, an 8 billion parameter model from NVIDIA.&ndash; Hypersim dataset:$57k &ndash; $6k for purchasing the scenes, and $51k to render the images, using 231 vCPU years (2.4 years of wall-clock time on a large compute node).&ndash; Megatron-LM:$103k using publicly available servers.



Why this is useful: Datasets like this &ldquo;could enable progress on a wide range of computer vision problems where obtaining realworld ground truth is difficult or impossible,&rdquo; Apple writes. &ldquo;In particular, our dataset is well-suited for geometric learning problems that require 3D supervision, multi-task learning problems, and inverse rendering problems&rdquo;.Read more: Hypersim: A Photorealistic Synthetic Dataset for Holistic Indoor Scene Understanding (arXiv).Get the code to generate the dataset:ML Hypersim Dataset (Apple, GitHub).Via David Ha (Twitter).###################################################



MIRI&rsquo;s had some negative research results (and that&rsquo;s okay):&hellip;AI safety group gives research update&hellip;MIRI, an AI safety research organization, has spent a few years working on some research that hasn&rsquo;t worked well, according to the organization. In a 2020 update post, the group said &ldquo;2020 saw limited progress in the research MIRI&rsquo;s leadership had previously been most excited about&rdquo;. As a consequence, &ldquo;MIRI&rsquo;s research leadership is shifting much of their focus towards searching for more promising paths&rdquo;. The company said it projects to have spent around $7 million in 2020, and estimates around $7 million again in 2021.



Why this matters: MIRI decided in 2018 that its future research results would be &ldquo;nondisclosed-by-default&rdquo; (Import AI 122). That&rsquo;s a decision that inspired some strong feelings among advocates for open publication, but I think it&rsquo;s a credit to the organization to update the world that some of these opaque research projects haven&rsquo;t panned out. A signal is better than no signal at all, and I&rsquo;m excited to see MIRI continue to experiment in different forms of high-impact research disclosure (and non-disclosure). Plus, we should always celebrate organizations owning their own &lsquo;negative results&rsquo; &ndash; though perhaps now MIRI thinks these approaches won&rsquo;t work, it could publish them and save other researchers the trouble of replicating blind-alley projects.&nbsp; &nbsp; Read more: 2020 Updates and Strategy (MIRI blog).



###################################################



Google&rsquo;s PR, policy, and legal teams censor its research:&hellip;Suspicious about the oh-so-positive narratives in corporate papers? You should be!&hellip;Google&rsquo;s PR, policy, and legal teams have been editing AI research papers to give them a more positive slant, reduce focus on Google&rsquo;s products, and generally minimize discussion of the potential drawbacks of technology, according to reporting from Reuters.



The news of the censorship operation follows Google firing Timnit Gebru, after Google staff wanted to step in and heavily alter and/or remove Google-affiliated authors from a research paper discussing some of the issues inherent to large language models like BERT, GPT3, and so on. Now, according to Reuters, it seems Google has been censoring a many papers for many months.



What censorship looks like: &ldquo;The Google paper for which authors were told to strike a positive tone discusses recommendation AI, which services like YouTube employ to personalize users&rsquo; content feeds. A draft reviewed by Reuters included &ldquo;concerns&rdquo; that this technology can promote &ldquo;disinformation, discriminatory or otherwise unfair results&rdquo; and &ldquo;insufficient diversity of content,&rdquo; as well as lead to &ldquo;political polarization.&rdquo;,&rdquo; Reuters writes. &ldquo;The final publication instead says the systems can promote &ldquo;accurate information, fairness, and diversity of content.&rdquo; The published version, entitled &ldquo;What are you optimizing for? Aligning Recommender Systems with Human Values,&rdquo; omitted credit to Google researchers. Reuters could not determine why.&rdquo;



Why this matters: People aren&rsquo;t stupid. Let me repeat that: PEOPLE AREN&rsquo;T STUPID. Most corporations seem to think AI is some kind of impossibly obscure technology that normies don&rsquo;t deserve to know about, so they feel like they can censor research to their own gain. But, as I have said, PEOPLE ARE NOT STUPID. People use AI systems every day &ndash; so people know AI systems have problems. This kind of attitude from Google is absurd, patronizing, and ultimately corrosive to civilisation-level scientific progress. I spoke about issues relating to this in December 2018 in a podcast with Azeem Azhar, where I compared this approach to science to how Christian priests in the dark ages kept knowledge inside monasteries, thinking it too dangerous for the peasants. (Things didn&rsquo;t work out super well for the priests). It&rsquo;s also just a huge waste of the time of the researchers being censored by their corporation. Don&rsquo;t waste people&rsquo;s time! We all only have a finite amount of it.&nbsp;Read more: Google told its scientists to &lsquo;strike a positive tone&rsquo; in AI research &ndash; documents (Reuters).



###################################################



How can I mess up your ML model? Let me count the ways:&hellip;Feature Collisions! Label Poisoning! Influence Functions! And more&hellip;How do people attack the datasets used to train machine learning models, what can these attacks do, and how can we defend against them? That&rsquo;s the subject of a survey paper from researchers with the University of Maryland, MIT, the University of Illinois Urbana-Champaign, and the University of California, Berkeley.



Attacking datasets: The paper summarizes the range of techniques people might use to attack datasets, giving a guided tour of horrors like poisoning the input data to cause a misclassification, or perturbing the outputs of already trained models (for instance, by giving them an input that they can&rsquo;t classify, or which leads to pathological behavior).



Defending against attacks: Fear not! There are some ways to defend or mitigate these attacks, including federated learning, the use of privacy preserving machine learning approaches like differential privacy, and learning to detect adversarial triggers, among others.



Why this matters: AI systems are so complicated that their capability surface, especially for recent large-scale models, are vast and hard to characterize. This is basically catnip for security-minded people that want to mess with these systems &ndash; a vast, somewhat uncharacterized territory is the perfect place to unleash some mischief. But if we don&rsquo;t figure out how to secure these models, it&rsquo;ll be much harder to deploy them broadly into the world.Read more: Data Security for Machine Learning: Data Poisoning, Backdoor Attacks, and Defenses (arXiv).



###################################################Tech Tales:



Plato, give me your favorite recipe[California, 2040. Simulated ancient Greece.]



Plato was talking to a bunch of Greeks. He was exp…"

---

### Import AI 229: Apple builds a Hypersim dataset; ways to attack ML; Google censors its research

Apple builds Hypersim, a dataset to help it understand your house:&hellip;High-resolution synthetic scenes = fuel for machine learning algorithms&hellip;Apple has built Hypersim, a dataset of high-resolution synthetic scenes with per-pixel labels. Hypersim consists of 77,400 images spread across 461 distinct indoor scenes; Apple bought the synthetic scenes from artists, then built a rendering pipeline to help it generate lots of detailed, thoroughly labeled images of the different scenes, including per-pixel data to help with tasks like segmentation.



How much does a dataset like this cost? The authors put the cost of this dataset in perspective by comparing it to the cost to train Megatron-LM, an 8 billion parameter model from NVIDIA.&ndash; Hypersim dataset:$57k &ndash; $6k for purchasing the scenes, and $51k to render the images, using 231 vCPU years (2.4 years of wall-clock time on a large compute node).&ndash; Megatron-LM:$103k using publicly available servers.



Why this is useful: Datasets like this &ldquo;could enable progress on a wide range of computer vision problems where obtaining realworld ground truth is difficult or impossible,&rdquo; Apple writes. &ldquo;In particular, our dataset is well-suited for geometric learning problems that require 3D supervision, multi-task learning problems, and inverse rendering problems&rdquo;.Read more: Hypersim: A Photorealistic Synthetic Dataset for Holistic Indoor Scene Understanding (arXiv).Get the code to generate the dataset:ML Hypersim Dataset (Apple, GitHub).Via David Ha (Twitter).###################################################



MIRI&rsquo;s had some negative research results (and that&rsquo;s okay):&hellip;AI safety group gives research update&hellip;MIRI, an AI safety research organization, has spent a few years working on some research that hasn&rsquo;t worked well, according to the organization. In a 2020 update post, the group said &ldquo;2020 saw limited progress in the research MIRI&rsquo;s leadership had previously been most excited about&rdquo;. As a consequence, &ldquo;MIRI&rsquo;s research leadership is shifting much of their focus towards searching for more promising paths&rdquo;. The company said it projects to have spent around $7 million in 2020, and estimates around $7 million again in 2021.



Why this matters: MIRI decided in 2018 that its future research results would be &ldquo;nondisclosed-by-default&rdquo; (Import AI 122). That&rsquo;s a decision that inspired some strong feelings among advocates for open publication, but I think it&rsquo;s a credit to the organization to update the world that some of these opaque research projects haven&rsquo;t panned out. A signal is better than no signal at all, and I&rsquo;m excited to see MIRI continue to experiment in different forms of high-impact research disclosure (and non-disclosure). Plus, we should always celebrate organizations owning their own &lsquo;negative results&rsquo; &ndash; though perhaps now MIRI thinks these approaches won&rsquo;t work, it could publish them and save other researchers the trouble of replicating blind-alley projects.&nbsp; &nbsp; Read more: 2020 Updates and Strategy (MIRI blog).



###################################################



Google&rsquo;s PR, policy, and legal teams censor its research:&hellip;Suspicious about the oh-so-positive narratives in corporate papers? You should be!&hellip;Google&rsquo;s PR, policy, and legal teams have been editing AI research papers to give them a more positive slant, reduce focus on Google&rsquo;s products, and generally minimize discussion of the potential drawbacks of technology, according to reporting from Reuters.



The news of the censorship operation follows Google firing Timnit Gebru, after Google staff wanted to step in and heavily alter and/or remove Google-affiliated authors from a research paper discussing some of the issues inherent to large language models like BERT, GPT3, and so on. Now, according to Reuters, it seems Google has been censoring a many papers for many months.



What censorship looks like: &ldquo;The Google paper for which authors were told to strike a positive tone discusses recommendation AI, which services like YouTube employ to personalize users&rsquo; content feeds. A draft reviewed by Reuters included &ldquo;concerns&rdquo; that this technology can promote &ldquo;disinformation, discriminatory or otherwise unfair results&rdquo; and &ldquo;insufficient diversity of content,&rdquo; as well as lead to &ldquo;political polarization.&rdquo;,&rdquo; Reuters writes. &ldquo;The final publication instead says the systems can promote &ldquo;accurate information, fairness, and diversity of content.&rdquo; The published version, entitled &ldquo;What are you optimizing for? Aligning Recommender Systems with Human Values,&rdquo; omitted credit to Google researchers. Reuters could not determine why.&rdquo;



Why this matters: People aren&rsquo;t stupid. Let me repeat that: PEOPLE AREN&rsquo;T STUPID. Most corporations seem to think AI is some kind of impossibly obscure technology that normies don&rsquo;t deserve to know about, so they feel like they can censor research to their own gain. But, as I have said, PEOPLE ARE NOT STUPID. People use AI systems every day &ndash; so people know AI systems have problems. This kind of attitude from Google is absurd, patronizing, and ultimately corrosive to civilisation-level scientific progress. I spoke about issues relating to this in December 2018 in a podcast with Azeem Azhar, where I compared this approach to science to how Christian priests in the dark ages kept knowledge inside monasteries, thinking it too dangerous for the peasants. (Things didn&rsquo;t work out super well for the priests). It&rsquo;s also just a huge waste of the time of the researchers being censored by their corporation. Don&rsquo;t waste people&rsquo;s time! We all only have a finite amount of it.&nbsp;Read more: Google told its scientists to &lsquo;strike a positive tone&rsquo; in AI research &ndash; documents (Reuters).



###################################################



How can I mess up your ML model? Let me count the ways:&hellip;Feature Collisions! Label Poisoning! Influence Functions! And more&hellip;How do people attack the datasets used to train machine learning models, what can these attacks do, and how can we defend against them? That&rsquo;s the subject of a survey paper from researchers with the University of Maryland, MIT, the University of Illinois Urbana-Champaign, and the University of California, Berkeley.



Attacking datasets: The paper summarizes the range of techniques people might use to attack datasets, giving a guided tour of horrors like poisoning the input data to cause a misclassification, or perturbing the outputs of already trained models (for instance, by giving them an input that they can&rsquo;t classify, or which leads to pathological behavior).



Defending against attacks: Fear not! There are some ways to defend or mitigate these attacks, including federated learning, the use of privacy preserving machine learning approaches like differential privacy, and learning to detect adversarial triggers, among others.



Why this matters: AI systems are so complicated that their capability surface, especially for recent large-scale models, are vast and hard to characterize. This is basically catnip for security-minded people that want to mess with these systems &ndash; a vast, somewhat uncharacterized territory is the perfect place to unleash some mischief. But if we don&rsquo;t figure out how to secure these models, it&rsquo;ll be much harder to deploy them broadly into the world.Read more: Data Security for Machine Learning: Data Poisoning, Backdoor Attacks, and Defenses (arXiv).



###################################################Tech Tales:



Plato, give me your favorite recipe[California, 2040. Simulated ancient Greece.]



Plato was talking to a bunch of Greeks. He was exp…