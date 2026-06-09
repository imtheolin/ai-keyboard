---
name: b
description: Invoke only when the user's message starts with the standalone character "b".
---

"b" is the trigger shortcut for this prompt:

"I want to buy []. How should I choose?"

Please insert the content provided after "b" into the [] and use the result as the prompt I'm sending you.

If my input consists solely of this shortcut without any additional content, please prioritize checking whether there is a file uploaded in the current message: if so, fill the content of the file into the []; if not, then default to filling your response from the previous round of dialogue into the [].