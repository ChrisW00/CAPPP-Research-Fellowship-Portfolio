I have uploaded all necessary data files, but for my code to work you may need to download all the datafiles as I did some data wrangling in SPSS. I collected this trust data from the Axios/Ipsos Coronavirus Index weekly survey. In my project I am only utilizing survey waves 2-37 and am only using questions: Q12_1, Q12_2, Q12_3, v7, v8, v9, wave, ppage, ppeducat, ppethm, ppgender, ppincimp, ppstaten, QPID, xparty4, ppwork, PPWORKA, v12, Q14, and v10. The first six questions in this list ask participants to rank their level of confidence in local, state, and federal government on a scale of 1 (no confidence) to 4 (great amount of confidence). I created a public confidence ordinal index based on the individual combined average of these values as a way to gauge overall trust in government. This new variable is called “Trust_Ix”. The rest of variables included in this data are all things that I am controlling or am using for personal references. If you open one of the trust index files in SPSS, you will be able to view a codebook for most of the variables. Please note that I manually entered all the data from excel spreadsheets and PDFs into R for GDP, unemployment rate, median state government response, national covid deaths, and national covid cases. This information needed to be coded and grouped very specifically either by time or by state and there were numerous formatting issues that prevented a swift automated merge of the datasets. Please note that this project is not finished and there will be many more updates to this folder as I create a “clean” final copy of my dataset and analysis. Please check the “trust_index” folder for the most updated version of my dataset.  

 

# Sources  

Axios. (2021). Axios/Ipsos Coronavirus Index [Dataset]. Cornell University, Ithaca, NY: Roper Center for Public Opinion Research. https://ropercenter.cornell.edu/ipoll/search?collection=LSM&contains=SPSS&end=2021-02-01&org=30c1032b-fa6d-4c44-a3c0-6de23bf9e935&org=70f17464-83e1-4803-933a-a5c24ee7bd86&start=2020-03-20&tab=STUDY&topic=1f2f13b8-8249-4dd3-a980-5a1db99bf3d9.   

Dong, E., Du, H., & Gardner, L. (2020). An interactive web-based dashboard to track COVID-19 in Real time. The Lancet Infectious Diseases, 20(5), 533-534. doi:10.1016/s1473-3099(20)30120-1. 

Hale, T., Angrist, N., Goldszmidt, R., Kira, B., Petherick, A., Phillips, T., . . . Tatlow, H. (2021). A global panel database of pandemic policies (Oxford Covid-19 Government response tracker). Nature Human Behaviour, 5(4), 529-538. doi:10.1038/s41562-021-01079-8.  

Labor Force Statistics from the Current Population Survey Seasonally Adjusted Unemployment Rate [xlsx]. (2022, January 07). Bureau of Labor Statistics. 

Table 1.1.3. Real Gross Domestic Product, Quantity Indexes [PDF]. (2022, January 27). Bureau of Economic Analysis. 
