# Heap Leach Modeling SOP

## **OBJECTIVE**

The purpose of this document is to guide customers in effectively using the Data Model for the Heap Leach Modeling. This user manual offers step-by-step instructions to simplify the process, ensuring that users, regardless of their technical background, can navigate and utilize our Heap Leach Recovery Modeling with ease and efficiency.

It is crucial to underscore that the core components of product should be designed and manufactured with adaptability in mind, allowing for modifications as per the unique needs of each client.

This ensures not only the efficiency and effectiveness of the Heap Leaching process but also results in an end product that precisely aligns with the expectations and necessities of each individual client. This practice emphasizes the importance of flexibility and customization in production processes, enhancing their overall success and relevance in diverse application scenarios.

## **SCOPE**

The development of case studies is crucial for identifying and understanding the challenges and problems prevalent in the mining and processing industries. The primary objective of these case studies is to generate the specific information necessary to build Data Models that can offer viable business solutions.

This document is specifically designed with our clients in mind, focusing on Heap Leach Recovery Modeling. Our goal is to facilitate a comprehensive understanding of the Heap Leaching processes, allowing clients to harness the potential of these processes effectively and efficiently. By shifting our focus towards the client's perspective, we aim to deliver a tool that is user-friendly, informative, and valuable for those navigating the complexities of Heap Leaching in mineral processing.

## **TERMINOLOGY**

- Heap Leach
- Pad
- Cyanide
- Lime
- Agglomeration

## **FUNCTIONAL DESCRIPTION**

Heap Leaching involves stacking of metal-bearing ore into a heap on an impermeable pad, irrigating the ore for an extended period of time (weeks, months, or years) with a chemical solution to dissolve the sought-after metals, and collecting the leachant (pregnant solution) as it percolates from the base of the heap.

In heap leaching, crushed and agglomerated ores stacked and leached in the most economical way possible, achieving a net positive cash flow. Heap leaching is more suitable for low grade materials.

It also should be noted that process can be considered as unsuitable for ores with complex mineralogy, hard rock, nonoxidized (ores show mildly or higher degree of refractoriness) and ores with finer metal liberation sizes.

As can be understood, heap leaching is chosen for basic financial reasons, and some of the financial considerations that might result in the selection of heap leaching;

- Capital Risk
- Capital is very difficult or Expensive to raise
- Lack of Sufficient Reserves
- Equal or Better Percent Recovery
- Differential Recovery is not sufficient to justify added investment

The chemistry of leaching gold and silver from their ores is essentially the same for both metals, and many ores contain a mixture of the two. A dilute alkaline solution of sodium cyanide dissolves these metals without dissolving many other ore components (copper, zinc, mercury, and iron are the most common soluble impurities). Solution is maintained at an alkaline pH of 9.5e11. Below a pH value of 9.5, cyanide consumption is typically high. Above a pH value of 11, metal recovery decreases. A pH value above 11 can also result in dissolution of silica, which can cause problems with scale control and blinding of carbon.

Most gold heap leaches apply cyanide within a range of 200 - 600 mg/L NaCN. Silver-bearing ores should usually be leached with a cyanide level of 600 - 1000 mg/L NaCN. Cyanide consumption via complexation, volatilization, natural oxidation, or oxidation by ore components typically ranges from 0.1 to 1.0 kg/t of ore. Cement and/or lime consumption ranges from 0.5 to 70 kg/t of ore. Several operations use cement for alkalinity control (instead of or in addition to lime) as well as for agglomeration.

### **Factors Affecting the Heap Leach Efficiency**

**Ore Type:** Heap leach recovery is dependent on the ore type being processed and its mineralogy. Some typical examples are;

  - Carlin-Type Sedimentary Ores
  - Low-Sulfide Acid Volcanics or Intrusives
  - Oxidized Massive Sulfides
  - Saprolites/Laterites
  - Clay-Rich Deposits
  - Silver-Rich Deposits

**Climate Extremes:** The effectiveness of heap leaching is heavily influenced by the climatic conditions of the operation area. In extremely cold conditions, the leaching solution could freeze, slowing down or even halting the leaching process. On the other hand, in very hot, arid climates, the solution may evaporate too quickly. Additionally, high rainfall can lead to excessive dilution or even washing away of the leaching solution. Hence, managing these climate extremes is crucial for maintaining heap leach efficiency.

