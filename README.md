# AE-improved
We carefully analyzed the characteristics of AE-pub, and we have defined 11 entity types for e-commerce scenarios: gender, time, style, material, color, category, scene, brand, size, object and other. 
Then we manually annotate 10,000 attribute types in the AE-pub dataset.  
We use the current SOTA model W2NER to train these data, automatically label the remaining data with trained model, and then we conduct manual correction. 
Finally, we get all the attribute entity types. We refer to this dataset as AE-improved in our experiments. 
