# Final Project - Artificial Intelligence Course (Prof. Tan Ghatari)  
Sharif University of Technology, Tehran  

## Team Members
- Taha Izadi (402110543)  
- Arash Ghavami (402106359)  
- Mohammad Ebrahimian (402110905)  

---

## Phase 1: U-net  
In this part of the project, a specific convolutional neural network called **U-net** and its variants (**Attention U-net & Residual U-net**) are implemented.  
The purpose is **pixel-wise classification** of images, allowing different segments of an image to be separated.  

Implementation is done using several Python libraries (especially **PyTorch**) and trained on a dataset available on **Kaggle**.  

Additionally, four fundamental questions about U-net are discussed:  
1. A complete explanation of the U-net architecture  
2. Explanation of the loss function used  
3. Other applications of U-net and loss functions commonly used in them  
4. The role of skip connections in this network  

📹 [Video link for Phase 1](https://drive.google.com/file/d/1YPRM50tBRRimvfEBc_0SscFqU26VdNU_/view?usp=sharing)  

---

## Phase 2: Soft Actor Critic (SAC)  
In this phase, an agent interacts with an environment using **Reinforcement Learning** via the **Soft Actor Critic (SAC)** method.  
The agent learns to reach an optimal policy based on its objective function, and the implementation is carried out graphically using the **Gymnasium** library.  

Four fundamental questions about SAC are discussed:  
1. A complete explanation of the Soft Actor Critic algorithm  
2. What is the role of entropy in SAC’s final objective?  
3. By repeatedly applying the soft Bellman operator on the Q-function, what value does the Q-function converge to?  
4. In SAC, the optimal policy distribution takes the form of a softmax over Q-functions.  
   However, why do we still train a separate policy network?  
   What is the policy loss function and why is it formulated this way?  

📹 [Video link for Phase 2](https://drive.google.com/file/d/1fj5yPQUQH7QXaMpj9nTaeaXmRj02gCbq/view?usp=sharing)  
