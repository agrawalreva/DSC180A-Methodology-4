# DSC180A Methodology Assignment 4

**Name:** Reva Agrawal  
**Email:** ragrawal@ucsd.edu
**Section:** B15 
**Mentor:** Yu-Xiang Wang

---

**1. What is the most interesting topic covered in your domain this quarter?**  
One of the most interesting topics this quarter has been the connection between differential privacy and synthetic data generation. I found it fascinating how privacy-preserving mechanisms can allow data sharing without exposing individuals’ sensitive information. Learning about how noise injection, query release, and model-based synthesis techniques interact with privacy budgets and accuracy trade-offs has helped me better understand the implications of data privacy in research and industry.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For Quarter 2, we will be working with Intel telemetry data. A potential investigation I’d like to pursue is evaluating whether different levels of differential privacy can be applied to telemetry data without significantly affecting model performance. This could involve measuring how noise added to certain metrics impacts the ability to detect system anomalies or predict hardware failures while maintaining strong privacy guarantees.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
In our current project, we’re recreating synthetic medical data from a real dataset and comparing the inference results. One improvement could be to apply formal differential privacy mechanisms during the generation process rather than relying solely on distributional similarity. This would provide stronger privacy guarantees and help us quantify the privacy-utility trade-off in a more principled way. Additionally, incorporating evaluation metrics like membership inference risk could give a clearer sense of how private our synthetic data truly is.

**4. What other techniques would you be interested in using in your project?**  
I’m interested in exploring privacy-preserving machine learning methods, such as federated learning and private stochastic gradient descent, to complement our current differential privacy techniques. These approaches could be useful in settings where data can’t be centralized, such as medical or telemetry data collection. I’d also like to look into using generative models like diffusion models or VAEs for producing higher-quality synthetic data while maintaining differential privacy guarantees.
