---
layout: default
---

## Digital Twins

![From Snake Oil to AI Papers in Medicine](https://files.virgool.io/upload/users/22770/posts/k26eqia1hlxo/7upnfr0iqern.png)

One thing that has always fascinated me is the reconstruction of complex biological systems on computers. A few years ago, when I first started learning programming, I tried to write a program that I later realized was called cellular automata. Considering my knowledge at that time and the workload, everything didn’t go very well. Eventually, when I got to know about Conway's Game of Life, I realized that I was treading a well-known path and had nothing new to offer. Later, as I worked more in the field of artificial intelligence, I became familiar with the concept of digital twins and felt that I might find what I had thought about back then in this domain and create something new here. Below, I write a few paragraphs about digital twins in healthcare, summarizing several review articles. This includes an explanation of the overall concept and history of digital twins, their types and functionalities, an example, and how they can help us in medicine.

At its core, the concept of digital twins involves creating virtual alter-egos of objects, living organisms, spaces, or processes. The historical roots of digital twins trace back to simulated environments created by NASA in the 1970s to monitor unreachable physical spaces, such as spacecraft during missions. The most famous early application of digital twins occurred during the Apollo 13 mission when one of the oxygen tanks exploded two days after launch. NASA's flight control team in Houston had to model and test possible solutions in a simulated environment. They guided astronauts to build an improvised air purifier using available materials in the spacecraft to bring the Apollo 13 crew back to Earth [1].

Although the concept of digital twins was introduced in the 1970s, it has recently gained new momentum with advancements in processing and artificial intelligence, to the point where the IEEE Computer Society named it the third most popular technology of 2020. However, much of this attention, which has repeatedly occurred throughout history, often diminishes over several years as companies strive to create truly useful and applicable tools. Various fields benefit from this innovation, including industry, construction, and transportation. Another field is life sciences. In essence, virtual reconstruction of any complex system in nature allows us to observe its behavior in new conditions and thus replicate its behavior in the real world. And what could be more fascinating than reconstructing complex components such as cells, cellular processes, or even organs, and eventually, the entire human body?

While the complete virtual reconstruction of the human body may seem far-fetched, creating organs and processes is already happening. Although there may be factors that are overlooked in these organs and processes, as our knowledge of their pathways and components increases, these digital twins will become more complete and closer to reality. Perhaps a few examples can help you understand better.

One of the areas that has gained more popularity is the creation of digital twins for the heart. This process involves two stages: anatomical and functional twinning. In the anatomical stage, a very detailed 3D copy of the real heart is created based on the patient's CT or MRI scans. This stage uses a model like UVC, and with relatively little input data, automatically creates a virtual twin of the heart by utilizing the locations of specific cardiac regions such as the apex or septum.

![From Snake Oil to AI Papers in Medicine](https://files.virgool.io/upload/users/22770/posts/k26eqia1hlxo/6v2mwv53367u.png)

The next stage is creating the functional twin, which covers the heart's electrophysiology. Four main factors are involved in generating ECG waves: depolarization caused by the His-Purkinje system and distribution to the subendocardium, conduction velocity within the ventricles, spatially varying action potential duration, and the conductivity of the torso surrounding the heart. The electrophysiological activity of the anatomical reference frame was simulated and compared with clinical measurements of 12-lead ECGs. These comparisons show that the ECG can be automatically and very closely simulated to the real ECG.

![From Snake Oil to AI Papers in Medicine](https://files.virgool.io/upload/users/22770/posts/k26eqia1hlxo/hbn1ibjvoqir.png)

Creating this model helps doctors and medical staff to use the collected patient data to have a virtual ECG of the patient. They can see the effect of various interventions, such as implanting different devices, on the patient's heart function and ECG virtually before applying them in reality, allowing them to make better decisions [2].

This is just one example among many articles written in this field, which are increasing day by day. Our advancements in hardware and processing power, as well as AI models and algorithms, will make this technology faster and more accurate. Perhaps one day, before any intervention (from drugs to surgery) on the human body, its effectiveness will be tested on a digital twin of that person. Maybe one day, there will be a digital twin of each of us so precise that it can even predict and prevent our cause and time of death due to diseases.

_1.Barricelli, B.R.; Casiraghi, E.; Fogli, D. A survey on digital twin: Definitions, characteristics, applications, and design implications. IEEE Access 2019, 7, 167653–167671._

_2.Gillette, K.; Gsell, M.A.; Prassl, A.J.; Karabelas, E.; Reiter, U.; Reiter, G.; Grandits, T.; Payer, C.; Štern, D.; Urschler, M.; et al. A Framework for the generation of digital twins of cardiac electrophysiology from clinical 12-leads ECGs. Med. Image Anal. 2021, 71, 102080_



[back](./)
