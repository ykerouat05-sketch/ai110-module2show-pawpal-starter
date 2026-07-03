# PawPal+ Project Reflection

## 1. System Design

**a. Initial design**

- Briefly describe your initial UML design. add a pet , schedule a task, see today's task
- What classes did you include, and what responsibilities did you assign to each? i have included owner with pet name it has add task and remove task ,pet tasks, Constraints, and  daily plan

**b. Design changes**

- Did your design change during implementation?
- If yes, describe at least one change and why you made it.
yes i made some changes to the design as i added classes to complete missing responsibilities and make it easer for connection 
---

## 2. Scheduling Logic and Tradeoffs

**a. Constraints and priorities**

- What constraints does your scheduler consider (for example: time, priority, preferences)?
my scheduler consider time limits, task duration, priority, preferred start time and remaining daily capacity. 
- How did you decide which constraints mattered most?
I prioritized time-related constraints first because they determine whether tasks can be scheduled at all. Then I considered start time and priority to organize tasks more efficiently within the available window.

**b. Tradeoffs**

- Describe one tradeoff your scheduler makes. it compares exact time equality, not overlaping intervals. a 30 min task at 9:00 and another at 9:15 won't flag only identical start time do.
- Why is that tradeoff reasonable for this scenario? this tradeoff is reasonable because it keeps the system simple and easier to implement without requiring comlex time range calculations.

---

## 3. AI Collaboration

**a. How you used AI**

- How did you use AI tools during this project (for example: design brainstorming, debugging, refactoring)? honestly i used AI tools during this project for design, brainstorming and refactoring 
- What kinds of prompts or questions were most helpful? the most helpful propmts were to show me what is wrong with the code, what fixes he will make and how it does really work.  

**b. Judgment and verification**

- Describe one moment where you did not accept an AI suggestion as-is.
i did not accept claude suggestion when he added two more classes to the uml design so it make 7 in total so i asked him to make it more concise as remove the unecessary classes or add them to the others.
- How did you evaluate or verify what the AI suggested?

---

## 4. Testing and Verification

**a. What you tested**

- What behaviors did you test? i tested adding task in general, sorting, filtering 
- Why were these tests important? these tests were important becaus eit showed me what it was missing how it really works and is everything going according to the plan

**b. Confidence**

- How confident are you that your scheduler works correctly? 5/5
- What edge cases would you test next if you had more time? i dont know i think i tested all that i know

---

## 5. Reflection

**a. What went well**

- What part of this project are you most satisfied with?
the part where i tested using pytest and it all passed.

**b. What you would improve**

- If you had another iteration, what would you improve or redesign?
i would improve the classes that i design i will try to make them clearer and more concise. 
**c. Key takeaway**

- What is one important thing you learned about designing systems or working with AI on this project? 
one important thing that i leanred from this project is that designing the system before coding makes it much easier to udnerstand  nd visualize how the entire project will work.