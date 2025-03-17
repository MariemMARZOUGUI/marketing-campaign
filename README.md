# **Optimizing Marketing Campaign for a Restaurant in the Bay Area**
Project realised by M.MARZOUGUI and K.BEN AYED

## **Problem Reformulation**

As data scientists working at LinkedIn, we aim to optimize a marketing campaign for a restaurant located in the Bay Area. We have access to a dataset that includes a subset of LinkedIn users, detailing their locations, employers, and colleges. However, this data is incomplete, with 60% of the information missing. To accurately target individuals who can influence the campaign and promote the restaurant, we need to infer the missing data.

Our goal is to ensure we are targeting the right influencers who will have the most impact on the campaign's success.


### **Strategy:**

To meet our objectives, we will use the following strategies:

- **“Birds of a feather flock together” principle**: This principle suggests that individuals with similar characteristics tend to be geographically close. By leveraging this idea, we will infer missing geographical locations for individuals.
- **Machine learning models**: We will apply machine learning algorithms to predict missing data and optimize their parameters to improve accuracy.
- **Influencer selection**: We will calculate a score (ranging from 0 to 1) for each individual, based on a set of characteristics. The characteristics will be defined and weighted based on their importance, which will be determined after analyzing the statistics of the graph.
  
These methods will help us identify the most influential individuals in the Bay Area who can successfully promote the restaurant.

The final report represents a detailed description of our work.

The final result is provided in two different notebook:

- fill_empty_nodes: in which we worked on filling the empty nodes as our initial network was provided with missing data
- find_influencers: in which we developed the different algorithms applied on the final network to find the most influential individuals in the selected area




