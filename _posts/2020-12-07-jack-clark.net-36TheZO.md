---

layout: post
category: product
title: "Import AI 226: AlphaFold; a Chinese GPT2; Timnit Gebru leaves Google"
date: 2020-12-07 18:56:28
link: https://vrhk.co/36TheZO
image: 
domain: jack-clark.net
author: "Jack Clark"
icon: https://s2.wp.com/i/webclip.png
excerpt: "DeepMind cracks the protein folding problem:&hellip;AlphaFold&rsquo;s protein structure predictions start to match reality&hellip;AlphaFold, a system built by DeepMind to predict the structures of proteins, has done astonishingly well at the Critical Assessment of protein Structure Prediction (CASP) competition. AlphaFold&rsquo;s &ldquo;predictions have an average error (RMSD) of approximately 1.6 Angstroms, which is comparable to the width of an atom (or 0.1 of a nanometer),&rdquo; according to DeepMind.&nbsp; What does this mean? Being able to make (correct) predictions about protein structures can speed up scientific discovery, because it makes it cheaper and quicker to explore a variety of ideas that require validating against protein structures. &ldquo;This will change medicine. It will change research. It will change bioengineering. It will change everything,&rdquo; Andrei Lupas, an evolutionary biologist at the Max Planck Institute for Developmental Biology, told Nature.How big a deal is this really? Many biologists seem impressed by AlphaFold, marking the result as a landmark achievement. AlphaFold is very much a &lsquo;v1&rsquo; system &ndash; it&rsquo;s impressive in its own right, but there are a bunch of things that&rsquo;ll need to be improved in the future; more capable versions of the system will need to model how proteins move as dynamic systems, as well as making predictions at more detailed resolutions.&nbsp; &ldquo;A lot of structural biologists might be thinking that they might be out of a job soon! I don&rsquo;t think we are anywhere close to this. Structures like ribosomes and photosynthesis centres are huge and complex in comparison. How the many different parts fit together to form a functional machine is still a big challenge for AI in the near future,&rdquo; said structural biology professor Peijun Zhang in an interview with The Biologist.Why this matters: AlphaFold is one of the purest examples of why ML-based function approximation is powerful &ndash; here&rsquo;s a system where, given sufficient computation and a clever enough architecture, humans can use it to predict eerily accurate things about the fundamental structure of the biomachines that underpin life itself. This is profound and points to a future where many of our most fundamental questions get explored (or even answered) by dumping compute into a system that can learn to approximate a far richer underlying &lsquo;natural&rsquo; process.&nbsp; Read more: AlphaFold: a solution to a 50-year-old grand challenge in biology (DeepMind blog).&nbsp; Read more: &lsquo;It will change everything&rsquo;: DeepMind&rsquo;s AI makes gigantic leap in solving protein structures (Nature).###################################################



Russia plans general AI lab &ndash; and Schmidhuber is (somewhat) involved:&hellip;Russia taps AI pioneer to launch in-country research lab focused on &ldquo;general artificial intelligence&rdquo;&hellip;Sberbank, the largest bank in Russia, will open an institute focused on developing general artificial intelligence. And AI pioneer Juergen Schmidhuber is going to be an honorary leader of  this really happening? Tass is a reputable news agency, but I couldn&rsquo;t find a reference to Schmidhuber on websites associated with Sberbank. I emailed Juergen at his academic address to confirm, and he clarified that: &ldquo;I was invited for an honorary role at a new academic institute. I will keep my present affiliations with IDSIA and NNAISENSE&rdquo;.Who is Schmidhuber? Schmidhuber is one of the main figures in AI responsible for the current boom, alongside Geoff Hinton (UofT / Google), Yann Lecun (NYU / Facebook), and Yoshua Bengio (MILA / ElementAI). Unlike those three, he didn&rsquo;t win a Turing award, but he&rsquo;s been a prolific researcher, co-invented the LSTM, theorized some early GAN dynamics via POWERPLAY, and many of the next generation have come out of his IDSIA lab (including prominent researchers at DeepMind).&nbsp;Russian general AI: &ldquo;In the near future, we will open the first AI institute in Russia with the involvement of leading domestic and world scientists. The main mission of the institute is to provide an interdisciplinary approach to research to create general artificial intelligence,&rdquo; said Herman Gref, CEO of Russia&rsquo;s Sberbank, according to Tass news agency.Read more:Sberbank plans to open Russia&rsquo;s first AI institute (Tass News Agency).



###################################################



Amazon enters the custom AI training race with AWS &lsquo;Trainium&rsquo; chips:&hellip;TPU, meet Trainium&hellip;Amazon has become the second major cloud company to offer a specialized processor for training AI workloads on its cloud, starting a competition with Google, which fields Tensor Processing Unit (TPU) chips on its cloud. Both companies are betting that if they can design chips specialized for DL workloads (combined with an easy-to-use software stack), then developers will switch from using industry standard GPUs for AI training. This likely nets the companies better margins and also the ability to own their own compute destiny, rather than be tied so closely to the roadmaps of NVIDIA (and more recently AMD).



