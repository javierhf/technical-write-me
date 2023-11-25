---
title: Single-Responsibility Principle for Documentation Projects   
status: new
---   

# Single-Responsibility Principle for Documentation Projects     

## Overview  

**According to Wikipedia the Single-Responsibility Principle (SRP) is:**  

> a computer programming principle that states that "A module should be responsible to one, and only one, actor."

**This term was created by Robert C. Martin** who expresses the principle as:  

> A class should have only one reason to change".

The word "reason" caused some controversy within the community** so he had to provide further clarification saying that the "principle is about people." He also added that the principle's focus is _roles_ or _actors_.   

!!! info "Info"  

    Learn more about [Single-Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle) in Wikipedia.    

    
## Roles in a Documentation Project  

**Documentation projects may include the following roles:** _collaborators_, _editor_ (reviewers), _technical writers_, _translators_ and _managers_. Ideally, we'll have a single person for each role, but we all know the truth: _the real world does not work like this_.   

**Lucky for us we have technical writers, a role that absorb many of the previous roles:**  

* They edit the collaborations from other team members.  
* They manage the documentation project and platform.  
* They collaborate with new content actively.    
  
**Having a technical writer in your team** allows  _collaborators_ (developers, subject-matter experts, testers, Product Owners (POs), etc.) to *focus where they provide more value*. In other words, after providing new information, developers can focus on coding, testers in testing and POs in owning the product while the technical writer converts the information into effective, awesome content.   

But _how do we apply and support this separation of responsibilities?_

## Single-Responsibility Principle (SRP) for Documentation Projects

**Even if it seems simple, applying the SRP to documentation projects** requires a little change in the product team's mindset:  

* Now they will provide the information.  
* The technical write will create the content  

### Key Concepts  

**To understand the change** that the SRP introduces in the management of a documentation project, let's have a look at the following table:   


| Concept | Description |  
|------------- | ------------------- |  
| **Information** |	Information is the all pieces of text (introduction, instruction steps, feature and code descriptions (library, parameters, snippets, endpoints, etc), screenshots and raw data provided by collaborator as _information draft_ with a basic structure.|  
| **Content** |	Content is the information after being transformed into a standardized output, applying a style guide and technical writing best practices to the page structure and layout, and the text formatting to allow readers to easily find and understand the information the need. |  
| **Shared Ownership** | Since every single page is the result of the work of different collaborators (roles), the team owns the documentation. |  

**Keeping this concepts in mind** we can define the following roles and their responsibilities:  

| Role | Responsibility |  
| ------------- | --------------- |    
| **Collaborators** | Provide information which:<ol><li> is correct</li><li>is in the right order</li><li>is in the right context.</li></ol> |  
| **Reviewers** |	Validate the information provided by collaborators when required.|  
| **Technical Writer** | <ol><li>Converts information into content.</li><li>Manages release process.</li><ol> |  

**This is the little mindset change** that will guide us to a quality documentation and ensure that everyone in the team focus where they provide more value.


     
