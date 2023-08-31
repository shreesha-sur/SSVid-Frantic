# SSVid-Frantic
**Frantic fish behaviour dataset:**

![Sample-frame]<img src= "https://github.com/shreesha-sur/SSVid-Frantic/assets/91935551/e060a22a-5695-4a53-9b53-3f97ec191474" width="600" height="300">

**Description:**
The "Aquaculture Behavior and Water Quality Dataset" is a comprehensive collection of data aimed at studying fish behavior, particularly the frantic patterns exhibited by Sillago sihama and Tilapia species. This dataset is intended for research purposes only and encompasses various aspects of aquaculture, including behavior analysis and water quality prediction.

**Fish Behavior Dataset:**

Objective: The primary objective of this dataset is to detect and understand frantic fish behavior, characterized by sudden changes in swim direction and speed. This behavior is crucial in aquaculture, serving as an early indicator of fish stress. Detecting such behavior and implementing preventive measures can enhance harvest yields and promote sustainability in aquaculture practices.

Video Data: The dataset comprises a total of 16 videos, with 7 designated for training and 9 for testing. Each video ranges from 10 to 30 seconds in duration and is captured at a rate of 12 frames per second (fps). The objective is to classify each frame as "normal" (coded as 0) or "frantic" (coded as 1). Notably, all videos in the training set contain only normal fish behavior patterns, while the test set includes both normal and frantic behavior patterns.

Fish Species: The dataset primarily focuses on the behavior of wild-caught Sillago sihama and Tilapia species, providing valuable insights into their stress responses and swimming patterns.

![GROUNDTRUTH_5]<img2 src= "https://github.com/shreesha-sur/SSVid-Frantic/assets/91935551/b6963727-069b-4ec9-90bd-459251618da1" width="600" height="300">

Real Cage Scenario: Additionally, a separate set of videos collected from real aquaculture cages is included. This subset contains videos that feature both normal and frantic fish behavior. Researchers can use these videos to assess the performance of their models in real-world aquaculture scenarios.


**Water Quality Parameters Dataset:**

Objective: In addition to fish behavior, the dataset includes water quality parameters data, consisting of 7235 sample values for Temperature, Dissolved Oxygen, and Salinity. These parameters are sampled at 90-minute intervals, providing a comprehensive view of the aquatic environment. Figure below shows the plot of DO, Temperature and Salinity values. The dataset are tabulated in csv file.

![DO_plot]<img3 src= "https://github.com/shreesha-sur/SSVid-Frantic/assets/91935551/8e1aaa1d-07eb-4429-80cf-b1a2f1c53994" width="600" height="300">

![Temp_plot]<img4 src= "https://github.com/shreesha-sur/SSVid-Frantic/assets/91935551/62d7f025-e689-4aa2-912d-5024a36c6630" width="600" height="300">

![Salinity_plot]<img5 src= "https://github.com/shreesha-sur/SSVid-Frantic/assets/91935551/9b324db0-2297-464e-aef5-a30538375805" width="600" height="300">

Forecasting Models: Researchers can utilize this dataset to develop forecasting models for water quality parameters. Deep learning or hybrid models can be employed to predict changes in temperature, dissolved oxygen levels, and salinity, offering valuable tools for managing aquaculture environments and optimizing fish health.

In conclusion, the "Fish Behavior and Water Quality Dataset" is a versatile resource for aquaculture research, offering insights into fish behavior and the development of predictive models for water quality parameters. It serves as a valuable asset for enhancing aquaculture practices and promoting sustainability in the industry.
