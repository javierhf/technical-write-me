# Single-Responsibility Principle for Documentation Projects   
## Overview  

**According to Wikipedia the Single-Responsibility Principle (SRP) is:**  

> a computer programming principle that states that "A module should be responsible to one, and only one, actor."

**This term was created by Robert C. Martin who expresses the principle as:  

> A class should have only one reason to change".

The word "reason" caused some controversy within the community** so he had to provide further clarification say that the "principle is about people." He also added that the principle's focus is _roles_ or _actors_.   

!!! info "Info"  

    Learn more about [Single-Responsability Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle) in Wikipedia.    

    
## Roles in a Documentation Project  

**Documentation projects may include some of the following roles:** _subject-matter experts (SME), _collaborators_, _reviewers_, _translators_ and _managers_. Ideally we'll have a single persona fitting a single role (and responsibility) but we know that is not always possible.   

**In many developer documentation projects technical writers absorb multiple roles:** they are _reviewers_ (editors) and _managers_ at the same time. This allows other  _collaborators_ (developers, subject-matter experts, testers, Product Owners, etc.) to focus on their specific tasks. the where they provide more value.   

**That is one of the benefits of having a technical writer:**  your team memmbers can fixate their attention on their specialized tasks while the technical writer focus on converting the information into content.   

_How do we support this separation of responsabilities?_

## Single-Responsibility Principle for Developer Documentation  

**To support the single-responsibility principle in documentation projects** we can start by describing the ideas of _information_, content_ and _ownership_ as shown in the following table:   


| Concept | Description |  
|------------- | ------------------- |  
| **Information** |	Information is all the required introduction and instruction texts (steps), feature and code descriptions (library, parameters, snippets, endpoints, etc), screenshots and raw data that the collaborator provides as an _information draft_ with a basic structure.|  
| **Content** |	Content is the information after being transformed into a standardize user-center structure, layout and text formatting, following technical writing and UX best practices. layout and formatting.<br>As result, the time needed to find and understand the information decreases, while increasing the user experience. |  
| **Ownership** | 	Scope of tasks and responsibilities of each role keeping in mind that the documentation entails a _shared ownership_. |  

**Then we can define a minimum set of roles** and the scope of their responsibilities:  

| Role | Responsibility |  
| ------------- | --------------- |    
| **Collaborators** | Provide the information:<ol><li>which is correct</li><li>in the right order</li><li>in the right context.</li></ol> |  
| **Reviewers** |	Validate the information provided by collaborators when required. |  
| **Technical Writer** | <ol><li>Converts information into content.</li><li>Manages the ESG and the improvement processes and communication.</li><ol> |



     
