When looking at the Detailed Results, it is interesting to note that BERT is not clearly performing better than the GPT-3 models.
However, GPT-3 is regularly performing on par with BERT or even better in the case of **Obama Care** where the BERT approach
wrongly classified an input element as a decision which the GPT-3 models did not.
The only case in which GPT-3 really performed poorly is the **Fraud Rating Score** which is a technical description of how
to calculate a fraud rating score.
None of the GPT-3 models were able to correctly identify the relevant concepts,
but instead identified a lot of concepts (high number of _#pred_ values) and linked them together without
a clear reasoning behind it. Regarding the **Student AID US** example,
the main reason why the GPT-3 models are not performing on par with the BERT approach is because
the golden standard identified _legal resident_ and _US Citizen_ as two separate input elements whilst
GPT-3 merged these two together.
