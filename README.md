# ESSNET Big DATA II 2018-2020

The “ESSnet on Big Data II - 2018-2020” is the envisaged successor to the “ESSnet Big Data I” that existed from January 2016 to May 2018. The ESSnet Big Data II will build on the results of the ESSnet Big Data I.

The overall objective of the ESSnet Big Data II is to further prepare the ESS for integration of big data sources into the production of official statistics. The strategic, practical and urgent need for this is explained in the Scheveningen Memorandum and the Big Data Action Plan and Roadmap. Given the nature and diversity of big data sources, this objective requires research into the possibilities of and impediments to using these sources. Thus, the previous ESSnet investigated aspects of data access, processing and dissemination including in particular conditions for access and use, the development of methodology, quality and technology, and the production of experimental outputs. These aspects were looked at for the specific data sources and domains of the pilots, and at a more general level to identify communalities and good practices


The ultimate goal is to have actual implementation of big data sources into the production of ESS statistics. The research outcomes of the previous ESSnet allow this step to be taken for several of the big data sources and domains, but not yet for all. Moreover, several other potentially relevant big data sources have not been investigated yet for the ESS, therefore there is a need to continue with doing research next to starting with the actual implementation of earlier results. This will, once again, be carried out in the form of pilot projects, as this approach has been shown to be effective in the previous ESSnet.
In total 28 ESS members have expressed interest in participating in the ESSnet.

Four new pilot projects will be carried out, resulting in experimental statistics. They concern (1) use of financial transactions data, (2) use of remotely sensed data (e.g., satellite images, in-situ measurements, etc.), (3) use of mobile network operator data and (4) use of innovative sources and methods for tourism statistics.


## WPI Mobile Networks Data
The main objective of the WPI on mobile phone data is to carry out the construction of a production framework already initiated in the former ESSnet on Big Data. A modular instead of a linear approach will be followed both to avoid potential blockings in the research due to the obstacles in accessing real data and to optimally develop the different elements in the production framework. The modular approach will enable the project to concentrate on many different aspects of the framework as the data access itself and the relationship with Mobile Network Operators, both the methodological and IT elements (thus also enabling the identification of necessary skills and capabilities), quality issues as well as proposals for standards and related metadata and dissemination aspects of statistical products (mainly visualization thus orienting the outputs towards stakeholders). As a novelty, the use of instrumental (semi-simulated) data closely resembling real data (when these are not accessible) will be used in this line of work. All in all, the ultimate goal is to push forward an ESS production framework with mobile phone data aiming at a standardised statistical production process.

### Description of work
Before describing the planned work it is important to explicitly formulate the difference between those data sets we aim to process: microdata and aggregate data. The former are data at the mobile device level, either coming from Call Detail Records (CDRs) or from signalling data. The latter are aggregation of microdata (e.g. number of detected mobile devices) in each territorial cell and in a give time period. These data sets, according to our experience, will have to be complemented with technical information about the network (antennae position and others).
The work plan for this WP builds on the results already achieved in the former ESSnet on Big Data. As stated above, a modular approach will be followed. We propose to develop 8 tracks. They are not completely independent, but play a clear distinctive role in the overall strategy. They are:

1. Access.
2. Instrumental data generation.
3. Methodology.
4. Information technologies (IT).
5. Standards and metadata.
6. Quality.
7. Application to data.
8. Visualisation.

The foreseen contents of each track are provided in detail below.

### T1. Access
Access to data is still one of the major goals for this sort of data. Negotiations and agreements with MNOs must still be pursued and the conditions under which access will be granted are a clear objective for the project and the whole ESS. As analysed in the former ESSnet, there is a number of issues to be overcome (legal issues, extraction and preprocessing costs, risk perception…). One of the main conclusions of the former experience in the ESS is that MNOs will ineludibly be part of the statistical production process in the initial stages of data collection and data preprocessing. This is clearly in line with the Reference Methodological Framework for Mobile Network Data proposed and promoted from Eurostat.

### T2. Instrumental data generation
This is an intermediate instrumental task gathering necessary steps at other parts of the research. Firstlly, this instrumental data with similar structure and format to real data (taking advantage of our knowledge on them) will play the role of real data while access to these has not been reached. This will avoid blocking the research because of the lack of data. Secondly, these data will assist in the assessment of the economics regarding data access and its many aspects such as the analysis of costs/benefits for MNOs in granting access to different types of data or the technological issues regarding the preprocessing of these different types of data. Thirdly, they are necessary to assess statistical models in the inference stage or, in the case of microdata simulation, to assess geolocation routines or spacetime interpolation methods (see below). In particular, quality assessment (in terms of bias, variance, and model goodness of fit) will clearly benefit from these instrumental data. Finally, they will also provide an extraordinary framework for reproducibility of the results.
These instrumental (semi-simulated) data are not the target per se of the research. They will play the role of real data whenever real data are not available, apart from the quality assessment and reproducibility framework (where they are needed). Simulating whole population values will be a central part of this task; otherwise the instrumental value will be very low. The need for both methodology and IT tools is thus clear.


### T3. Methodology
As a result of the former ESSnet, several methodological key points were identified needing further (indeed constant) research. In the line of the Reference Methodological Framework cited above, the two-phase life-cycle model used in administrative data was proposed in the deliverables of the former ESSnet as a tool to understand the generation of these data as well as the identification of error sources. More recent proposals in the realm of admin data are also suitable for this framework under this view. This must provide an overall understanding of the whole production process. Additionally, the geolocation of events (thus the spatial attributes of the statistical units) and the inferential stage (going from data to the target population) are two key steps in this process.