AWS trainium: Trainium allegedly has the &ldquo;highest performance and lowest cost for ML training in the cloud&rdquo;, though without being able to see the speeds and feeds and benchmarks, it&rsquo;s hard to know what to make of this. The chips will be available in 2021, Amazon says, and are compatible with Amazon&rsquo;s &lsquo;Neuron&rsquo; SDK.



Why this matters: ML training hardware is a strategic market &ndash; building AI systems is hard, complicated work, and the type of computing substrate you use is one of the fundamental constraints on your development. Whoever owns the compute layer will get to see the evolution of AI and where demands for new workloads are coming from. This is analogous to owning a slice of the future, so it&rsquo;s no wonder companies are competing with eachother.Read more: AWS Trainium (AWS product page).



###################################################



Google&rsquo;s balloons learn to fly with RL:&hellip;Finally, another real world use case for reinforcement learning!&hellip;Google has used reinforcement learning to teach its &lsquo;Loon&rsquo; balloons to navigate the stratosphere &ndash; another example of RL being used in the real world, and one which could point to further, significant deployments.



What they did: Loon is a Google project dedicated to providing internet to remote places via weather  do that, Google&rsquo;s Loon balloons need to stay aloft in the stratosphere, while responding intelligently to things like wind speed, pressure changes, and so on.&nbsp; Expensive simulation: Any RL process typically requires a software-based simulator that you can train your agents in, before transferring them into the real world. The same is true here; Google simulates various complex datasets relating to wind and atmospheric movements, then trains its balloons with the objective to stay relatively close to their (simulated) assigned ground station. Due to the complexity of the data, the simulation is relatively heavy duty, running more slowly than ones used for games.&nbsp; &nbsp; &ldquo;A trial consists of two simulated days of station-keeping at a fixed location, during which controllers receive inputs and emit commands at 3-min intervals. Flight controllers are thus exposed to diurnal cycles and scenarios in which the balloon must recover from difficult overnight conditions. These realistic flight paths come at the cost of relatively slow simulation&mdash;roughly 40 Hz on data-centre hardware. In comparison, the Arcade Learning Environment (ALE) benchmark operates at over 8,000 Hz,&rdquo; Google says.



Real world test: Google tested the system in the real world, racking up &ldquo;a total of 2,884 flight hours from 17 December 2019 to …"

---

### Import AI 226: AlphaFold; a Chinese GPT2; Timnit Gebru leaves Google

DeepMind cracks the protein folding problem:&hellip;AlphaFold&rsquo;s protein structure predictions start to match reality&hellip;AlphaFold, a system built by DeepMind to predict the structures of proteins, has done astonishingly well at the Critical Assessment of protein Structure Prediction (CASP) competition. AlphaFold&rsquo;s &ldquo;predictions have an average error (RMSD) of approximately 1.6 Angstroms, which is comparable to the width of an atom (or 0.1 of a nanometer),&rdquo; according to DeepMind.&nbsp; What does this mean? Being able to make (correct) predictions about protein structures can speed up scientific discovery, because it makes it cheaper and quicker to explore a variety of ideas that require validating against protein structures. &ldquo;This will change medicine. It will change research. It will change bioengineering. It will change everything,&rdquo; Andrei Lupas, an evolutionary biologist at the Max Planck Institute for Developmental Biology, told Nature.How big a deal is this really? Many biologists seem impressed by AlphaFold, marking the result as a landmark achievement. AlphaFold is very much a &lsquo;v1&rsquo; system &ndash; it&rsquo;s impressive in its own right, but there are a bunch of things that&rsquo;ll need to be improved in the future; more capable versions of the system will need to model how proteins move as dynamic systems, as well as making predictions at more detailed resolutions.&nbsp; &ldquo;A lot of structural biologists might be thinking that they might be out of a job soon! I don&rsquo;t think we are anywhere close to this. Structures like ribosomes and photosynthesis centres are huge and complex in comparison. How the many different parts fit together to form a functional machine is still a big challenge for AI in the near future,&rdquo; said structural biology professor Peijun Zhang in an interview with The Biologist.Why this matters: AlphaFold is one of the purest examples of why ML-based function approximation is powerful &ndash; here&rsquo;s a system where, given sufficient computation and a clever enough architecture, humans can use it to predict eerily accurate things about the fundamental structure of the biomachines that underpin life itself. This is profound and points to a future where many of our most fundamental questions get explored (or even answered) by dumping compute into a system that can learn to approximate a far richer underlying &lsquo;natural&rsquo; process.&nbsp; Read more: AlphaFold: a solution to a 50-year-old grand challenge in biology (DeepMind blog).&nbsp; Read more: &lsquo;It will change everything&rsquo;: DeepMind&rsquo;s AI makes gigantic leap in solving protein structures (Nature).###################################################



