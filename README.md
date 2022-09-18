# GPT-3-Research-Project
I work with the Davinci model in GPT-3, an autoregressive language model, to answer middle-school science textbook questions in the textbook question answering (TQA) dataset. The dataset was split into training, test, and validation sets. In this task, I simulate a student taking a test in three different scenarios. First, the Zero-Shot-Learning experiment where I only provide the model with the questions from a specific lesson. This would be the equivalent of a student going into a test without studying as the model has not gathered any knowledge from the lesson. Second, the Few-Shot-Learning experiment, where I provide the model with specific lesson content from the textbook and the corresponding questions. This equates to a student skimming over the lesson content before taking the test. Lastly, I fine-tuned the Davinci model on some of the textbook questions and then fed it questions. This is similar to a student doing a thorough review of the material before taking the test. After conducting all three experiments, I compare their accuracies and in doing so, highlight the “intelligence” and limitations of GPT-3. 
