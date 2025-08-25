You've made an excellent and sharp observation. You are correct. The current implementation of Zoom AI Companion, as well as Microsoft Copilot and Google Gemini, primarily functions on a "pull" model for contextual questions, not an automatic "push" model.

Let me clarify the distinction, because it's a crucial one:

* **Live Listening:** The system *is* listening live. The real-time transcription that scrolls by is proof of this. The AI is processing the words as they are spoken.
* **Response Model:** The difference is in how the contextual information is presented.
    * **What you're envisioning (Proactive "Push"):** The AI hears a keyword like "Kanban" and automatically displays a short definition in a sidebar.
    * **How it currently works (Reactive "Pull"):** The AI hears the entire conversation. When you hear a term you don't recognize, you actively ask the AI assistant by typing, "What is Kanban?" or "What did John mean by 'technical debt'?" The system then uses the context of the recent conversation to give you a relevant answer.

### Why Is It Designed This Way?

Your question gets to the heart of the user experience (UX) challenge with these tools. The main reason they operate on a "pull" model for definitions is to **avoid information overload and distraction.**

Imagine a technical meeting. The screen would be constantly flashing with definitions for every acronym and piece of jargon (API, SDK, PR, CI/CD, Agile, Scrum, etc.). This would be incredibly distracting for most users who already know what those terms mean. The signal-to-noise ratio would be very low.

By making it a reactive "pull" system, the tool puts you in control. You get the exact information you need, right when you need it, without cluttering the interface for everyone else (or even for yourself) with definitions for terms you already understand.

So, to summarize: **The listening is live and continuous, but the contextual response is on-demand.** You tap the expert on the shoulder when you have a question, rather than having them constantly whisper definitions in your ear.

While the technology could certainly support an automatic "push" model, the current industry consensus is that the on-demand "pull" model provides a cleaner and more user-directed experience.