**Heap Permeability and Flow Efficiency:** The permeability of the heap is a critical factor in heap leaching. It determines how easily the leaching solution can percolate through the heap. If the heap isn't properly constructed and the ore is too densely packed, the solution may not percolate efficiently, leading to lower extraction rates. In contrast, a heap that is too loosely packed may lead to preferential flow paths, meaning the solution flows too quickly through certain areas, reducing contact time with the ore and potentially decreasing extraction efficiency.

**Recovery Delay in Multiple Lifts Heaps:** In heap leach operations where multiple lifts (or layers) are used, there can be a delay in recovery as the leach solution needs more time to percolate through each lift. This can lead to longer recovery times and potentially lower overall efficiency. Moreover, if the leach solution becomes depleted in its reactive components (like cyanide in the case of gold leaching) in the upper lifts, it may not effectively leach the lower lifts.

**Solution Application Rate, Cyanide Strength, and Leach Time:** The rate at which the solution is applied, its cyanide concentration (in the case of gold and silver leaching), and the duration of leaching all impact the efficiency of the process. If the solution is applied too rapidly, it may not have enough contact time with the ore to fully react. On the other hand, too slow a rate could unnecessarily prolong the process. Similarly, if the cyanide concentration is too low, the reaction may not proceed efficiently, but too high a concentration can pose safety and environmental risks. The leach time should also be optimized to ensure maximum recovery of the valuable mineral.

### **Heap Leach Processing**

Mining of ore for heap leaching employs the same techniques and equipment as mining of ore to feed any other process method. Where uncrushed ore (run-of-mine (ROM) ore) is placed on the leach pad.

Ore preparation varies widely. ROM ore may be hauled from the mine and dumped directly onto the heap, generally material is crushed and agglomerated before placed to the pad, in some extreme situations dry grinding before agglomeration is applied. Ores high in clay (such as saprolites) are typically processed by two stages of crushing using toothed roll-crushers, then agglomerated in drums and stacked using a conveyor stacking system. Many ores are crushed and then either truck-stacked or conveyor-stacked without agglomeration. For these harder ores, crushing is usually done using a jaw crusher followed by one or two stages of cone crushing.

Where ores are nearly pure clays, drum agglomeration is usually employed. The ore is first crushed finely enough (typically 25 - 75 mm) to form particles that can be a stable nucleus for round pellets. Cement and water are then added and the ore is sent through a rolling drum. The fines and the cement form a high-cement shell around the larger particles, and the rolling action of the drum compacts and strengthens the shell.

As process requires longer residence times, one of the primary challenges in operating a heap is delay in metallurgical responce. With long leach times, the results of a change in operations will not be seen for months. A common mistake people make is to watch a heap on a day-by-day basis, which is an insignificant amount of time. It can be easily said that the most critical time in the construction of a multi-lift heap is the base lift of the heap, if the first lift is built poorly and has poor permeability or chemistry, this can have a lasting effect throughout the life of the heap.

### **FUNCTIONAL DESCRIPTION – MODEL**

Heap leaching is responsible for approximately 21 percent (3.9 million tonnes) of copper production and 9 percent (8.7 million ounces) of gold production worldwide.

Heap leaching requires many months and sometimes years to realize the ultimate expected metal extractions and translation of these values into recovered metal production. Along with in-heap inventory issues that are unique to the heap leach processes, it is particularly challenging to develop accurate metal production forecasts for heap leach projects. Accurate financial projections for heap leach projects rely upon the accuracy of metal production forecasts. Without accurate metal production forecasts, it is unlikely accurate cash flow projections will be developed for metal sales.

As time delays affects the outcome of the model, it is important to understand the terminology;

- **Extracted Metal:** Metal that has been leached from ore and is now present within the inventory of the heap pore solution or has been transported to the heap liner.
- **Recovered Metal:** Metal that has arrived at the heap at the heap liner in Pregnant Solution is then transferred to the metal production process.
- **Produced Metal:** Metal that is in saleable form.

The difference between recovered and produced metal corresponds to the delays and inefficiency in the overall metal production process.

Delayed extraction curves are generally not required if in-heap metal in solution inventory is accurately accounted for. For models that do not fully consider in-heap metal in solution inventory, delayed extraction curves should be applied.

Heap permeability and solution channeling is typically allowed for using scale-up factors or discount factors to reduce the rate and ultimate extent of metal extraction.

Complex phenomenological CFD models require significant processor capacity to run effective three-dimensional heap simulations. Typically, two dimensional simulations are adequate for most diagnostic, design, and optimization purposes.

