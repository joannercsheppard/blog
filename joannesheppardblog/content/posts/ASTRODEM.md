---
title: "Dementia Detection"
date: 2018-09-01T11:30:03+00:00
---

In the summer of 2018 I was funded to do research as part of the [Junior Research Associate scheme at The University of Sussex](https://www.sussex.ac.uk/study/undergraduate/undergraduate-research/junior-research-associates). During this time I explored methods of finding patients who had been diagnosed with dementia but it had been missed from their medical records. This project was my first ever project using machine learning, in fact, I’m pretty sure it was the first time I ever really used Python in more than a print(“Hello World!”) capacity. And, boy, did I have a lot to learn.

This research was part of the [ASTRODEM](https://www.bsms.ac.uk/research/primary-care-and-population-health/public-health/astrodem/index.aspx) project where “astrophysicists swap galaxies for general practice patient data in an innovative new study, in collaboration with researchers from Brighton and Sussex Medical School”[1]. The premise was that physicists were used to dealing with large, messy datasets through exploring the entire universe, so, can we translate these skills to other fields?

For my part of the project I focused on finding the missing patients. The issue in NHS is that there isn’t great communication between departments, and so, a patient could get a diagnosis from a dementia specialist and this is never communicated to their GP. Or, it is communicated and they are treated for dementia, but this is never seen on their records. This lost diagnosis can cause many issues for the patient as they may not be able to get extra funding to help with their condition. Also, on a local council level, they will not be given adequate funding for the number of patients they have and so the patients are left with worse quality of life. 

So we needed to find the missing patients… But how? Whilst they did not have a diagnosis in their records, they may have other markers. For example, they could be prescribed medication to slow the effects of dementia, or, there could be markers for increasing family concern or more frequent falls. We wanted to utilise this data to find those missing patients.

In the eight-weeks I learnt how to code in Python and SQL as well as tonnes of data engineering (if N/A don’t delete but do something useful), and supervised learning machine learning techniques (from sklearn import randomforest). I had an incredible supervisor, Dr Elizabeth Ford, who helped me out massively with all of the medical jargon I needed to learn, but on the coding side I was all on my own. I would say this was the first time I had ever done real self-directed study and it was difficult, I really did not like it at times, but it was incredibly rewarding.

In the end this project was [published in BMJOpen](https://bmjopen.bmj.com/content/11/1/e039248) and at the time I was incredibly proud. I still am really - not only because it was publishable, but because I knew the absolute pain it took to get there. I would link the code but I honestly can’t find the Github and I have now been locked out of that account because I had the smart idea to link it to my university email addres. But I can promise you, it was terrible code - I rewrote it when I expanded on the project for my undergraduate dissertation and sections that were taking more than 24 hours to run took seconds (in the eight weeks I did not come across a mapping function). But I did also present my findings in a university-wide poster presentation for the JRA students (see the picture below. Can you tell I forgot to turn up to the lecture on creating academic posters?)


This project taught me the value of interdisciplinary work and how it can lead to impactful solutions. It was a fascinating use case that set me on the path of becoming a researcher. Looking back, I am proud of the publication and grateful for the self-directed learning experience.

![Me standing by my poster. Don't ask why I thought that yellow text was a good idea.](https://github.com/joannercsheppard/blog/img/jra-poster.JPG)

[1] https://www.bsms.ac.uk/research/primary-care-and-population-health/public-health/astrodem/index.aspx