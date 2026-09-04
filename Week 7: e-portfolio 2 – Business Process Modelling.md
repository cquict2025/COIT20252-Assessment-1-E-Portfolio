# Week 7: E-Portfolio 2: Business Process Modelling

# Artefact 1: BPMN Business Process Modeling for Beginners – Tool Rental (video)

**Watch on YouTube:** https://youtu.be/HEdoyk4GKho.

**Summary:**

Hense (2025) builds a BPMN 2.0 model of a tool rental process live in Camunda Modeler. He adds elements one at a time and explains why each gateway, event and lane is needed (Hense 2025, 04:06). The finished model has one company pool with four role lanes, a collapsed Supplier pool, and event-based gateways with message and timer events so the process waits for replies (Hense 2025, 39:50).

**Why I chose it:**

I selected this because Week 4 lectures introduced BPMN 2.0 as the notation that supports design, analysis and execution (ABPMP International 2019, p. 98). The lecture showed the symbols. This video shows how a modeller decides what to leave out. Hense never models the supplier's own steps he collapses that pool and shows only the messages that cross it (Hense 2025, 39:50). Before this I would have drawn the supplier's process too. Now I understand the Week 5 point that a process is modelled only to the level its purpose needs, and that other organisations' processes sit at a higher level (ABPMP International 2019, p. 113).

![Hense's finished tool-rental model showing four lanes, the collapsed Supplier pool and event-based gateways](images/hense-tool-rental.png)

*Figure 1: The finished tool rental model in Camunda Modeler. Source: Hense (2025, 39:50)*

---

## Artefact 2: *Practical Business Process Modeling and Analysis* – Chapter 1 (book)

 [Chapter 1 free preview on Packt](https://www.packtpub.com/en-au/product/practical-business-process-modeling-and-analysis-9781805126744)

**Summary:**

Sinur, Misiak and Biernatowski (2025) argue in Chapter 1 that modelling and analysing processes is now a basic skill, not a specialist one. Digital and AI transformation programs fail when they automate processes nobody has understood (Sinur, Misiak & Biernatowski 2025). The chapter positions BPMN as the link between strategy and execution (Sinur, Misiak & Biernatowski 2025)

**Why I chose it:**

This chapter matters because it explains the "why" behind the Week 4 purpose of modelling, which is to represent a process accurately and sufficiently for the task at hand (ABPMP International 2019, p. 94). The authors warn that organisations lead with technology instead of process. This matches the Week 7 lecture point that technology-first change fails because it does not start from the customer or the process (ABPMP International 2019, p. 203). Reading both together showed me that modelling is a strategic activity, not just documentation. The book is practitioner opinion rather than research, but it gives a current view that CBOK does not.

---

## Artefact 3: Artificial intelligence in business process modelling – a structured overview (conference paper)

[IEEE Xplore record](https://ieeexplore.ieee.org/document/11205411) · DOI: 10.1109/ICT58284.2025.11205411

**Summary:** 

Subotic (2025) reviews forty-two peer-reviewed studies from 2022 to 2025, selected with the PRISMA method across four databases, to map how AI is changing the way process models are built (Subotic 2025). The main trend is natural language processing and large language models that generate BPMN models from text descriptions. The paper identifies gaps, especially the lack of standard ways to judge the quality of a generated model (Subotic 2025).

**Why I chose it:**
I included this after Week 5 noted that Visio, PowerPoint and Excel are still the most used modelling tools, and that analysis should focus on the process, not the tool (ABPMP International 2019, p. 124). This paper shows a new tool capability arriving: the tool drafts the model (ABPMP International 2019, p. 94). If that happens, the modeller's value moves to validation, which Week 5 defined as checking the model consistently produces the intended outcome. I now see tool selection and model validation as one decision, not two. The paper's limitation is that it is a single-author conference review, so it is a snapshot rather than a settled view.

---
## Artefact 4: Business Process Diagramming and Process Analysis – The Anderson Inc. Logistics Case (journal article)

[Issues in Accounting Education, 40(3)](https://doi.org/10.2308/ISSUES-2023-098)

**Summary:**
Bradford, Bucy and Lee (2025) present a teaching case where students document the as-is procure-to-pay and logistics processes of a fictitious company in BPMN. Students then use the diagram to find control weaknesses and inefficiencies, including tolerance limits in the three-way match, and propose a streamlined to-be process (Bradford, Bucy & Lee 2025, p. 141). The teaching notes include a reference BPMN solution (Bradford, Bucy & Lee 2025).

**Why I chose it:**

This case is here because it is the clearest example I found of the Week 4 summary point that process models express the as-is state and lead to a to-be model (ABPMP International 2019, p. 99). The control issues students must find are the business rules that Week 6 said should be designed into a process from the start. Working through the case changed how I read a BPMN diagram. I now read it looking for the gateway where a control should sit and does not. It is written for accounting students, so I had to translate its audit language into BPM terms.

---

## References


Bradford, M, Bucy, RA & Lee, LS 2025, 'Business process diagramming and process analysis: the Anderson Inc. logistics case', Issues in Accounting Education, vol. 40, no. 3, pp. 141-156, doi:10.2308/ISSUES-2023-098.

Hense, A 2025, BPMN business process modeling for beginners – tool rental, video recording, BPMN Series, no. 49, Zenodo, doi:10.5281/zenodo.18364293.

Sinur, J, Misiak, Z & Biernatowski, BJ 2025, Practical business process modeling and analysis: design and optimize business processes incrementally for AI transformation using BPMN, Packt Publishing, Birmingham.

Subotic, S 2025, 'Artificial intelligence in business process modelling: a structured overview of trends, challenges and future research direction', 2025 IEEE 23rd Jubilee International Symposium on Intelligent Systems and Informatics (SISY), pp. 000295-000300, doi:10.1109/sisy67000.2025.11205411

