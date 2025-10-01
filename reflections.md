# Copilot Usage and Self-Reflections

For each thing that was not working as you intended, include an entry with:
- A description of the issue
- How you described the issue to Copilot and requested a test
- The test Copilot generated (if any)
- Reflections on how you fixed the issue and any particularly effective prompts you discovered

At the end of this file, add your self-reflections on the process.

---

# Example Entry

**Issue:**
The TypingPrompt component was not updating the displayed text as the user typed.

**Prompt to Copilot:**
Right now the TypingPrompt component displays a static prompt text. I want it to update the displayed text as the user types in the input field.
Write a test for TypingPrompt to check that the displayed text updates as the user types.

**Test Copilot Generated:**
```js
// ...test code Copilot suggested...
```

**Next Prompt:**
"Please generate hypotheses for why the TypingPrompt component is not updating the displayed text as the user types and suggest possible fixes. Don't write code until I approve a hypothesis."

**Notes and Reflections**

At first, it misunderstood what was going wrong. It wanted to add state to a different component, but after discussion I realized the problem was that I had the wrong name for the event handler. Once I clarified that, it fixed it quickly.

---

# Self Assessment
  - What are you most proud of in your work?
  - What would you do differently next time?
