---

layout: post
category: product
title: "Import AI 219: Climate change and function approximation; Access Now leaves PAI; LSTMs are smarter than they seem"
date: 2020-10-19 05:16:27
link: https://vrhk.co/3dErGG5
image: 
domain: jack-clark.net
author: "Jack Clark"
icon: https://s2.wp.com/i/webclip.png
excerpt: "LSTMs: Smarter than they appear:&hellip;Turns out you don&rsquo;t need to use a Transformer to develop rich, combinatorial representations&hellip;Long Short-Term Memory networks are one of the widely-used deep learning architectures. Until recently, if you wanted to develop sophisticated natural language understanding AI systems, you&rsquo;d use an LSTM. Then in the past couple of years, people have started switching over to using the &lsquo;Transformer&rsquo; architecture because it comes with inbuilt attention, which lets it smartly analyze long-range dependencies in data.



Now, researchers from the University of Edinburgh have studied how LSTMs learn long-range dependencies; LSTMs figure out how to make predictions about long sequences by learning patterns in short sequences then using these patterns as &lsquo;scaffolds&rsquo; for learning longer, more complex ones. &ldquo;Acquisition is biased towards bottom-up learning, using the constituent as a scaffold to support the long-distance rule,&rdquo; they write. &ldquo;These results indicate that predictable patterns play a vital role in shaping the representations of symbols around them by composing in a way that cannot be easily linearized as a sum of the component parts&rdquo;.



The goldilocks problem: However, this form of learning has some drawbacks &ndash; if you get your data mix one, the LSTM might quickly learn how to solve shorter sequences, but fail to generalize to longer ones. If you make its training distribution too hard, it might find it hard to learn at all.&nbsp;



Why this matters &ndash; more human than you think: In recent years, one of the more surprising trends in AI has been in identifying surface-level commonalities between our AI systems and how they learn, and how people learn. This study of the LSTM provides some slight evidence that these networks, though basic, learn via some similarly rich, additive procedures as people. &lsquo;The LSTM&rsquo;s demonstrated inductive bias towards hierarchical structures is implicitly aligned with our understanding of language and emerges from its natural learning process,&rdquo; they write.Read more:LSTMs Compose (and Learn) Bottom-Up (arXiv).



###################################################



Google speeds up AI chip design by 8.6X with new RL training system:&hellip;Menger: The machine that learns the machines&hellip;Google has developed Menger, software that lets the company train reinforcement learning systems at a large scale. This is one of those superficially dull announcements which is surprisingly significant. That&rsquo;s because RL, while useful, is currently quite expensive in terms of computation; therefore, RL benefits from compute, which requires being able to run a sophisticated learning system at a large scale. That&rsquo;s what Menger is designed to do &ndash; in tests, Google says it has used Menger to reduce the time it takes the company to train RL for a chip placement task by 8.6x &ndash; cutting the training time for the task from 8.6 hours to one hour (when using 512 CPU cores).



Why this matters: Google is at the beginning of building an AI flywheel &ndash; that is, a suite of complementary bits of AI software which can accelerate Google&rsquo;s broader software development practices. Menger will help Google more efficiently train AI systems, and Google will use that to do things like develop more efficient computers (and sets of computers) via chip placement, and these new computers will then be used to train and develop successive systems. Things are going to accelerate rapidly from here.&nbsp; Read more:Massively Large-Scale Distributed Reinforcement Learning with Menger (Google AI Blog).



###################################################



Access Now leaves PAI:&hellip;Human Rights VS Corporate Rights&hellip;Civil society organization Access Now is leaving the Partnership on AI, a multi-stakeholder group (with heavy corporate participation) that tries to bring people together to talk about AI and its impact on society.



Talking is easy, change is hard: Over its lifetime, PAI has accomplished a few things, but one of the inherent issues with the org is &lsquo;it is what people make of it&rsquo; &ndash; which means that for many of the corporations, they treat it like an extension of their broader public relations and government affairs initiatives. &ldquo;While we support dialogue between stakeholders, we did not find that PAI influenced or changed the attitude of member companies or encouraged them to respond to or consult with civil society on a systematic basis,&rdquo; Access Now said in a statement.



Why this matters: In the absence of informed and effective regulators, society needs to figure out the rules of the road for AI development. PAI is an organization that&rsquo;s meant to play that role, but Access Now&rsquo;s experience illustrates the difficulty in a single org being able to deal with structural inequities which make some of its members very powerful (e.g, the tech companies), and some of them comparatively weaker.&nbsp; Read more:Access Now resigns from the Partnership on AI (Access Now official website).



###################################################



