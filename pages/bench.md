---
layout: post
title: "Returning to the bench"
date: October 10, 2020
permalink: /returntobench/
output: 
  html_document
  
---

 <img src="../assets/ratchet.png"  width="40%" height="40%">

It’s been a few months since I last wrote here. I joined [Michael Purugganan’s](https://en.wikipedia.org/wiki/Michael_Purugganan) lab and spent the summer trying to infer the demographic history of rice in the context of the peopling of Island Southeast Asia via the [Austronesian expansion](https://en.wikipedia.org/wiki/Austronesian_peoples#Austronesian_expansion).  
  
  
The Austronesian expansion represents one of the largest pre-historic migrations we know of, and is believed to have spread out from Taiwan to Island Southeast Asia, Polynesia, Melanesia, and all the way to Madagascar over a period spanning more than three millennia. What drove this geographical expansion? Was it population growth associated with high-yielding wet rice-based agriculture, or did it have more to do with finding large areas of farmable land for less productive forms of agriculture like millet or rainfed rice?  
  
  
Exploration of such questions combines input from archaeology, anthropology, and most recently, population genetics using both modern and ancient genomes. The genomes of rice varieties indigenous to each region can be used to reconstruct the evolutionary relationships between them, and make inferences about how they spread. For my first project over the summer, the sequencing had already been done before I joined the lab, and all my work was computational (which was just as well, as the pandemic had just hit). It was a good time. I got to learn population genetics theory, perform admixture graph modeling, and demographic inference using site frequency spectra, and work across programming languages to do all of this. This largely continued a tradition from my first year, where all four of my rotations had involved computational projects barring a single flow cytometry experiment.  
  
  
As I now slowly begin to wrap up the summer project, the next stage of my dissertation research does require me to generate my own data, and it’s actually quite exciting. A former post-doc in the lab, Rafal Gutaker, had started collecting centuries-old [rice specimens from herbariums and museums](https://sites.google.com/view/rafalplants/1000hrg-project?authuser=0), and set up an ancient DNA laboratory in the basement of our building. This greatly expands our sampling of indigenous, pre-modern rice varieties across Asia. He was able to show me everything before he left, and I am now in the process of extracting and sequencing DNA from the herbarium specimens. I am going to collect a few more myself as well.
  
  
DNA gets degraded over time. When working with old or ancient specimens, contamination from environmental DNA is therefore a major concern as it could easily mask the often tiny amounts of the small fragments of DNA typically present in the samples. In addition, a lot of DNA becomes inaccessible, for instance through forming cross-links with DNA and proteins, which decreases the yield further when using traditional DNA extraction protocols on ancient samples.  
  
  
To address the contamination issue, all the extraction steps prior to PCR are conducted in a clean room containing its own set of hoods, pipettes, and chemicals, and with very restricted movement of objects in and out of it. PCR is conducted after extractions to amplify the DNA, but because amplified DNA can be a source of contamination, that particular step is performed in the main lab and not in the clean room. Here’s a neat [primer](https://link.springer.com/protocol/10.1007/978-1-4939-9176-1_1) on the considerations of setting up an ancient DNA facility.  
  
  
As for the cross-linking problem, we use an [alternative chemical treatment](https://www.future-science.com/doi/10.2144/000114517) to break up cross-links to release very short pieces of DNA that remain inaccessible when using DNA extraction protocols for modern DNA.