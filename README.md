
# HeartSense

Chronic Heart Disease remains one of the leading causes of death around the world, and the major concern is arrhythmia, an abnormal heart rhythm, which can lead to severe health complications such as stroke, heart failure, and sudden cardiac arrest. Thus, the early and accurate detection of arrhythmia forms a crucial role in reducing risks by allowing timely medical intervention. This paper develops a comprehensive framework that integrates traditional clinical risk assessment with continuous physiological monitoring for early prediction of heart failure. This hybrid model, based on the integration of the Framingham Risk Score (FRS) and real-time electrocardiogram signal analysis, will give greater accuracy and timeliness in cardiovascular disease prediction using IoT.

An Arduino microcontroller is used connected with sensors, and it gathers real-time ECG and heart rate data. This data then undergoes two different machine learning models. One is the Random Forest Classifier for FRS analysis, and the other one is the EfficientNetB0 deep learning model for the interpretation of the ECG signal. The Framingham Risk Score is considered the groundwork for the conventional risk assessment, because it makes use of age, cholesterol levels, blood pressure, smoking history, and other parameters. Real-time ECG signals are, however, able to provide critical information regarding the electrical activity of the heart and point out potential abnormalities overlooked by the FRS model. The results obtained from each model are then averaged by a technique called weighted averaging in order to make the outcome stronger and predictive.

ECG will be measured by the use of AD8232 and heart rate by the MAX30102. This system will seamlessly interface with an Arduino microcontroller. The device will constantly transmit real-time data to a web application which would not only provide heart health insights for the user but also notifications and risk scores regarding possible heart failure. This integration hence allows for non-invasive, low-cost, and continuous monitoring while being more accessible for larger applications including resource-limited environments. Preliminary results show that this hybrid technique significantly improves the prediction of heart disease risks, bringing the ECG classification about 97% accuracy and 90% in the FRS model.

It fills in the gap between conventional risk assessment of cardiovascular disease and deep learning. This scalable, non-invasive, efficient early detection and monitoring solution of heart failure helps in active medical interventions and personalized care. Further work can involve more datasets, further physiological parameters, and better understanding of the model for much more extensive clinical applicability.

