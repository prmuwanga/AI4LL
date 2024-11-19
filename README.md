# AI4ALL
Computer Vision Project Proposal 

**Authors:** Primah Muwanga, Angelina Yang, Eniola Aloba

**Project Title:** Predicting the lifespan/freshness of produce in one’s refrigerator. 
Research question: How can computer vision technology, combined with knowledge of expiration dates and best by results, reduce consumer-level food waste?

**Sources of bias:**
The way some fruits and vegetables look and taste buds based on personal preferences
Cultural bias: varied definitions of expiration, different regions and cultures interpret expiration, best by and use by date differently. Some cultures may be more lenient towards consuming food past its labeled date, while others might be stricter.
Lighting and Image quality; real world usage of computer vision tools may be affected by environmental factors like lighting, camera resolution or angle, which could result in biases depending on the conditions in which images of the products are taken. 
Dataset to be used: Fresh and Rotten Classification

Github: GROUP GITHUB LINK

**Summary**
A report published by the United States Health Department of Agriculture’s (USDA’s) Economic Research Service estimates the amount of and value of food loss in the United States to be 31 percent at the retail and consumer levels, corresponding to approximately 133 billion pounds and $161 billion worth of food. As sustainability movements have become increasingly energetic in the 21st century, we hope to encourage more American households to be conscious of the food in their homes through further research in combining machine learning techniques with classification of fresh and rotten produce in one’s home, in order to help families more accurately discern and prevent edible food from being wasted. Our group chose Swoyam Siddharth Nayak’s “Fresh and Rotten Classification” dataset on Kaggle (Swoyam Siddharth Nayak, Fresh and Rotten Classification, 13 October, 2024, Kaggle, https://www.kaggle.com/datasets/swoyam2609/fresh-and-stale-classification), which provides a comprehensive database of common produce seen in the average household refrigerator.
The dataset contains a substantial amount of images with significant variations in lighting conditions, angles, and backgrounds in order to mimic real-world scenarios and challenges a model would face. Each dataset is carefully labeled with appropriate annotations indicating whether an item is fresh or rotten, enabling supervised learning and facilitating the development of our model’s classification accuracy. While in reality freshness is not explicitly labeled, we aim to focus on constructing our model to reach an accuracy well above 69% as a baseline comparison to the amount of fresh food that has not been wasted according to the USDA.

Type of machine learning algorithm(s) the group intends to use: Our dataset is annotated with labels indicating whether each item is fresh or rotten/stale, making it suitable for supervised learning and the development of classification models. The type of machine learning algorithm our group intends to use is Convolutional Neural Networks (CNNs). CNNs are a type of deep learning model specifically designed for image classification tasks. These networks utilize convolutional layers to automatically extract features from images, effectively handling variations in lighting, angles, and backgrounds. CNNs excel at image data because they learn spatial hierarchies of features—such as edges, textures, and patterns—without requiring manual feature extraction. By passing input images through a series of layers, CNNs progressively extract meaningful patterns, enabling accurate classification. Each layer captures increasingly complex aspects of the image, starting from simple edges and gradually identifying more intricate structures, such as shapes or objects.

**Challenges and Limitations:**
We understand that some challenges and limitations may be related to imbalance classes of fresh and rotten product during the supervised learning process as well as potential edge cases, such as internal spoilage. Our project plan is to evaluate the size and variety of training datasets, test incrementally, and engage with the broader AI research community for insights and support.

**citations:**
https://www.ers.usda.gov/webdocs/publications/43833/43680_eib121.pdf?v=0
https://www.usda.gov/foodwaste/faqs 
https://forskning.ruc.dk/en/publications/reducing-consumer-food-waste-using-green-and-digital-technologies 
https://www.emerald.com/insight/content/doi/10.1108/BFJ-05-2021-0545/full/html
