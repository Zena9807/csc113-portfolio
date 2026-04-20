# Prototype Testing Results

## Version 1: ChatGPT

### What Works:
- Error shows when no message is entered
- Load Example button fills the text box
- Analyze button returns tone, feedback, and suggestions
- Clear button resets the page
- Tone detection correctly identifies positive and negative messages

### What's Broken:
- No major issues found

### Observations:
- The app uses keyword-based logic instead of real AI
- Feedback is helpful but general and does not provide examples to replace negative or neutral statements
- The UI is clean and easy to use
- The improved version now includes a "Suggested Rewrite" feature that provides direct wording users can apply in real scenarios
- Updated version includes multiple rewrite options instead of a single suggestion
- Each rewrite option can be copied directly using a "Copy" button
- Copy buttons now provide visual feedback by changing to "Copied!"
- Feedback tone was improved to sound more like a real team lead or coach instead of generic AI responses

---

## Decision

Undecided. Running a different version to see if I like that version better.

---

## Version 2: Gemini

### What Works:
- Accepts user input and processes messages
- Returns tone and basic feedback
- Displays suggestions for improving the message
- Handles both positive and negative message examples

### What's Broken:
- Feedback was less detailed and more generic
- Suggestions were repetitive and not always actionable
- Layout was less structured and harder to read

### Observations:
- The logic worked, but responses felt more surface-level
- The tool focused more on identifying tone than improving it
- UI design was simpler but less user-friendly

---

## Updated Decision

After comparing both versions, I chose to continue with ChatGPT's version because it provided clearer structure, more useful feedback, and a better overall user experience. However, I will still be testing one more with Claude in comparison.

---

## Version 3: Claude

### What Works:
- Accepts user input and analyzes customer service messages
- Provides tone detection and structured feedback
- Includes suggestions for improving clarity and tone
- Handles different message types (positive, neutral, negative)

### What's Broken:
- Feedback sometimes felt overly formal or wordy
- Suggestions were helpful but not always concise
- Lacked clear, direct phrasing that users could easily reuse

### Observations:
- The structure of the response was strong and well-organized
- Feedback leaned more toward explanation than action
- The tone felt more scholarly than practical for real-world use

---

## Final Decision

After testing multiple versions, I chose to continue with ChatGPT's version because it provided the best structure, usability, and overall user experience.

After additional iterations, the application was significantly improved by:
- Making feedback more natural and human-sounding
- Adding multiple ready-to-use rewrite options
- Adding copy-to-clipboard functionality with visual confirmation

These improvements made the tool more practical and closer to a real-world customer experience coaching solution.
---
