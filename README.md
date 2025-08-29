# BIO3014S

This is a 2 week module on "Space and Conservation" for the third year course _Conservation: Genes, Population & Biodiversity_ (BIO3014S).

### Module Outline:
The conservation of biodiversity is a wicked problem, but in the absence of perfect knowledge, we need pragmatic solutions. This largely boils down to the use of space. The prioritisation, allocation and management of geographic space, but also the use of tools that allow broad-scale mapping and monitoring of biodiversity and conservation actions, such as space-borne remote sensing platforms. This module of the course will explore how both meanings of space are used in global and local biodiversity conservation, including some advantages and limitations of these approaches.

### Learning outcomes:

By the end of the module, students should:

-  understand the concept, principles and goals of area-based conservation within the context of global biodiversity frameworks (e.g., Kunming–Montreal Global Biodiversity Framework, Aichi Targets),
- understand global conservation prioritisation tools and informants like the IUCN Red List of Threatened Species and Ecosystems, and how these are applied in South Africa,
- understand the principles of spatial conservation planning and how they are applied,
- know what remote sensing is, how it works, and how it can be used for mapping and monitoring biodiversity - especially with application to area-based conservation

Throughout, students should consider the challenges, trade-offs and opportunities of applying these tools and concepts at local versus global scales.

The module includes 8 lectures, a practical and a discussion of a journal article.

### Lectures (18-29 August 2025):

_Note:_ These are currently last year's lectures and will be updated as we go. They can be downloaded as .html files [here](https://github.com/PlantEcologi/BIO3014S/) by clicking on the file and then the download icon towards the top right corner.

1. [Space and Conservation](1_SpaceConservation1)
2. [Area-Based Conservation](2_AreaBasedConservation)
3. [Threat Assessment](3_ThreatAssessments)
4. [Remote Sensing of Biodiversity](4_RemoteSensingBio)
5. [Biodiversity Assessment and Planning – Practice and Policy](Skowno_NationaBiodiversityAssessment_UCT_20250822.pdf) - Guest lecture by Dr Andrew Skowno, South African National Biodiversity Institute
6. Discussion of [Gurney et al. 2023](https://doi.org/10.1016/j.oneear.2023.01.012). 
    - Please answer the questions in the [Google Form](https://forms.gle/PtAA4HzWHoLKG1R37) prior to the discussion. These answers and participation in the discussion count 20% of your mark for this module.
7. Mapping Marine Ecosystems - Guest lecture by Dr Ralph Watson, UCT (slides on Amathuba)
8. [Using spatial data to increase the impact of conservation action at The Nature Conservancy](Moncrieff_impacts_TNC.pdf) - Guest lecture by Dr Glenn Moncrieff, The Nature Conservancy
9. [Protecting Area in a World of Change](5_ProtectingArea)
10. [Revision/Reflection](6_Summary)

## Practical (18th August): Mapping biodiversity

We'll be using [***remap***](https://remap-app.org/) to play with mapping ecosystems using satellite remote sensing.

Ecosystems are one level in the hierarchy of biodiversity _sensu_ [Noss 1990](https://doi.org/10.1111/j.1523-1739.1990.tb00309.x), and is one of the foci for area-based conservation (versus a species focus). The exercise is aimed at giving you a soft introduction to mapping with satellite remote sensing and greater insight into many of the challenges faced and assumptions or pragmatic decisions required when mapping and monitoring ecosystems.

Remap is an online mapping platform for people with little technical background in remote sensing. It enables you to quickly map and report the status of ecosystems, contributing to the IUCN Red List of Ecosystems.

Read through the steps below and assignment instructions before getting started.

### Steps

1. Open [***remap***](https://remap-app.org/)
2. Go to "tutorials", open and read through PDF Tutorials 1 and 2
3. Select an area you know reasonably well that is about the size of the Cape Peninsula (e.g. the Cape Peninsula)
4. Follow the instructions from tutorial 1, but for your area and time set to "present" (this is important - see step 8)
  - We will have a discussion around how best to collect your training data. 
      - A key point of departure here is whether you choose your locations based on what you see in the high resolution imagery, versus known locations of a focal species of interest (e.g. using localities from www.iNaturalist.org or similar).
      - Other issues are that you need to select classes that cover the dominant variation in the image (e.g. even if you are not interested in water or built up areas, you should have these as classes to help the algorithm make sense of the imagery).
      - Note that you need a minimum of 20 (preferably 50) observations per class. If the algorithm fails with an error, it usually means you need more observations or an additional class (see previous point).
5. Colour your classes something sensible 
 - take a screen shot of your classified map ("Map 1" - for submission with your prac).
 - click "Results" and take a screen shot ("Results 1" - for submission with your prac)
 - set your classification to semi-transparent, pan around and see how well your classifier has done
6. Consider ways to improve your classification and address issues you noticed by 
  - altering or adding to your training data e.g. 
      - adding more observations per class
      - adding new classes (or merging similar classes)
      - using an imagery vs species-oriented approach
  - adding or dropping predictors
7. Rerun your classification with your altered training data and repeat the screen shots in step 5 ("Map 2" and "Results 2" - you can redo this step a few times until you feel you have a reasonable classification, but you only need submit your final map and results)
8. Now switch the time setting to "past". 
  - check that your training data points have not changed (e.g. many have have been transformed to human-altered land cover, or sand if it is an active dune landscape, etc) 
  - classify and take screen shots ("Map 3" and "Results 3")
  - compare present and past classifications with slider as per tutorial 2
9. Export your data as a JSON file labelled with your name



### Assignment

Please answer the questions below. Contextualise your answers by highlighting how they relate to the approach we adopted in this practical and illustrate them with examples from your analyses - e.g. where your classifier did well or badly or changed with different settings or training data (and embed your maps and results with captions where relevant - _**6 marks**_). 

1. What assumptions are required when using satellite remote sensing (SRS) to map ecosystems? (_**4 marks**_)
2. What are the potential drivers of uncertainty when using SRS to develop an ecosystem type classification? (_**4 marks**_)
3. What are the pros and cons of selecting your training data based on vegetation physiognomy (e.g. forest, shrubland, grassland, etc) versus the occurrence of focal species?  (_**4 marks**_)
4. What are the implications of the issues raised above for how and what we conserve?  (_**4 marks**_)

Each question is worth 4 marks and shouldn't be more than half a page (don't forget to illustrate your answers based on your results!!!). 6 marks are allocated for providing your figures and results with captions. An additional 2 marks will be awarded for providing appropriately cited and relevant references (and reference list). This brings the total mark allocation to **24 marks**. 6 marks come from your answers to the questions on the reading, resulting in 30 marks for the module.

Please provide your write-up as a ***PDF*** by the **29th August**. Please also submit your JSON file labelled with your name.
