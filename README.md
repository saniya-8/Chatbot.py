# Chatbot.py
Chatbot...
# chatbot.py
def chatbot():
    print("🤖 Hello! I’m PyBot. Type 'bye' to exit.")
    while True:
        user = input("You: ").lower()
        if "hello" in user:
            print("Bot: Hi there!")
        elif "how are you" in user:
            print("Bot: I’m good, thanks for asking!")
        elif "name" in user:
            print("Bot: I’m PyBot, your friendly assistant.")
        elif "bye" in user:
            print("Bot: Goodbye! 👋")
            break
        else:
            print("Bot: Sorry, I didn’t understand that.")

if __name__ == "__main__":
    chatbot()