Can AI tackle climate change? Facebook and CMU think so:&hellip;Science, meet function approximation&hellip;Researchers with Facebook and Carnegie Mellon University have built a massive dataset to help researchers develop ML systems that can help us discover good electrocatalysts for use in renewable energy storage technologies. The Open Catalyst Dataset contains 1.2 million molecular relaxations (stable low-energy states) with results from over 250 million DFT (density functional theory) calculations.&nbsp; DFT, for those not familiar with the finer aspects of modeling the essence of the universe, is a punishingly expensive way to model fine-grained interactions (e.g, molecular reactions). DFT simulations can take &ldquo;hours&ndash;weeks per simulation using O(10&ndash;100) core CPUs on structures containing O(10&ndash;100) atoms,&rdquo; Facebook writes. &ldquo;As a result, complete exploration of catalysts using DFT is infeasible. DFT relaxations also fail more often when the structures become large (number of atoms) and complex&rdquo;.&nbsp; Therefore, the value of what Facebook and CMU have done here is they&rsquo;ve eaten the cost of a bunch of DFT simulations and used this to release a rich dataset, which ML researchers can use to train ML systems to approximate this data. Maybe that sounds dull to you, but this is literally a way to drastically reduce the cost of a branch of science that is existential to the future of the earth, so I think it&rsquo;s pretty interesting!



Why this matters: Because deep learning systems can learn complex functions then approximate them, we&rsquo;re going to see people use them more and more to carry out unfeasibly expensive scientific exercises &ndash; like attempting to approximate highly complex chemical interactions. In this respect, Open Catalyst sits alongside projects like DeepMind&rsquo;s &lsquo;AlphaFold&rsquo; (Import AI 209, 189), or earlier work like &lsquo;ChemNet&rsquo; which tries to pre-train systems on large chemistry datasets then apply them to smaller ones (Import AI 72).&nbsp; Read more:Open Catalyst Project (official website).&nbsp; Get the datafor Open Catalyst here (GitHub).&nbsp; Read the paper:An Introduction to Electrocatalyst Design using Machine Learning for Renewable Energy Storage (PDF).&nbsp; &nbsp; Read more:The Open Catalyst 2020 (OC20) Dataset and Community Challenges (PDF).



###################################################



Google X builds field-grokking robot to analyze plantlife:&hellip;Sometimes, surveillance is great!&hellip;Google has revealed Project Mineral, a Google X initiative to use machine learning to analyze how plants grow in fields and to make farmers more efficient. As part of this, Google has built a small ro…"

---

### Import AI 219: Climate change and function approximation; Access Now leaves PAI; LSTMs are smarter than they seem

LSTMs: Smarter than they appear:&hellip;Turns out you don&rsquo;t need to use a Transformer to develop rich, combinatorial representations&hellip;Long Short-Term Memory networks are one of the widely-used deep learning architectures. Until recently, if you wanted to develop sophisticated natural language understanding AI systems, you&rsquo;d use an LSTM. Then in the past couple of years, people have started switching over to using the &lsquo;Transformer&rsquo; architecture because it comes with inbuilt attention, which lets it smartly analyze long-range dependencies in data.



Now, researchers from the University of Edinburgh have studied how LSTMs learn long-range dependencies; LSTMs figure out how to make predictions about long sequences by learning patterns in short sequences then using these patterns as &lsquo;scaffolds&rsquo; for learning longer, more complex ones. &ldquo;Acquisition is biased towards bottom-up learning, using the constituent as a scaffold to support the long-distance rule,&rdquo; they write. &ldquo;These results indicate that predictable patterns play a vital role in shaping the representations of symbols around them by composing in a way that cannot be easily linearized as a sum of the component parts&rdquo;.



The goldilocks problem: However, this form of learning has some drawbacks &ndash; if you get your data mix one, the LSTM might quickly learn how to solve shorter sequences, but fail to generalize to longer ones. If you make its training distribution too hard, it might find it hard to learn at all.&nbsp;



Why this matters &ndash; more human than you think: In recent years, one of the more surprising trends in AI has been in identifying surface-level commonalities between our AI systems and how they learn, and how people learn. This study of the LSTM provides some slight evidence that these networks, though basic, learn via some similarly rich, additive procedures as people. &lsquo;The LSTM&rsquo;s demonstrated inductive bias towards hierarchical structures is implicitly aligned with our understanding of language and emerges from its natural learning process,&rdquo; they write.Read more:LSTMs Compose (and Learn) Bottom-Up (arXiv).



###################################################



