# Book_recommandation
 Features
1.AI-powered chatbot interface
2.Recommend books by genre, author, mood, or themes
3.Suggest popular and award-winning books
4.Provide summaries, similar book suggestions, and random picks
5.Supports dynamic intents and natural user queries
6.Easy to expand with new genres and user intents
7.Can be integrated into websites, apps, or voice assistants

⚙️ Tech Stack
Frontend: HTML/CSS/JavaScript (or any UI platform)
Data: CSV/JSON datasets of books
Deployment: Local, Web

📦 Use Cases
📖 Personalized book discovery
🎓 Educational and reading assistant
📱 Integration with mobile or web reading apps
🎮 Gamified genre-based book quests





 #code


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Book Finder Chatbot</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f0f4f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .box {
      text-align: center;
    }

    h1 {
      color: #2c3e50;
    }

    p {
      color: #555;
    }

    .chat-info {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      max-width: 400px;
    }
  </style>
</head>
<body>

  <div class="box">
    <div class="chat-info">
      <h1>📚 Book Finder Chatbot</h1>
      <p>Click the chat bubble at the bottom right to start!</p>
    </div>
  </div>

  <!-- Watson Assistant Web Chat Script -->
<script>
  window.watsonAssistantChatOptions = {
    integrationID: "bac68eb0-524f-48b7-b7d8-fb07a7f54ea6", // The ID of this integration.
    region: "au-syd", // The region your integration is hosted in.
    serviceInstanceID: "579706c6-5aab-4f03-97a4-e5059fa29ab4", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>
</script>
</body>
</html>