The ability to generate accurate reagent consumption information depends on the type of operation — such as cyanide leach for Au/Ag, sulfuric acid leach for Cu, Zn, U — and the type, amount, and representativeness of testing information available.

Between the all differences in model types and their features, accuracy of the forecasting is the most vital parameter of the model.

### **AIRTH HEAP LEACH RECOVERY MODELING**

Airth Heap Leach Model will be a separate product represented within Airth ACT.

Model as the structure will be carrying features of Tier 3 Model with ability to calculate in-heap inventory changes via empirical formulas which rely on the assumptions along with considering delay times of the leaching process. The product is not a simulation tool but a single model which called as Recovery Model.

From the user interface perspective, the model will be divided into the sections below;

- Executive Summary: The table represents the actual and forecast/budget of the approved scenario, along with the interactive graphs showing the summary information.
- Scenario Analysis: The interactive table represents the outcomes of the scenario data for forecasting metal production. This section is specifically prepared for management to evaluate the possible scenarios and allow them to select the best one.
- Data Input: Most crucial section of the Heap Leach Model will be divided into four main categories;
  - Model Data Input: Actual and Scenario data from Mining and Processing Departments, which needs to be added on a scheduled basis.

Mine Department Actual Data can be uploaded thorugh CSV file or directly obtained from the Grade Control Block Model, Mine Department Forecast Data can be obtained directly from the Airth Plan and/or other Planning Software through Airth Connect; however, a CSV upload section also will be available for the client. Actual data will represent tonnages, grades, and assigned recoveries for the selected ore types. Scenario Data will be the outcome of the Airth Plan; however, the client will either push the data to the Heap Leach Model or upload it through a CSV file and will give a unique scenario name. Mine Department can upload as many scenarios as they like; however, the outcome of the model will not be represented until Processing Department decide their scenario inputs.

Therefore, a notification system will be applied and let Processing Department know when the Mine Department uploads a new scenario.

Therefore, Processing should upload their actual inputs through a CSV file. Then call the specific scenario via scenario name given by the Mine Department and decide scenario values. If client is utilizing a Metallurgical Accounting Software actual data can be directly obtained from accounting database. Snecario data will be manually put thorugh the user interface. Whenever "Complete Process Forecast" is clicked by the user, the model can carry the output to the Scenario Database, which carries some of the main parameters to the Scenario Analysis section for evaluation.

  - Metallurgical Data Input: Metallurgical test results to evaluate k-factor, solution inventory grade factor, and calibration. This section will be divided into two main sections.

    - Initial Tests: Initial metallurgical testwork is essential for the model and also for the process itself. Most of the companies generally perform standart column leaching test, which can give information on reaction kinetics.

Leaching often follows a first-order rate profile, however data might misleading when evaluating the rate reactions, since reaction rate may change during the time period. Therefore, Airth Heap Leach Model utilizes overall first rate kinetic constant while, showing the rate changes over time.

In principal, to calculate delay times and solution inventory factors client has to perform Cycle Base Column Tests and use the results for model input. However, most of the companies may not have these results, there fore in case the client does not have the related data Airth will provide two standart test results for a fast leaching ore and a slow leaching ore.

    - Metallurgical Tests: This section will be used for on going metallurgical tests, such as monthly basis column leach tests, weekly and monthly basis IBRT tests, daily percolation tests and Particle Size Distribution Tests. As Recovery Model prepared on a bench base testwork, result of these tests will give indication to the client the evaluate the calibration. Restul of the Metallurgical Tests will be represented in the Heap Leach Caliration Section.

  - Assumption Data Input: Section for the user to decide some of the main factors and constants for the model to be run in the first place.

  - Heap Leach Raw Data Summary: Table with visualization to check the inputs.

- Heap Leach Calculation Table: Represents all the raw, calculation, assumptions, model outputs in the one table for the to check to outcomes in detail with visualization for selected parameters.

- Heap Leach Model Calibration: Initial calibration methodology is prepared according to the Mean R-Square, which is trying to achieve minimum difference in meaning of Project to Date (PTD) firuges by changing;

  - K-factor by Ore Types
  - Scale-up Factor by Ore Types
  - Lab Factor

Difference between Actual Gold Produced and Modelled Gold Produced values should be;
    - Less than +/- 20% in monthly basis
    - Less than +/- 10% in yearly basis
    - Less than +/-1% in projected to date