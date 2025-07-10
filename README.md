 <h1>📊 WhatsApp Chat Analyzer (Python-Based)</h1>
  <p>
    An interactive tool to analyze WhatsApp chat histories using Python. This project extracts meaningful insights like user activity, emoji usage, sentiment trends, and message frequency. Perfect for data enthusiasts who want to visualize and explore group or individual chats in a fun and informative way.
  </p>

  <h3>🔗 Link to Web App</h3>
  <p><a href="https://whatsapp-chat-analyzer-jituji.streamlit.app/">Try it out here</a></p>
  <h3>🚀 Features</h3>
  <ul>
    <li>📈 Daily and monthly activity tracking</li>
    <li>🕵️ Message count, frequent words, and word cloud generation</li>
    <li>😃 Emoji frequency and visualization</li>
    <li>🔍 Individual user stats (for group chats)</li>
    <li>📅 Timeline charts of message flow over time</li>
    <li>📊 Interactive pie and bar charts using matplotlib & seaborn</li>
    <li>🧠 <strong>Sentiment analysis</strong> of chats using NLP
      <ul>
        <li>Classifies messages as Positive, Negative, or Neutral</li>
        <li>Aggregated sentiment breakdown per user and group</li>
      </ul>
    </li>
    <li>💬 Real-time <code>.txt</code> file parsing with Streamlit-based UI</li>
  </ul>

  <h3>📦 Tech Stack</h3>
  <h4>🖥 Frontend</h4>
  <ul>
    <li>Streamlit</li>
    <li>streamlit-webrtc (optional for live updates)</li>
  </ul>

  <h4>⚙️ Backend</h4>
  <ul>
    <li>pandas</li>
    <li>regex</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>emoji</li>
    <li>nltk / textblob / vaderSentiment</li>
  </ul>

  <h4>💬 Language</h4>
  <ul>
    <li>Python</li>
  </ul>

  <h3>🔧 Installation</h3>
  <pre><code>git clone https://github.com/JitendraSrivastava12/Whatsapp-Analyzer.git
cd whatsapp-chat-analyzer
pip install -r requirements.txt
</code></pre>
  <p>Make sure to download NLTK assets if using <code>textblob</code> or <code>vader</code>:</p>
  <pre><code>python -m nltk.downloader all
</code></pre>

  <h3>▶️ Run the App</h3>
  <pre><code>streamlit run app.py
</code></pre>
  <p>Upload your exported WhatsApp <code>.txt</code> chat file and explore visualizations interactively.</p>

  <h3>🛠 Deployment</h3>
  <ul>
    <li>Compatible with: Streamlit Cloud, Render</li>
    <li>Supports uploaded <code>.txt</code> files</li>
    <li>Enable camera/mic access if using WebRTC features</li>
    <li>Best performance on Chrome or Firefox</li>
  </ul>

  <h3>❗ Known Issues</h3>
  <ul>
    <li>Corrupted or incomplete export files may reduce analysis accuracy</li>
    <li>Sentiment analysis may have limitations with regional languages</li>
    <li>Performance may vary depending on chat size and device specs</li>
  </ul>

  <h3>🙌 Acknowledgements</h3>
  <ul>
    <li>pandas</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>emoji</li>
    <li>nltk</li>
    <li>Streamlit</li>
    <li>vaderSentiment</li>
  </ul>

  <h3>📄 License</h3>
  <p>This project is licensed under the MIT License – see the LICENSE file for details.</p>
</body>
</html>
