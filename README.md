# Transformer Explainability

- Implemented transfomer model, Explanability method Integrated Gradients (IGs) using TensorFlow
- Model is encoder only tranfomer developed for sentence level classification.
- First token of the sentence (\[START\]) is used for the classificaiton.
- Showed adapting IGs method usally applied for images to language model.
- Highlighted the words in the sentense contributed to the prediciton decision.
- This method can be adapted to any gradient based models.

  
![positive_explanation](images/positive_explanation.png)
<i>Above image shows, model predicted given sentense as positive with 98% confidence. Also IGs methos hilights `excellent` and `fascinating` are the two words contributed most to model prediciton as postive</i>
<br>
![negative_explanation](images/negative_explanation.png)

