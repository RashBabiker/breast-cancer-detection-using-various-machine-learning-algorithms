# Breast cancer detection using various machine learning algorithms

I have used breast cancer data that includes measurementsof digitised fine needle aspiration images of a breast mass. The values represent features of the cell nuclei present in the digital image.

With this data I have predicted the malignancy of tumours with different machine learning methods and calculated its accuracy by comparing it with expert annotations.

The best algorithm for classifying tumours is the random forest method, which is difficult to interpret, but effective. The decision-making algorithm is a little less accurate, but maintains sensitivity, so it could be used to make a guide for doctors analysing cells under the microscope to get an idea of the severity of the tumour; personally I do not recommend it, because the decision making is a little less accurate, but maintains sensitivity. I do not recommend it personally, because the data collection involves taking a biopsy of the breast tissue, so it is already suspected to be malignant. might be useful in other circumstances, but not in this one. In addition, once the samples have been taken the random forest could classify them in less than two minutes, certainly less time than it would take the doctor to follow the the dichotomous key, and more accurate.

For all these reasons, and as a conclusion, the random forest algorithm is recommended for this task, because, although we cannot easily follow the process by which it makes the decisions, it is the one that makes the fewest mistakes in predicting data with the data that is predicting data with which it has not been trained.

The code is written in R with bioconductor packages, the comments are written in Spanish, if you need a translation or have any questions please contact me at rashbabiker@gmail.com
