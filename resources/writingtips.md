---
layout: page
title: On Technical Writing
exclude: true
---

**Great work is worthless without writing:** Leslie Lamport, 2013 of the Turing Award (the Nobel Prize of Computer Science), spent most of his 2017 commencement address at Brandeis pleading with students for better communication.

> If you succeed in attaining a position that allows you to do something great, if you do something that really is great, and if you realize that it’s great, there’s still one more hurdle: You have to convince others that it’s great. This will require writing.

**Simply put:** if you are bad at writing or communicating your ideas, your ideas don’t matter. **So, what is clear, effective, technical communication?**

- **Improve your style:** Google _technical paper_ or _systems design doc_ Look at the structure of the documents. There is a clear structure that is not just reflected in the content, but through section titles, through lists, and through figures. The important information is easy to locate. Your goal is to communicate as clearly and efficiently as possible. <br/><br/>
  - Does your document have clear sections and subsections that communicate the structure of your writing?
  - When you are communicating a list of items, are you using a bullet-point (or numbered) list?
  - Do key words or definitions stand out (by bolding, italicizing, etc.)?
  - When appropriate, are their captioned images that represent the ideas you’re trying to communicate? Don’t tell me about your design, _show me_. Don’t just tell me about your technical system, _create a visual overview of the modules_.
  - Does your document look like a professional document? Don’t double space these documents. Find a good style template to use.
<br/><br/>

- **Look at our course’s writing rubric:** I have it linked in the syllabus and instructions of each assignment I’ve posted. Read it. Look at what it emphasizes. Content + Spelling & Grammar are just two dimensions. I also look for _Clarity, Organization, Style, Visuals_. Many students ignore these factors, but these aren’t arbitrary requirements. They are standard in any good technical document.

- **CS students are good at describing ‘how’, but not ‘why’:** I can make a reasonable argument against every single technical decision you make. There are always tradeoffs. Always. When I write a technical document, critics often come back with the comment _"you can’t make that assumption"_. So don’t. Provide a rationale. **For example:** Imagine that you have decided to create a system on iOS. **Why?**<br/><br/>
  - _Does it align with your users needs?_ Platforms and languages are not neutral. If you are designing a medical app, you should be aware that choosing iOS reduces the accessibility of your app to low income families. You might not like Amazon’s tablets, but know that their very low price point opens different opportunities for the impact of your app.<br/><br/>
  - _Does it align with your client’s needs?_ Your client and your users may not be the same group of people. Are the platforms you’re choosing accessible to the client? What happens if something goes wrong in the database? Will your client be able to debug it? Probably not. Using Google Sheets as a database sounds absolutely silly and ridiculous from a technical standpoint. But it also might make the maintenance and management of the client’s data significantly more accessible. Your technical decisions cannot be divorced from the users.<br/><br/>
  - _Does it align with your group’s needs?_ Every technical decision will have a cost. These costs might be in terms of learnability, previous expertise, or development environments. Remember that you are not working by yourself, and the fuse on this project is short. Make decisions that align with the needs of your group.
  <br/><br/>

- **Technical Communication is different than your journals:** the tone and formality of these documents should be significantly different. _I think_ and _I like_ are wonderful ways to express your experience, but they do not offer evidence.<br/><br/>
  - Instead of: _We like the designs of iOS apps so we chose iOS._
  - Write: _The design metaphors of iOS align with the expectations and experiences of our users, who are predominately iPhone users._<br/><br/>

  Notice the difference! In the first case, you chose iOS just for the hell of it. In the second case, you chose for reasons that are grounded in your project.

- **In general, be a good writer.** Norman Ramsey, a CS prof at Tufts University, outlines the following principles in [_Learn Technical Writing in Two Hours per Week_](https://www.cs.tufts.edu/~nr/pubs/learn-two.pdf):
<br/><br/>
  - _CORRECTNESS:_ Write correct English, but know that you have more latitude than your high-school teachers may have given you.
  - _CONSISTENT NAMES:_ refer to each significant character (algorithm, concept, language) using the same word everywhere. Give a significant new character a proper name.
  - _SINGULAR:_ To distinguish one-to-one relationships from n-to-m relationships, refer to each item in the singular, not the plural.
  - _SUBJECTS & VERBS:_ Put your important characters in the subjects, and join each subject to a verb that expresses a significant action.
  - _INFORMATION FLOW:_ In each sentence, move your reader from familiar information to new information.
  - _EMPHASIS:_ For material you want to carry weight or be remembered, use the end of a sentence.
  - _COHERENCE:_ In a coherent passage, choose subjects that refer to a consistent set of related concepts.
  - _PARALLEL STRUCTURE:_ order your text so your reader can easily see how related concepts are different and how they are similar
  - _ABSTRACT:_ In an abstract (or overview), don’t enumerate a list of topics covered; instead, convey the essential information found in your paper.
