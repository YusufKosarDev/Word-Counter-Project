# Word Counter Project
A compact, single-page Word Counter that displays real-time counts for:
- Words
- Characters
- Sentences
- Paragraphs

📝 What Does It Do?
The app analyzes user input and updates counts instantly:
- Words: split by whitespace and trimmed tokens.
- Characters: total characters in the input.
- Sentences: detected via sentence-ending punctuation (. ! ?).
- Paragraphs: blocks separated by one or more newlines.

⚙️ How Does It Work?
- Single-file build: HTML contains structure, styles, and script for portability.
- Event-driven: an `input` event listener on the textarea triggers recalculation.
- String handling: uses `trim()`, regex-based splitting, and simple normalization to handle extra spaces and line breaks.
- Lightweight logic: no external libraries — pure JavaScript + DOM updates.

🎓 What I Learned
- Practical string manipulation and edge-case handling (multiple spaces, empty input).
- Regex for splitting and basic sentence detection.
- Efficient DOM updates and minimal UI state management.
- How to present useful text analytics in a small, self-contained project.