### T4. Information technologies
The production of software solutions is an explicit goal of the WP. To provide a fairly enough number of IT tools they should be able to be developed in parallel. A modular approach providing solutions for different elements of the production framework developed in the track on methodology (software solutions for quality issues are put off to later tracks) will be followed. Based on the experience with the former ESSnet we underline that these solutions are usually better developed along with the methodology.

### T5. Standards and metadata
The production of official statistics with mobile network data is a new process in the ESS. Thus, it requires new standards and metadata. Furthermore, the modular approach in different steps of the process requests that these modules must interact with each other in a transparent way to make them functionally modular. This is the role of standards and metadata gluing all pieces together.

### T6. Quality
In this track, both methodology and IT aspects are to be treated in a combined way to focus on quality aspects. The ultimate goal in this track is basically to address the quality of the process as a whole and of each element.

### T7. Application on data
This track shall concentrate on the application of all previous work to real data. As activities, in a natural way, we propose the application of each element of the production framework to the set of real data under analysis.


### T8. Visualisation
The final track focuses on the dissemination of results and the orientation of the whole framework, especially for partners in the ESS and stakeholders in general. Every stage in the preceding production framework must be completed with a visualization layer. Moreover, the website on Github devoted to the software tools developed during the former ESSnet is planned to be slightly refurbished and completed offering a view of the whole process and guiding the user through the different elements.




# ESSNET BIG DATA I 2016-2018 

## General Objectives

The ESSnet BIG DATA I was part of the Big Data Action Plan and Roadmap 1.06 (BDAR below) and it was agreed to integrate it into the ESS Vision 2020 portfolio. The related business case Big Data received the support of the ESSC at its meeting on 20 June 2015 in Luxemburg.
The overall objective of the project was to prepare the ESS for integration of big data sources into the production of official statistics. The award criteria mentioned that the project had to focus on running pilot projects exploring the potential of selected big data sources for producing or contributing to the production of official statistics. Aim of these pilots was to undertake concrete action in the domain of big data and obtain hands-on experience in the use of big data for official statistics.
Taking into account these objectives, this ESSnet was meant to go from exploration to exploitation of big data for official statistics. This showed the difference of this European-funded international big data project compared to more scientific and policy-making projects in the domain of big data. It also clarified the choices of activities which are included in this ESSnet or not.

During the first part of the project a consortium of 22 partners, consisting of 20 National Statistical Institutes and 2 Statistical Authorities has been formed in September 2015 to meet the objectives of the project. According to the Framework Partnership Agreement (FPA) between the consortium and Eurostat, the project run between February 2016 and May 2018. To concentrate the work as much as possible on the pilots, the consortium had organised its work around the pilots. More specifically, the consortium has subdivided its work into the following work packages:
WP 0 : Co-ordination
WP 1 : Webscraping / Job Vacancies
WP 2 : Webscraping / Enterprise Characteristics
WP 3 : Smart Meters
WP 4 : AIS Data
WP 5 : Mobile Phone Data
WP 6 : Early Estimates
WP 7 : Multi Domains
WP 8 : Methodology
WP 9 : Dissemination

## WP5 Mobile Phone Data for Official Statistics

The aim of this workpackage was to investigate how NSIs may obtain more or less ‘stable’ and continuous access to the mobile phone data. In the current situation, most NSIs face complications to get access to these data due to legal, privacy and contractual issues. On the other hand, the potential of mobile phone data as a data source for official statistics is beyond any debate. 
This workpackage describes concrete statistical outputs – relevant for official statistics – based on mobile phone data (and previous studies) and discuss the pro’s and con’s of using aggregated or microdata from mobile phone providers for these actions. The 1st year of the action was used to get access to the data based on this plan. Challenges ahead are: data access, representativity issues, linking to other datasets, linking the outputs to other statistical estimates.


### Statistical outputs
The first part of the project was focused on data access. In the second part of the project, the main statistical output was the population dynamics in several stages:

* For a sub-municipal partition of the territory and an intra-day time division we produced a distribution of the population. The grain of these partitions was decided according to a preliminary analysis of the diverse data sets seeking for maximum comparability.
* The computation of these distributions was also conducted according to a classification of population in terms of concepts of interest: tourist/non-tourist, commuter/non•commuter,... These concepts were chosen according to the preliminary analysis of the data sets.
* These distributions werew completed with mobility matrices expressing how population moves among the territorial grids in the successive time divisions.

The goal of this work package was not these statistical outputs per se but to use them as a vehicle to assess the necessary statistical methodology and technological requirements to obtain the results together with an evaluation of the adequacy of the common data quality framework for Official Statistics.

### Statistical methodology. IT requirements and data quality

Regarding the methodology the three aspects of greater interest were:
* the presumably novel statistical methods to perform the classification of units using mobile phone data possibly combined with some other Official Statistics sources and/or outputs (Census, Population Registers, etc.);
*	the inference problem connecting the mobile data set sample with the whole population of interest;
*	the accuracy of the estimations for the population of analysis.

Once the statistical methodology was assessed, in close connection we identified the technological requirements to implement this analysis. In particular, we identified:
* needs for distributed computing; 
* special needs for data storage; 
* novel needs for software.

The quality of the statistical outputs was also evaluated with a double purpose:

* to assess the quality of the novelties in the statistical production, both from the point of view of the process and of the product; 
* to assess the adequacy of the common quality framework for this new source of data.

### Future perspectives

The final phase of the work package was accounted crosssectionally, i.e. all findings in each task were correspondingly assessed in terms of their immediate and future applicability under standard production conditions within the ESS.

As part of the future perspectives, we analysed those conditions in each task related to international comparability, data sharing among NSls and sustainability of sources for production in the long term.

The reporting was undertaken with two simultaneous generic goals: (i) to clearly report about each detailed step necessary to produce the statistical outputs and (ii) to produce clear guidelines for all members within the ESS in the verge of using mobile phone data for their production.


