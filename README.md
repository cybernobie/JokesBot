
# JokesBot 🤖😂

A Python-based Telegram bot built using Pyrogram that fetches and sends random jokes to users using a joke API! 

## Features 🎉

- Get a new random joke with every request.
- Supports text commands to fetch jokes easily.
- User-friendly and light-weight.
- Error handling for smooth user experience.

---

## Installation 🛠️

To set up and run the bot, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/cybernobie/JokesBot.git
cd JokesBot
```

### 2. Install Dependencies

Ensure you have [Python 3.x](https://www.python.org/downloads/) installed, then install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file in the project directory with the following environment variables:

```
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
```

- Replace `your_api_id`, `your_api_hash`, and `your_bot_token` with your actual Telegram API credentials.

### 4. Run the Bot 🚀

```bash
python main.py
```

Your bot should now be running and ready to send jokes!

---

## 📝 Features & Improvements

- [ ] **Category-Specific Jokes**  
      Add support for joke categories (e.g., Dad Jokes, Puns, Dark Humor) so users can choose their preferred type.

- [ ] **Interactive Inline Mode**  
      Allow users to search and send jokes directly from Telegram inline queries.

- [ ] **Language Options**  
      Provide jokes in multiple languages to reach a broader audience.

- [ ] **Favorite & History Tracking**  
      Allow users to mark favorite jokes and view their joke history.

- [ ] **Daily/Weekly Joke Subscriptions**  
      Automatically send jokes to subscribed users at their preferred time.

- [ ] **Multimedia Jokes**  
      Support memes, images, or GIFs along with text jokes.

- [ ] **User Preferences**  
      Save user settings for personalized joke recommendations.

- [ ] **Rate Jokes Feature**  
      Enable users to rate jokes (👍 / 👎) to improve the quality of jokes served.

- [ ] **Group Mode Enhancements**  
      Improve bot functionality in groups: random joke sharing, command-based jokes, etc.

- [ ] **Fallback Jokes Database**  
      Maintain a local jokes database to ensure responses even if the API is down.

- [ ] **Gamification Features**  
      Introduce games like *Guess the Punchline* or joke leaderboards for engagement.

- [ ] **Better Error Handling & Logging**  
      Improve stability, debug logs, and resilience against API downtime.

- [ ] **Admin Panel (Optional)**  
      Create a simple dashboard for managing users, subscriptions, and API stats.

---

## Contributing 👥

Thank you to everyone who contributes to this project! ❤️ Contributions are welcome, whether it's improving the bot, fixing bugs, or adding new features.

---

## Contributors ✨

![Contributors Hall of Fame](https://github.aryansinghnegi.dev/?repo=cybernobie/JokesBot)

Happy Joking! 😄
