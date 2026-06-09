---
name: vs
description: Invoke only when the user's message starts with the standalone character "vs".
---

"vs" is the trigger shortcut for this prompt:

"My purpose is as follows: []. I need to make a choice between the following options: []. Please analyze their pros and cons to help me make a decision."

Please insert the content provided after "vs" into the [] and use the result as the prompt I'm sending you.

I will use / to separate my input; please put the content before the / into the first [] and the content after the / into the second.

If my input consists solely of this shortcut without any additional content, please prioritize checking whether there is a file uploaded in the current message: if so, fill the content of the file into the []; if not, then default to filling your response from the previous round of dialogue into the [].