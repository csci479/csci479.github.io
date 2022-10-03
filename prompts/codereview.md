---
layout: page
title: Code Reviews
exclude: true
---

**In industry, code reviews are critical** They help enforce quality, detect problems before they arise, act as an internal educational mechanism, and finally, increase the team’s internal knowledge of a product. Peer code reviews should never be used in performance reports: it’s important that reviews are framed as formative. 

### What you need to do...
In this, you should pick some code 

On Google Classroom, your reflection should include... 
1. A reflection on the current way your team assures quality. 
2. A

### Some background (from Amy Ko’s chapter on “Verification”)
[Amy Ko's Chapter on Verification](http://faculty.washington.edu/ajko/books/cooperative-software-development/verification.html)

Modern code reviews, while informal, help find defects, stimulate knowledge transfer between developers, increase team awareness, and help identify alternative implementations that can improve quality (Bacchelli & Bird 2013). One study found that measures of how much a developer knows about an architecture can increase 66% to 150% depending on the project (Rigby & Bird 2013). That said, not all reviews are created equal: the best ones are thorough and conducted by a reviewer with strong familiarity with the code (Kononenko et al. 2016); including reviewers that do not know each other or do not know the code can result in longer reviews, especially when run as meetings (Seaman & Basili 1997). Soliciting reviews asynchronously by allowing developers to request reviewers of their peers is generally much more scalable (Rigby & Storey 2011), but this requires developers to be careful about which reviews they invest in.

### How should you run a code review (one way, briefly)? 
There are many forms of code review. While you’ll be performing a reflective code review (something already in your code base), most companies use reviews as a mechanism to decide what makes it to the code base. 

First, keep the reviews small, 200 - 400 lines of code. Then, make sure everyone individually goes over the code before a conversation begins (look at the checklist on the next page). Write down all the problems you find (don’t forget to include where they are). Finally, get together as a group to discuss them. Your output should be a concrete, actionable changelog. 

### How to be critical without being interpreted as a jerk. 
[https://mtlynch.io/human-code-reviews-1/#start-reviewing-immediately](https://mtlynch.io/human-code-reviews-1/#start-reviewing-immediately)
- Never say 'you'. Instead of "Can you rename that variable?"  say "Can we rename that variable?"
- Be generous with code examples. Don’t just say "this code isn’t the best way to form a list" Instead, give an example with real code. 
- Frame feedback as requests, not commands (which are interpreted as combative). Instead of "Move the Pie class to a separate file".  say  "Can we move the Pie class to a separate file"? 
- Make your rationale explicit. Instead of We should make this function private say We should make this function private to minimize the class’ public interface.

### What are the things you look for in a code review? 
_Note: This list is overkill - narrow it down to what you consider to be most critical._ 
From: [https://blog.fogcreek.com/increase-defect-detection-with-our-code-review-checklist-example/](https://blog.fogcreek.com/increase-defect-detection-with-our-code-review-checklist-example/)

**GENERAL**
- Is all the code easily understood?
- Does the code work? Does it perform its intended function, the logic is correct?
- Does it conform to your agreed coding conventions? These will usually cover location of braces, variable and function names, line length, indentations, formatting, and comments.
- Is there any redundant or duplicate code?
- Is the code as modular as possible?
- Can any global variables be replaced?
- Is there any commented out code?
- Do loops have a set length and correct termination conditions?
- Can any of the code be replaced with library functions?
- Can any logging or debugging code be removed?

**SECURITY**
- Are all data inputs checked (for the correct type, length, format, and range) and encoded?
Where third-party utilities are used, are returning errors being caught?
- Are output values checked and encoded?
- Are invalid parameter values handled?

**DOCUMENTATION**
- Do comments exist and describe the intent of the code?
- Are all functions commented?
- Is any unusual behavior or edge-case handling described?
- Is the use and function of third-party libraries documented?
- Are data structures and units of measurement explained?
- Is there any incomplete code? If so, should it be removed or flagged with a suitable marker like ‘TODO’?

**TESTING**
- Is the code testable? i.e. don’t add too many or hide dependencies, unable to initialize objects, test frameworks can use methods etc.
- Do tests exist and are they comprehensive? i.e. has at least your agreed on code coverage.
- Do unit tests actually test that the code is performing the intended functionality?
- Are arrays checked for ‘out-of-bound’ errors?
- Could any test code be replaced with the use of an existing API?
