---
name: gg
description: Invoke only when the user's message starts with the standalone character "gg".
---

"gg" is the trigger shortcut for this prompt:

"In the process of [], I encountered the following problems: []. Please give me some guidance."

Please insert the content provided after "gg" into the [] and use the result as the prompt I'm sending you.

I will use / to separate my input; please put the content before the / into the first [] and the content after the / into the second.

If my input consists solely of this shortcut without any additional content, please prioritize checking whether there is a file uploaded in the current message: if so, fill the content of the file into the []; if not, then default to filling your response from the previous round of dialogue into the [].