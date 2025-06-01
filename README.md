body {
  background: #fff;
  color: #222;
  transition: background 0.3s, color 0.3s;
}
@media (prefers-color-scheme: dark) {
  body {
    background: #181818;
    color: #eee;
  }
  header, footer {
    background: #222;
    color: #eee;
  }
}

header, footer {
  padding: 16px 0;
  text-align: center;
}

main {
  max-width: 900px;
  margin: 0 auto;
  padding: 18px;
}

.gallery {
  display: flex;
  gap: 18px;
  justify-content: center;
  flex-wrap: wrap;
}
.gallery img {
  width: 200px;
  border-radius: 8px;
}

.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
  margin: 20px 0;
}
.portfolio-item {
  background: #f7f7f7;
  border: 1px solid #ddd;
  padding: 8px;
  border-radius: 8px;
  text-align: center;
  transition: box-shadow 0.2s;
}
.portfolio-item img {
  width: 100%;
  border-radius: 6px;
}
@media (prefers-color-scheme: dark) {
  .portfolio-item {
    background: #232323;
    border-color: #444;
  }
}

.social-links {
  display: flex;
  gap: 18px;
  margin: 18px 0;
  justify-content: center;
}
.social-links a {
  text-decoration: none;
  color: #222;
  font-size: 1.1em;
  display: flex;
  align-items: center;
  gap: 6px;
  transition: color 0.2s;
}
.social-links a:hover {
  color: #0072b1;
}
@media (prefers-color-scheme: dark) {
  .social-links a {
    color: #eee;
  }
}

/* Simple Chatbot Widget */
#chatbot-widget {
  position: fixed;
  bottom: 16px;
  right: 16px;
  width: 260px;
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 10px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.12);
  z-index: 1000;
  padding: 0;
  font-family: inherit;
}
#chatbot-header {
  background: #0072b1;
  color: #fff;
  padding: 8px;
  font-weight: bold;
  border-radius: 10px 10px 0 0;
  text-align: center;
}
#chatbot-messages {
  min-height: 60px;
  max-height: 140px;
  overflow-y: auto;
  padding: 8px;
  font-size: 0.95em;
}
#chatbot-input {
  width: 65%;
  padding: 4px;
  margin: 8px 0 8px 8px;
  border: 1px solid #bbb;
  border-radius: 4px;
}
#chatbot-send {
  width: 25%;
  margin: 8px 8px 8px 0;
  padding: 5px;
  background: #0072b1;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-weight: bold;
}
@media (prefers-color-scheme: dark) {
  #chatbot-widget {
    background: #232323;
    border-color: #444;
    color: #eee;
  }
  #chatbot-header {
    background: #444;
  }
  #chatbot-input, #chatbot-send {
    background: #232323;
    color: #eee;
    border-color

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
