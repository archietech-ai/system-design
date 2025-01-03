# system-design

### Visual Seacrh System

Problem statement: Finding an image that is similar to the selected image.


Model: It should be a network that supports images. CNN based architectures like RestNet and Transformer based architetcure like ViT can be used.

![image](https://github.com/user-attachments/assets/fd5ace62-c4a6-4602-b8c7-15ed00279c30)

#### Summary of design decisions

![image](https://github.com/user-attachments/assets/c87c34ad-77f0-4a8f-bf37-e677357e0393)

#### Simple Constrastive lost function

![image](https://github.com/user-attachments/assets/d5f24f2e-cb86-49f5-8b03-85e45f877021)



#### Simple System Design and Serving infrastructure 

![image](https://github.com/user-attachments/assets/c4439a23-75c2-4510-871c-8dcdd89b7d1a)


#### kNN decision points:

<b>Exact NN </b> : Searching the entire embedding space and calculating the distance of query with other embeddings. The time complexy is high (N x D) where N is the number of comparisons to compare and D is dimention of each embedding.







