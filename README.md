# Weather-net

Improve the prediction results of the numerical model in a way independent of the numerical model. (This will use history data) and use deep learning to do data assimilation.

The project comes from  the Thesis of my bachelor's degree. The core design idea of this project comes from the deep learning implementation of optical flow method. Then I made some preliminary improvements to this method after some experiments. This method does not assume that the data involved in the assimilation has no obvious unreasonable errors. It only effectively guarantees the consistency of the input data in some way, and the correlation is proved to be an effective means to ensure the consistency. 

The use of deep learning to complete data assimilation in meteorological science may be different from people’s understanding of data assimilation, but the reanalysis data that has been formed in the experiment, were proved to be able express observations better, especially on some variables, in some cases, compared to NCEP's reanalysis data.