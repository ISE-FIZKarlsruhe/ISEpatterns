# Good practices, tips and tricks
Developing an ontology is more than just listing terms and relationships; it requires a strategic approach that balances rigor with flexibility, and precision with usability.

Let's collect the **good practices** that guide ontology development, providing insights and actionable advice for us practitioners. From understanding the domain and engaging stakeholders to ensuring maintainability and alignment with established standards, these principles help ensure that your ontology is both robust and effective. By following these practices, we can create ontologies that not only meet current needs but also adapt gracefully to future challenges.


## General Resources

Here are some general resources everyone should pay attention on:

* some general [Onto-Tipps](https://douroucouli.wordpress.com/2019/03/09/ontotips-a-series-of-assorted-ontology-development-guidelines/)
* [Blog of Maria Keet](https://keet.wordpress.com/)
* [BFO Classifier](https://keet.wordpress.com/2023/06/29/improved-the-bfo-classifier/) from Keet Blog
* [Robot Utility](https://robot.obolibrary.org/) and [ODK](https://github.com/INCATools/ontology-development-kit)
* for absolute beginner colleagues or for a Protégé refresh: [the pizza tutorial](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial)

# Reuse Concepts (Lookup Services) 

Reusing concepts in ontologies promotes interoperability, consistency, and efficiency. By adopting well-established concepts from existing ontologies, you align with widely accepted standards, facilitating integration with other systems and datasets. Reuse also saves time and effort, reducing redundancy and leveraging the expertise embedded in proven ontological models. Additionally, it supports data sharing and reasoning by ensuring that shared terms have consistent meanings across different contexts.

Here are some lookup services, where you can find concepts and ontologies which you can reuse:

* Ontobee [https://ontobee.org/](https://ontobee.org/)
* OLS [https://www.ebi.ac.uk/ols4/](https://www.ebi.ac.uk/ols4/)
* TIB-Terminology Service [https://terminology.tib.eu/ts
](https://terminology.tib.eu/ts)
* Linked Open Vocabularies [https://lov.linkeddata.es/dataset/lov/](https://lov.linkeddata.es/dataset/lov/)


# Avoid Poly-Hierarchies and follow the Role-Pattern

Polyhierarchies—where a single concept has multiple parent concepts—can make ontologies more complex and harder to manage. They can lead to ambiguity in reasoning processes, complicate maintenance, and introduce challenges in ensuring consistency across the ontology. While sometimes necessary for representing certain domain realities, avoiding polyhierarchies when possible helps maintain clarity, improves computational efficiency, and simplifies navigation and interpretation.

Here is a [more detailed explanation](https://douroucouli.wordpress.com/2019/06/29/ontotip-learn-the-rector-normalization-technique/) and a method (Rector Normalization) to avoid poly-hierarchies.


