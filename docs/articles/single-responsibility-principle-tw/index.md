---
title: Single-Responsibility Principle for Documentation Projects   
status: new
---   

# Single-Responsibility Principle for Documentation Projects     

## Overview  

**According to Wikipedia the Single-Responsibility Principle (SRP) is:**  

> a computer programming principle that states that "A module should be responsible to one, and only one, actor."

**This term was created by Robert C. Martin** who expresses the principle as:  

> "A class should have only one reason to change".

**The word "reason" caused some controversy within the community** so he had to provide further clarification saying that the "principle is about people." He also added that the principle's focus is _roles_ or _actors_.   

!!! info "Info"  

    Learn more about [Single-Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle) in Wikipedia.    

    
## Roles in a Documentation Project  

**Documentation projects may include the following roles:** _collaborators_, _editor_ (reviewers), _technical writers_, _translators_ and _managers_. Ideally, we'll have a single person for each role.   

**Lucky for us we have technical writers, a role that absorbs many of the previous roles:**  

* They edit the collaborations from other team members  
* They manage the documentation project and platform  
* They collaborate with new content actively    
  
**Having a technical writer allows your collaborators (Subject-matter experts)** to focus where they provide more value:
> While they provide a draft with the right information, the technical writer creates the content.  

But _how do we apply and support this separation of responsibilities?_

## Single-Responsibility Principle (SRP) for Documentation Projects

**It seems simple but applying the SRP to documentation projects requires a little change** in the product team's mindset:  

* Now they will provide the information  
* The technical writes will create the content  

### Key Concepts  

**Applying the SRP to documentation projects** requires the key concepts described in the following table:   


| Concept | Description |  
|------------- | ------------------- |  
| **Information** |	<ul><li>Information consists of all pieces of text, screenshots and raw data provided by collaborators.</li><li>Pieces of text can be introduction, process steps, features, and code descriptions (library, parameters, snippets, endpoints, etc).</li><li>Pieces of text are provided as a draft with a basic structure.</li></ul>|  
| **Content** |	Content is the information after being standardized. Standardized information reflects the style guide and the technical writing best practices. |  
| **Shared Ownership** | Every page is the result of team collaboration, so the team owns the documentation. |  

**Keeping this concepts in mind** we can define the following roles and their responsibilities:  

| Role | Responsibility |  
| ------------- | --------------- |    
| **Collaborators** | Provide information which:<ol><li> is correct</li><li>is in the right order</li><li>is in the right context.</li></ol> |  
| **Reviewers** |	Validate the information provided by collaborators when required.|  
| **Technical Writer** | <ol><li>Converts information into content.</li><li>Manages release process.</li><ol> |    

## Conclusion

**This is the new mindset: assigning a limited and specific set of tasks**, for all the roles participating in the documentation workflow, to ensure we all add value where we have to.  

The Single Responsibility Principle (SRP) for documentation projects changes the idea of documentation ownership. We will not have _individual ownership_ anymore but an idea of _shared ownership_.   

Now that all the documentation roles contribute to the final documentation: _we all own the docs!_.  

This idea of _shared ownership_ may be not easy to accept for everyone but the technical writer can reduce any possible friction with an effective communication strategy.



     
