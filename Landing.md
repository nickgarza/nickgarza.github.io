# Welcome to my (Work in Progress) Site!  
I am a current senior studying at Johns Hopkins University in Baltimore, MD, with majors in computer science and biomedical engineering. My past experience has largely been in the computational biology field, working with genomic data
and finding trends and indicators for cancer as well as cardiovascular disease. I hope to gain even more experience 
in the future with courses like Human Computer Interaction and Artificial Intelligence to develop applications. This space will serve mostly as my workspace for informal/independent projects that have no conflict with my university allowing me to share
source code.

A few private projects not listed on this page include:

## 1. Patient Scoot (Penn Apps XIX Project: https://github.com/tyang27/PennappsWinter19)
In the world of out patient care, it is crucial that highly skilled doctors be efficiently scheduled to maximize efficient care to patients. Unfortunately, many at risk patients have a high rate of no-showing for appointments and create scheduling chaos as a result. There has been much data collected on this phenomenon and it is an active field of research into optimizing scheduling.

Our solution takes inspiration from this field of research and the literature surrounding it, and proposes a scheduling system that takes patient record into account and schedules patients based on their risk of cancellation and no-show. Some factors we took into account were age, day of the week, health risks, previous cancellation record, and average time before cancellation. With this information, we created an index of risk based on a method proposed in a publication from Operations Research for Healthcare, "An analysis of overlapping appointment scheduling model in an outpatient clinic". We minimzed this risk and scheduled the patient accordingly to increase efficiency in healthcare settings.

## 2. Beeline
Beeline is an android application that seeks to create ridesharing groups to lower the cost of going from point A to point B(ee). It utilizes a firebase database to store user data, trips, and locations that they wish to go to. Our application was developed following agile methodology within a team of 4 computer science undergraduate students as the final project for User Interfaces and Mobile Applications. We held weekly scrum meetings and demoed our application twice to our class for feedback and improvement. I led development of the main page layout and UI shortcuts through search functionality as well as quick interest buttons.

## 3. Identification of Methylation Quantitative Trait Loci
DNA methylation is a key regulator of gene expression and as such has been thoroughly investigated in physiological studies. Our project used a data set from TCGA to investigate novel methylation effects in a diseased population of 1000 patients with the BRCA gene. We built a linear regression model relating methylation level and single nucleotide polymorphisms (SNPs) and also accounts for latent, biological, and technical confounders of the data extracted through cleaning. Our results identified notable association sites (BH corrected p < 0.05) between methylation and gene expression and were presented to our peers for feedback and review.


## 4. Rudimentary Photoshop: written in ANSI C without use of APIs or such.  
The photoshop-esqe tool allowed for grayscale, cropping, saturation, and channel swapping of the input photo.  
<img width="638" alt="garden" src="https://user-images.githubusercontent.com/28008631/42184759-9a39cdb4-7e14-11e8-86c2-473d76feda93.png"> <img width="635" alt="garden-swap" src="https://user-images.githubusercontent.com/28008631/42184770-a4e46580-7e14-11e8-8edc-8fe0c8c7b56e.png"> <img width="636" alt="garden-grayscale" src="https://user-images.githubusercontent.com/28008631/42184783-af1cebee-7e14-11e8-86d5-2ba514428d30.png">   


## 5. Chess: written in C++ without the use of APIs or such.  
The C++ chess game simulated a full game of chess until either a stalemate or checkmate was reached. Additionally, the chess game allowed the saving of a current game and the loading of previous matches.  
<img width="564" alt="chess-screen" src="https://user-images.githubusercontent.com/28008631/42184317-1dcf047a-7e13-11e8-90e1-a9f793188a1e.png">


## 6. Quorum Sensing Simulator: Python simulation modeled on Hill Equation.  
From Wikipedia:  
"In biology, quorum sensing is the ability to detect and to respond to cell population density by gene regulation. As one example, quorum sensing (QS) enables bacteria to restrict the expression of specific genes to the high cell densities at which the resulting phenotypes will be most beneficial. Many species of bacteria use quorum sensing to coordinate gene expression according to the density of their local population. In similar fashion, some social insects use quorum sensing to determine where to nest."
Our project was to create a model for a biological quorum sensing system. Essentially a "bacterium" will produce a protein (P) which produces an autoinducer(AI) which then feeds back and causes more of itself to be produced. We used the Hill equation to simulate this production and added necessary parameters to simulate responses over time (https://en.wikipedia.org/wiki/Hill_equation_(biochemistry)).
Within the realm of computing, quorom sensing has important relevance to feedback control in general for decision making within a decentralized system.
Our sample data to fit is included in this folder as a .csv file and running the .py script should generate plots of our model superimposed with the expected values.  
<img width="379" alt="p-results" src="https://user-images.githubusercontent.com/28008631/42185224-119a5684-7e16-11e8-8873-68e0cd0d3799.png"> <img width="387" alt="ai-results" src="https://user-images.githubusercontent.com/28008631/42185220-0f913632-7e16-11e8-9b40-ac01d8db9e37.png"> 


More information can be shared upon request through reaching me at my email: ngarza@jhu.edu

