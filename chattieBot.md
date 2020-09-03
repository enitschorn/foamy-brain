# ChattIE Bot

- puppeteer runs a headless Chrome instance
- use cases for error handling
  - heavy traffic, everybody leaves, it can default to say that the meeting has ended -> possible solution could be to end the meeting and let it restart the process again

- 41-43 exposed functions so browser can read them
- 75-89 checks whether users have been entering - API only gets called when a user enters
- Asynclock is a library that blocks several threads from running