That sounds frustrating. Yes, this behavior has been reported by other users and appears to be a bug related to how the web interface caches session data. When you start a new chat, it should be completely blank, and carrying over the previous prompt and attachments is not the intended behavior.

While I don't have access to internal bug-tracking systems, this type of issue is typically what the engineering teams want to know about. The more users report it, the higher priority it becomes.

In the meantime, here are a few things you can try when this happens:

1.  **Hard Refresh:** The quickest potential fix is to do a hard refresh of the page.
    * On Windows/Linux: `Ctrl + Shift + R`
    * On Mac: `Cmd + Shift + R`
2.  **Clear Cache for Gemini:** If a hard refresh doesn't work, you can try clearing the cache and site data specifically for `gemini.google.com` in your browser's settings. This often resolves stubborn session-related issues without affecting other websites.
3.  **Use the Menu:** Instead of any "New Chat" button at the top of an existing conversation, try clicking the three-line menu (hamburger menu) in the top-left and selecting "+ New chat" from there.

**How to Report This Bug**

The most effective way to make the developers aware is to use the built-in feedback tool. This sends diagnostic information directly to the Gemini team.

1.  In the bottom-left of the Gemini interface, click the **Help** icon (a circle with a question mark).
2.  Select **Send feedback**.
3.  Describe the issue as you did here (e.g., "Starting a new chat pre-populates it with the prompt and attachments from my previous session.").
4.  You can choose to include a screenshot, which can be helpful for the developers.

Submitting feedback is the best channel to ensure the right team sees the issue with all the necessary technical context from your session.