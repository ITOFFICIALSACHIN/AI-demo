# AI-demo
print("🤖 My AI: Hello! Main tumhara AI assistant hoon.")
print("Type 'bye' to exit.\n")
while True:
    user = input("You: ")
    if user.lower() == "bye":
        print("🤖 My AI: Goodbye! 👋")
        break
 elif "hello" in user.lower() or "hi" in user.lower():
        print("🤖 My AI: Hello! Kaise ho?")

   elif "name" in user.lower():
        print("🤖 My AI: Mera naam My AI hai.")

  elif "python" in user.lower():
        print("🤖 My AI: Python ek popular programming language hai.")

   elif "who are you" in user.lower():
        print("🤖 My AI: Main ek simple Python-based chatbot hoon.")

  else:
        print("🤖 My AI: Sorry, mujhe ye samajh nahi aaya.")
