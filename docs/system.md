---
layout: page
title: System Design Proposal
exclude: true
---

- **One-Page Overview:** 9/14 (bring to class)
- **Written Report and Presentations:** 9/23

Student teams will present to the class a system design for their project. In this stage, the team should provide details of the components and their interaction such as working with external files, accessing internal images, or communicating with entities over the internet. The exact architecture and design may evolve, but the team should be clear that they'd need the specified functionality. **This will require coordination with your client**.

### Resources

**Before your one-page overview:**
- First, read [Angela Zhang's article on "How to write a good software design doc"](https://medium.freecodecamp.org/how-to-write-a-good-software-design-document-66fcf019569c). We'll be following this model and I will borrow heavily from it here.

**Before your full written report:**
- Read [this document that I've created with writing tips.](../resources/writingtips)
- You should draw on the writing workshop that we will do together in class. 

### Writing the Design Doc

Your team's design doc should minimally include the following pieces. 

- **Title and People:** name of the system, the authors, and the date it was last updated.

- **Overview:** give a _quick_ summary of the problem, the client, and your proposed solution. Keep this short. You'll go into more detail later on.

- **Goals and Non-Goals:** you might not be solving the problem entirely for all people, but you _will_ be solving at least on piece of the problem well. Articulate what you are trying to accomplish and what is outside the scope of your project. What is the specific problem you are solving? Who, specifically, are you designing this for? What tasks are you planning to support?

- **Current Solution:** what does your client do now to achieve the functionality of the proposed system? What are the steps? Who are the users?

- **Proposed Solution:** This is will compose of most of your report.
  - *Interaction elements:*
    - [Rough mockups of the screen (these can be hand-drawn sketches)](https://medium.com/ux-prototyping/6-reasons-why-you-should-be-prototyping-more-6b7b2b15da77)
    - These should give a clear direction for your user experience. Many aspects may change after this point: styling, information organization, etc. However, you should have used your prototypes as a method to validate the functionality of your project.
    - Ideally,  you should get some feedback from your client as to whether your articulation of the system's goals match their perceptions of the system's goals. 
    <br/><br/>
  - *Major technical components of the system:*
    - conceptual overview of your system that shows interaction between the major components (_for example, diagram that shows database, server, front-end_)
    - technical frameworks/platforms/languages for each major component (_for example, iOS, mongo, django, reactjs_). Include a rationale for _why_ you made this decision.
    - other artifacts to show how the system might work together
<br/><br/>

- **Milestones:** see Angela's article above. Realize that these are very rough estimates. I would encourage you to have a fully functioning prototype (even if it's ugly) as soon as possible. Plan to finish very early. Things _will_ go very wrong.

### Deliverables 
- **One-Page Overview:** You'll bring a bullet-pointed one-page overview to class on 9/14 + rough sketches of your user interface ideas. We'll use this period an opportunity to give technical feedback to each other - leveraging the vast set of skills and experiences that are represented by our entire senior class.
- **Written Report (on 09/23):** The written report is expected 5-7 pages (2,000 to 2,500 words). Refer to our [writing rubric](https://docs.google.com/spreadsheets/d/14jlmGaAK_6JquDYGFbrZSyTkQGRQtIbQPo1yyRxbdWM/edit?usp=sharing)
- **Presentation (on 09/23):** The presentation is expected to be no more than 10 minutes, with 5 minutes of questions. That's not much time! - so be clear in your communication and cover each of the major points listed above. Refer to our [presentation rubric](https://docs.google.com/spreadsheets/d/14jlmGaAK_6JquDYGFbrZSyTkQGRQtIbQPo1yyRxbdWM/edit#gid=1783332341)

### How to Write your Doc
Given the prevalence of markdown as a tool to generate docs in industry, you will use markdown in this class to create your documents. 

**What you will submit on 09/23:**
- The link to your repository that contains your markdown. Both Gitlab and [Github render markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) as a document that can be read easily within those platforms. This means that hosting your markdown file on these sites will automatically generate the "pretty" version. 

- A pdf of your rendered markdown to submit on Google Classroom

- Your presentation slides submitted via Google Classroom 