Russia plans general AI lab &ndash; and Schmidhuber is (somewhat) involved:&hellip;Russia taps AI pioneer to launch in-country research lab focused on &ldquo;general artificial intelligence&rdquo;&hellip;Sberbank, the largest bank in Russia, will open an institute focused on developing general artificial intelligence. And AI pioneer Juergen Schmidhuber is going to be an honorary leader of  this really happening? Tass is a reputable news agency, but I couldn&rsquo;t find a reference to Schmidhuber on websites associated with Sberbank. I emailed Juergen at his academic address to confirm, and he clarified that: &ldquo;I was invited for an honorary role at a new academic institute. I will keep my present affiliations with IDSIA and NNAISENSE&rdquo;.Who is Schmidhuber? Schmidhuber is one of the main figures in AI responsible for the current boom, alongside Geoff Hinton (UofT / Google), Yann Lecun (NYU / Facebook), and Yoshua Bengio (MILA / ElementAI). Unlike those three, he didn&rsquo;t win a Turing award, but he&rsquo;s been a prolific researcher, co-invented the LSTM, theorized some early GAN dynamics via POWERPLAY, and many of the next generation have come out of his IDSIA lab (including prominent researchers at DeepMind).&nbsp;Russian general AI: &ldquo;In the near future, we will open the first AI institute in Russia with the involvement of leading domestic and world scientists. The main mission of the institute is to provide an interdisciplinary approach to research to create general artificial intelligence,&rdquo; said Herman Gref, CEO of Russia&rsquo;s Sberbank, according to Tass news agency.Read more:Sberbank plans to open Russia&rsquo;s first AI institute (Tass News Agency).



###################################################



Amazon enters the custom AI training race with AWS &lsquo;Trainium&rsquo; chips:&hellip;TPU, meet Trainium&hellip;Amazon has become the second major cloud company to offer a specialized processor for training AI workloads on its cloud, starting a competition with Google, which fields Tensor Processing Unit (TPU) chips on its cloud. Both companies are betting that if they can design chips specialized for DL workloads (combined with an easy-to-use software stack), then developers will switch from using industry standard GPUs for AI training. This likely nets the companies better margins and also the ability to own their own compute destiny, rather than be tied so closely to the roadmaps of NVIDIA (and more recently AMD).



AWS trainium: Trainium allegedly has the &ldquo;highest performance and lowest cost for ML training in the cloud&rdquo;, though without being able to see the speeds and feeds and benchmarks, it&rsquo;s hard to know what to make of this. The chips will be available in 2021, Amazon says, and are compatible with Amazon&rsquo;s &lsquo;Neuron&rsquo; SDK.



Why this matters: ML training hardware is a strategic market &ndash; building AI systems is hard, complicated work, and the type of computing substrate you use is one of the fundamental constraints on your development. Whoever owns the compute layer will get to see the evolution of AI and where demands for new workloads are coming from. This is analogous to owning a slice of the future, so it&rsquo;s no wonder companies are competing with eachother.Read more: AWS Trainium (AWS product page).



###################################################



Google&rsquo;s balloons learn to fly with RL:&hellip;Finally, another real world use case for reinforcement learning!&hellip;Google has used reinforcement learning to teach its &lsquo;Loon&rsquo; balloons to navigate the stratosphere &ndash; another example of RL being used in the real world, and one which could point to further, significant deployments.



What they did: Loon is a Google project dedicated to providing internet to remote places via weather  do that, Google&rsquo;s Loon balloons need to stay aloft in the stratosphere, while responding intelligently to things like wind speed, pressure changes, and so on.&nbsp; Expensive simulation: Any RL process typically requires a software-based simulator that you can train your agents in, before transferring them into the real world. The same is true here; Google simulates various complex datasets relating to wind and atmospheric movements, then trains its balloons with the objective to stay relatively close to their (simulated) assigned ground station. Due to the complexity of the data, the simulation is relatively heavy duty, running more slowly than ones used for games.&nbsp; &nbsp; &ldquo;A trial consists of two simulated days of station-keeping at a fixed location, during which controllers receive inputs and emit commands at 3-min intervals. Flight controllers are thus exposed to diurnal cycles and scenarios in which the balloon must recover from difficult overnight conditions. These realistic flight paths come at the cost of relatively slow simulation&mdash;roughly 40 Hz on data-centre hardware. In comparison, the Arcade Learning Environment (ALE) benchmark operates at over 8,000 Hz,&rdquo; Google says.



Real world test: Google tested the system in the real world, racking up &ldquo;a total of 2,884 flight hours from 17 December 2019 to …