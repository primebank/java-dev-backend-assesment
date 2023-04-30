
# Java Backend Software Engineer Take-Home Assessment

This assessment is an opportunity for the candidate to provide examples of their knowledge and skills using technologies and practices they may see working for Intrepid Networks. It is also an opportunity for the Intrepid Networks software development team to evaluate the candidate's use of these skills and technologies. This assessment will be used as points of discussion during any additional interviews.

## Your challenge

### MVP Project
This project is the only part of this challenge we consider required. Create a project that can be tested with Postman (No frontend component required for this project) so that we are able to complete CRUD operations via the REST API. The **_user summary_**, **_technical summary_**, and **_user stories_** for this project are listed below in the MVP-User-Summary section below. Please also read the **_constraints_** section as they apply to the project as well. If something is not covered in the constraints or starter application, the decision of implementation is left up to you.

### Stretch Goal Project
As the name suggests, this part of the assessment is a stretch goal and is NOT required. We want to extend our MVP project. Again, it will be tested with Postman (No frontend component required for this project) so that we are able to complete CRUD operations via the REST API. The **_user summary_**, **_technical summary_**, and **_user stories_** for this project are listed below in the User-Summary section. Please also read the **_constraints_** section as they apply to the project as well. If something is not covered in the constraints or starter application, the decision of implementation is left up to you.

**Top Tips**: While we are of course looking to use this for discussion about code in our final interview, we are also giving you an insight as to how we work on our projects from a requirements perspective. This means we will be looking at code decisions, documentation, and communication (including sensible comments both in-app and in GitHub commits), etc.

| **Constraint** | **Detail**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| --- |----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 3 Business Days | We ask that you complete the assessment and provide us a link to the public repo within 3 full business days after receiving the link to this Repo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ~5 Hours | We structure this assessment so that the minimum ask is able to be completed in around 5 hours. However, we also provide additional items in the requirements documentation in case you able to complete more than the required within that ~ 5 hour window.                                                                                                                                                                                                                                                                                                                                                                                                                                                         
| Project Tech Stack | <ul><li>Required</li><ul><li>Java</li><li>Spring Boot</li></ul></ul><ul><li>Optional</li><ul><li>PostgresSQL</li></ul></ul>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| User Stories | The user stories below have a priority based on what we would like included in the MVP of our Blog product and then another set of user stories for the stretch goal project. Meaning, at a minimum we believe that creating the project and completing all of the “high” story items in the MVP project should be within reason to complete in around 5 hours. <br /><br /><ol><li>HIGH - We would hope to see these completed within the ~5 hour window. Consider HIGH essential for the MVP</li><li>MED (Stretch Goal) - Not required, but a very strong “would like to have” for MVP</li><li>LOW (Stretch Goal) - Expected for post MVP work, but listed in case the developer can include them in MVP</li></ol> |


# MVP User Summary for ABC Company, Inc
We want to create our own blog software to use for ABC Company, Inc because WordPress and all of the other CMS systems are just too cumbersome to set up and use. As with any other blog, our users will need to be able to create, read, update, and delete blog posts. Assume all users have the same role and permission levels.

# Technical Summary
- All communication with the backend should be via REST API endpoints with JSON payloads in the response
- User/blog data will need to be persisted to fulfill the requirement (Up to the developer to decide: in-memory or RDBMS)
- Code should be appropriately documented
- At least a basic set of tests for the happy path scenarios
- If using RDBMS, it would be nice to have a script to generate additional test data

# User Stories
| **Title** | **User Story** | Importance | Notes |
| --- | --- | --- | --- |
| Create Blog Post | A user should be able to create a new blog post | High | |
| Edit Blog Post | A user should be able to edit an existing blog post | High | This is the minimum for MVP, but preference would be to further extend this to inlcude “Edit Blog Post author” story in this list.|
| Delete Blog Post | A user should be able to delete an existing blog post | High | |
| Read Blog Posts List | A user should be able to pull all blog posts | High | |


# User Summary for ABC Company, Inc (Stretch Goal)
We want to enhance our blog software for ABC Company, Inc. Create/Edit/Delete capable users should be valid users in the system. Users that read the data don’t have to be registered with the system. Assume all users have the same role and permission levels (with the noted author exception below). Each blog post should be associated with an author that is a valid user of our blog system. We want only the original author being able to edit their own blog posts.

# Technical Summary
- All communication with the backend should be via REST API endpoints with JSON payloads in the response
- Read endpoint should be open to all (No Auth required)
- Code should be appropriately documented
- At least a basic set of tests for the happy path scenarios
- If using RDBMS, it would be nice to have a script to generate additional test data

# Stretch Goals
These are additional requirements that are on the road map for our blog AFTER we have had a successful proof of concept of the above MVP requirements. You are in no way required to implement these items to complete the expectations for this assessment.

# User Stories
| **Title** | **User Story** | Importance | Notes                                                             |
| --- | --- | --- |-------------------------------------------------------------------|
| Create Blog Post Author | Each blog post should be associated with an author | Med | Stretch goal                                                      |
| Edit Blog Post author | Only the original author of the blog post should be able to edit it | Med | Stretch goal                                                      |
| Delete Blog Post author | Only the original author of the blog post should be able to delete it | Med | Stretch Goal                                                      |
| Login | A user should be able to login so they can be authenticated as a valid user | Low | Big stretch goal: Implement with Spring Security using JWT tokens |


# How to submit your solution
Create a publicly accessible repo on GitHub and email the link to us.