Google speeds up AI chip design by 8.6X with new RL training system:&hellip;Menger: The machine that learns the machines&hellip;Google has developed Menger, software that lets the company train reinforcement learning systems at a large scale. This is one of those superficially dull announcements which is surprisingly significant. That&rsquo;s because RL, while useful, is currently quite expensive in terms of computation; therefore, RL benefits from compute, which requires being able to run a sophisticated learning system at a large scale. That&rsquo;s what Menger is designed to do &ndash; in tests, Google says it has used Menger to reduce the time it takes the company to train RL for a chip placement task by 8.6x &ndash; cutting the training time for the task from 8.6 hours to one hour (when using 512 CPU cores).



Why this matters: Google is at the beginning of building an AI flywheel &ndash; that is, a suite of complementary bits of AI software which can accelerate Google&rsquo;s broader software development practices. Menger will help Google more efficiently train AI systems, and Google will use that to do things like develop more efficient computers (and sets of computers) via chip placement, and these new computers will then be used to train and develop successive systems. Things are going to accelerate rapidly from here.&nbsp; Read more:Massively Large-Scale Distributed Reinforcement Learning with Menger (Google AI Blog).



###################################################



Access Now leaves PAI:&hellip;Human Rights VS Corporate Rights&hellip;Civil society organization Access Now is leaving the Partnership on AI, a multi-stakeholder group (with heavy corporate participation) that tries to bring people together to talk about AI and its impact on society.



Talking is easy, change is hard: Over its lifetime, PAI has accomplished a few things, but one of the inherent issues with the org is &lsquo;it is what people make of it&rsquo; &ndash; which means that for many of the corporations, they treat it like an extension of their broader public relations and government affairs initiatives. &ldquo;While we support dialogue between stakeholders, we did not find that PAI influenced or changed the attitude of member companies or encouraged them to respond to or consult with civil society on a systematic basis,&rdquo; Access Now said in a statement.



Why this matters: In the absence of informed and effective regulators, society needs to figure out the rules of the road for AI development. PAI is an organization that&rsquo;s meant to play that role, but Access Now&rsquo;s experience illustrates the difficulty in a single org being able to deal with structural inequities which make some of its members very powerful (e.g, the tech companies), and some of them comparatively weaker.&nbsp; Read more:Access Now resigns from the Partnership on AI (Access Now official website).



###################################################



Can AI tackle climate change? Facebook and CMU think so:&hellip;Science, meet function approximation&hellip;Researchers with Facebook and Carnegie Mellon University have built a massive dataset to help researchers develop ML systems that can help us discover good electrocatalysts for use in renewable energy storage technologies. The Open Catalyst Dataset contains 1.2 million molecular relaxations (stable low-energy states) with results from over 250 million DFT (density functional theory) calculations.&nbsp; DFT, for those not familiar with the finer aspects of modeling the essence of the universe, is a punishingly expensive way to model fine-grained interactions (e.g, molecular reactions). DFT simulations can take &ldquo;hours&ndash;weeks per simulation using O(10&ndash;100) core CPUs on structures containing O(10&ndash;100) atoms,&rdquo; Facebook writes. &ldquo;As a result, complete exploration of catalysts using DFT is infeasible. DFT relaxations also fail more often when the structures become large (number of atoms) and complex&rdquo;.&nbsp; Therefore, the value of what Facebook and CMU have done here is they&rsquo;ve eaten the cost of a bunch of DFT simulations and used this to release a rich dataset, which ML researchers can use to train ML systems to approximate this data. Maybe that sounds dull to you, but this is literally a way to drastically reduce the cost of a branch of science that is existential to the future of the earth, so I think it&rsquo;s pretty interesting!



Why this matters: Because deep learning systems can learn complex functions then approximate them, we&rsquo;re going to see people use them more and more to carry out unfeasibly expensive scientific exercises &ndash; like attempting to approximate highly complex chemical interactions. In this respect, Open Catalyst sits alongside projects like DeepMind&rsquo;s &lsquo;AlphaFold&rsquo; (Import AI 209, 189), or earlier work like &lsquo;ChemNet&rsquo; which tries to pre-train systems on large chemistry datasets then apply them to smaller ones (Import AI 72).&nbsp; Read more:Open Catalyst Project (official website).&nbsp; Get the datafor Open Catalyst here (GitHub).&nbsp; Read the paper:An Introduction to Electrocatalyst Design using Machine Learning for Renewable Energy Storage (PDF).&nbsp; &nbsp; Read more:The Open Catalyst 2020 (OC20) Dataset and Community Challenges (PDF).



###################################################



Google X builds field-grokking robot to analyze plantlife:&hellip;Sometimes, surveillance is great!&hellip;Google has revealed Project Mineral, a Google X initiative to use machine learning to analyze how plants grow in fields and to make farmers more efficient. As part of this, Google has built a small ro…