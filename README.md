# Project description

Our best estimates show there are over 7 billion people on the planet and 300 billion stars in the Milky Way galaxy. By comparison, the adult human body contains 37 trillion cells. To determine the function and relationship among these cells is a monumental undertaking. Many areas of human health would be impacted if we better understand cellular activity. A problem with this much data is a great match for the Kaggle community.

Just as the Human Genome Project mapped the entirety of human DNA, the Human BioMolecular Atlas Program (HuBMAP) is a major endeavor. Sponsored by the National Institutes of Health (NIH), HuBMAP is working to catalyze the development of a framework for mapping the human body at a level of glomeruli functional tissue units for the first time in history. Hoping to become one of the world’s largest collaborative biological projects, HuBMAP aims to be an open map of the human body at the cellular level.

This competition, “Hacking the Kidney," starts by mapping the human kidney at single cell resolution.

Your challenge is to detect functional tissue units (FTUs) across different tissue preparation pipelines. An FTU is defined as a “three-dimensional block of cells centered around a capillary, such that each cell in this block is within diffusion distance from any other cell in the same block” (de Bono, 2013). The goal of this competition is the implementation of a successful and robust glomeruli FTU detector.

You will also have the opportunity to present your findings to a panel of judges for additional consideration. Successful submissions will construct the tools, resources, and cell atlases needed to determine how the relationships between cells can affect the health of an individual.

Advancements in HuBMAP will accelerate the world’s understanding of the relationships between cell and tissue organization and function and human health. These datasets and insights can be used by researchers in cell and tissue anatomy, pharmaceutical companies to develop therapies, or even parents to show their children the magnitude of the human body.

# Exploratory analysis
## Data structure
The data consist of 13 images ranging from 20k to 40k pixels width/height in tiff format. For each one of them we are given information regariding the resolution of the image, the race, etnicity, sex, age, weight, height, bmi, of the patient. Also, which kidney (left or right) is included. Finally, the data also includes the percentage of sample surface corresponding to two kinds of tissue, cortex or medulla. As we will see later, glomeruli are found almost exclusiely in the cortex.


![All Samples](figures/all_samples.png)

![All Samples](figures/all_samples_cortex_glom.png)

# Approach
# Results