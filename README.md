# Transformer Explainability

- Implemented a Transformer model and integrated the explainability method Integrated Gradients (IGs) using TensorFlow.
- Developed an encoder-only Transformer for sentence-level classification.
- Utilized the first token of the sentence (\[START\]) for classification purposes.
- Demonstrated the adaptation of the IGs method, typically applied to images, to a language model.
- Highlighted the words in the sentence that contributed to the prediction decision.
- This method is adaptable to any gradient-based models.

  
![positive_explanation](images/positive_explanation.png)
<i>The above image shows that the model predicted the given sentence as positive with 98% confidence. Additionally, IG's method highlights that `excellent` and `fascinating` are the two words that contributed most to the model's prediction as positive.</i>
<br><br><br>
![negative_explanation](images/negative_explanation.png)
<i>The above image shows that the model predicted the given sentence as negative with 98% (1 - 0.018) confidence. IG's method explained the model prediction by highlighting words (in pink) that contributed to the negative prediction.</i>

## Integrated Gradients(IGs):

