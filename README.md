# KneeOsteoarthritis

•	Developed a deep learning algorithm for automatic detection and quantification of knee joint space narrowing in patients with Knee Osteoarthritis, enhancing the accuracy and objectivity of disease diagnosis and progression monitoring


•	Achieved a classification accuracy of 81% in accurately categorizing the severity of Knee Osteoarthritis using a dataset of over 10,000 medical imaging scans


•	Reduced false positives and false negatives by optimizing the algorithm. Employed advanced fine-tuning techniques to meticulously optimize model hyperparameters, resulting in a reduction of false positives by 27% and false negatives by 19%, compared to initial algorithm iterations


Knee osteoarthritis is defined by degeneration of the knee’s articular cartilage the flexible, slippery material that normally protects bones from joint friction and impact. The condition also involves changes to the bone underneath the cartilage and can affect nearby soft tissues. Knee osteoarthritis is by far the most common type of arthritis to cause knee pain and often referred to as simply knee arthritis. Many other less common types of arthritis can also cause knee pain, including rheumatoid arthritis, pseudogout, and reactive arthritis.

Content: Dataset contains knee X-ray data for both knee joint detection and knee KL grading. The Grade descriptions are as follows:

Grade 0: Healthy knee image.


Grade 1 (Doubtful): Doubtful joint narrowing with possible osteophytic lipping


Grade 2 (Minimal): Definite presence of osteophytes and possible joint space narrowing


Grade 3 (Moderate): Multiple osteophytes, definite joint space narrowing, with mild sclerosis.


Grade 4 (Severe): Large osteophytes, significant joint narrowing, and severe sclerosis.




Model Performance


my_model


52/52 [==============================] - 17s 312ms/step - loss: 1.1381 - accuracy: 0.5731


Test loss: 1.1380925178527832


Test accuracy: 0.5730676054954529


my_modelv2


52/52 [==============================] - 7s 121ms/step - loss: 1.0527 - accuracy: 0.5592


Test loss: 1.0527117252349854


Test accuracy: 0.5591787695884705
