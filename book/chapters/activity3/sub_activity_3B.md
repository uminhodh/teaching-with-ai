#### Activity 3B: Quiz for Students with Closed and Open Questions + Feedback

The prompt below uses a combination of **conversational prompting**, **structured prompting**, and **feedback-driven prompting**. Here's a breakdown of the techniques applied:

**Key Techniques Used:**

7. **Conversational Prompting**:  
   * The prompt engages the student in a step-by-step conversation, guiding them through each part of the quiz process, allowing them to interact at their own pace and providing assistance where needed.  
8. **Structured Prompting**:  
   * The quiz follows a clear, step-by-step structure, with specific phases for inserting questions, simplifying language, asking for clarification, and answering both closed and open-ended questions. This approach ensures that the student moves through the quiz in an organized and logical way.  
9. **Adaptive Prompting**:  
   * The prompt provides the option to simplify the language of the questions (Step 2\) and request additional explanations or hints (Step 3), allowing for tailored assistance based on the student's needs. This adaptability helps ensure that the quiz is accessible to students with varying levels of understanding.  
10. **Feedback-Driven Prompting**:  
    * After answering both closed and open-ended questions, the student receives **immediate feedback** (Steps 4, 5, and 6). The feedback includes both **quantitative** (e.g., scores) and **qualitative** (e.g., personalized comments) elements, guiding the student on how to improve their understanding and performance.  
11. **Iterative Feedback Process**:  
    * The process emphasizes not just answering questions but also receiving continuous feedback, which helps the student refine their learning. The detailed breakdown of scores and comments for each question helps the student reflect on their performance and learn from their mistakes.  
12. **Scaffolded Approach**:  
    * The prompt builds from simple closed questions to more complex open-ended questions, scaffolding the learning process and assessing both factual knowledge and deeper understanding.

### **Summary:**

This prompt primarily uses **conversational prompting** for interaction, **structured prompting** for guiding the student through the quiz process, and **feedback-driven prompting** to provide both immediate quantitative and qualitative feedback, helping the student improve their performance in real-time.

**Objective:** This prompt guides students through responding to both closed (multiple-choice, true/false) and open-ended questions provided by their teacher. It offers the option to simplify the language of the questions, request additional explanations, and provides both quantitative and qualitative feedback to enhance learning.

```
You’re ready to begin your quiz\! This quiz includes both closed (multiple-choice, true/false) and open-ended questions. Follow the instructions carefully and answer each question to the best of your ability.

**Step 1: Insert Questions**

* Please insert the questions that were provided by your professor. These will be the questions you need to answer during this quiz.

**Step 2: Simplify Language (Optional)**

* If you need to simplify the language of any question, you can do so now. This will help ensure that the questions are accessible and clear for your understanding.  
* **Do you need help simplifying the language of a question?**

**Step 3: Ask for Clarification (Optional)**

* If there are any concepts or terms you don’t understand, you can ask for additional explanations or definitions. You may also request hints or further context to help you respond.  
* **Do you need explanations or hints for any of the questions?**

**Step 4: Closed Questions**

* Answer the multiple-choice or true/false questions based on the topic \[insert topic here\]. For each question, you will receive immediate feedback, including a breakdown of your score and an explanation for the correct answer.

**Step 5: Open-Ended Questions**

* Respond to the open-ended questions provided. These questions are designed to assess your deeper understanding of the topic. After you submit your responses, you will receive both quantitative and qualitative feedback, evaluating criteria such as depth of analysis, clarity, and use of evidence.

**Step 6: Feedback**

* After each response, you will receive:  
  * **Quantitative Feedback:** A breakdown of your performance (e.g., 4/5 for depth of analysis).  
  * **Qualitative Feedback:** Specific comments on how you can improve your answers and deepen your understanding of the subject matter.

### **Step 7: Total Score**

**After completing the quiz, here is a summary of your performance, including both closed and open-ended questions:**

---

**Closed Questions**

| Question | Your Answer | Correct Answer | Feedback |
| ----- | ----- | ----- | ----- |
| **1** | **\[Your Answer\]** | **\[Correct Answer\]** | **\[Feedback\]** |
| **2** | **\[Your Answer\]** | **\[Correct Answer\]** | **\[Feedback\]** |
| **3** | **\[Your Answer\]** | **\[Correct Answer\]** | **\[Feedback\]** |
| **4** | **\[Your Answer\]** | **\[Correct Answer\]** | **\[Feedback\]** |

**Closed Question Scores:**

* **Question 1: \[X\] point(s)**  
* **Question 2: \[X\] point(s)**  
* **Question 3: \[X\] point(s)**  
* **Question 4: \[X\] point(s)**  
  **Total for Closed Questions: \[X\]/\[Total\] points**

---

**Open-Ended Questions**

| Question | Your Answer | Score | Feedback |
| :---: | ----- | ----- | ----- |
| **1** | **\[Your Answer\]** | **\[X\]/\[Max\]** | **\[Feedback\]** |
| **2** | **\[Your Answer\]** | **\[X\]/\[Max\]** | **\[Feedback\]** |
| **3** | **\[Your Answer\]** | **\[X\]/\[Max\]** | **\[Feedback\]** |
| **4** | **\[Your Answer\]** | **\[X\]/\[Max\]** | **\[Feedback\]** |

**Open-Ended Question Scores:**

* **Question 1: \[X\]/\[Max\] points**  
* **Question 2: \[X\]/\[Max\] points**  
* **Question 3: \[X\]/\[Max\] points**  
* **Question 4: \[X\]/\[Max\] points**  
  **Total for Open-Ended Questions: \[X\]/\[Total\] points**

---

**Overall Score:**

* **Closed Questions: \[X\]/\[Total\] points**  
* **Open-Ended Questions: \[X\]/\[Total\] points**  
  **Total Score: \[X\]/\[Total\] points**

**General Performance Feedback:**  
**\[Personalized feedback based on performance\]**
```
