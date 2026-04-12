# ST10485711_PROG_POE
Initial Project Setup

I created a new C# console application in Visual Studio. This provided the basic structure with a Program.Main() entry point where the chatbot logic begins.

Added Voice Greeting

I implemented the VoiceGreeting() method, which attempts to play a greetings.wav file when the bot starts. If the file is missing or playback fails, the program gracefully continues with a text greeting.

Added ASCII Art

I designed the ShowAsciiArt() method to display colorful ASCII art and a robot mascot. This gives the chatbot personality and makes the console interface visually engaging.

Implemented User Input

I added the AskName() method to request the user’s name. If no name is entered, it defaults to “Guest.” This personalization makes the chatbot feel more interactive.

Added Chatbot Responses

I built the ChatLoop() and Respond() methods.

ChatLoop() keeps the conversation running until the user types “exit.”

Respond() interprets user input, matches it to cybersecurity topics, and provides answers.

I also added small talk responses (e.g., “how are you”) to make the bot friendlier.
