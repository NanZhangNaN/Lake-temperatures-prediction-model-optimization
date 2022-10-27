# Lake-temperatures-prediction-model-optimization

LEAPCourse Climate Pred Challenges Project 2

Team members: Nan Zhang, George Lu, Charlie Sturr, Bryn Stecher

In the notebooks, we reproduced physics-guided deep learning models proposed in Read et al (2019) and Jia et al (2019). We use only the Lake Mendota data in the notebooks.

Both papers combine state-of-the-art deep learning models with strategies to incorporaate "guidance" from known physics that governs the dynamics of lake thermal stratefication.

In this project, we

- Evaluated and compared six long short-term memory (LSTM) models with three optimization algorithms and two types of learning rates, and found the model using dynamic learning rate and stochastic gradient descent (SGD) algorithm used the least running time while performing well.

- Analyzed the lake temperatures data on different depths of the lake and concluded that the temperatures at the bottom of the lake contribute much less in the model training part and can be removed without affecting the model performance too much.

- Optimized the existing LSTM model and concluded that the new model performed well while using less memory and less running time.

