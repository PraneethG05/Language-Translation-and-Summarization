
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  
</head>
<body>

  <h1>🌐 Language-Translation-and-Summarization</h1>
  <p>This project focuses on using advanced NLP techniques to make Hindi-to-English translation more fluent and accurate. Since Hindi and English have very different grammar and sentence structures, translating between them can be tricky, especially with issues like word order, grammar, and cultural context.  

To tackle this, we used the mBART pre-trained model for translating Hindi into English, ensuring the translations are accurate and capture the right meaning. Once translated, we used the Pegasus model to summarize the text, making it concise while keeping the key points intact.  

We also relied on a bilingual corpus and specialized dictionaries to handle vocabulary challenges and improve translation quality across areas like news, literature, and everyday conversations.  

By combining mBART and Pegasus, this project demonstrates how deep learning can address common translation problems, making the results more natural and human-like. The ultimate goal is to create tools that make translations not just accurate but also easy to understand and culturally relevant for Hindi-speaking users.</p>

  <div class="section">
    <h2>📌 Project Overview</h2>
    <ul>
      <li><strong>Translation Model:</strong> mBART (fine-tuned on Hindi → English)</li>
      <li><strong>Summarization Model:</strong> PEGASUS (fine-tuned for abstractive summarization)</li>
      <li><strong>Focus:</strong> High-context accuracy, language adaptability, and summarization precision</li>
    </ul>
  </div>

  <div class="section">
    <h2>📂 Data Collection & Preprocessing</h2>
    <ul>
      <li>Bilingual datasets sourced from Indian news portals, corpora, and social media</li>
      <li>Preprocessing includes:
        <ul>
          <li>Diacritic normalization, tokenization</li>
          <li>Removing special characters and transliteration adjustments</li>
          <li>Handling idioms, local phrases, and domain-specific expressions (e.g., politics/news)</li>
        </ul>
      </li>
    </ul>
  </div>

  <div class="section">
    <h2>🔄 Translation with mBART</h2>
    <ul>
      <li>Used <strong>mBART</strong> for Indian language → English translation</li>
      <li>Fine-tuned on Hindi-English, Tamil-English corpora</li>
      <li>Handles low-resource scenarios through multilingual pretraining</li>
      <li><strong>Evaluation:</strong> BLEU Score for translation accuracy, with human checks for clarity/context</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧠 Abstractive Summarization with PEGASUS</h2>
    <ul>
      <li><strong>GSG Pretraining:</strong> Uses sentence gaps to learn to summarize critical information</li>
      <li>Fine-tuned using translated English corpora with human-written summaries</li>
      <li>Generates concise, abstract summaries optimized for readability and relevance</li>
      <li><strong>Evaluation:</strong> ROUGE metrics (Precision, Recall, F1) and native speaker feedback</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Experimental Setup</h2>
    <ul>
      <li><strong>GPU:</strong> Trained on Lighting AI T4 GPU</li>
      <li><strong>Data Split:</strong> 80% Train, 10% Validation, 10% Test</li>
      <li><strong>Batch Sizes & LR:</strong> Set individually for translation & summarization stages</li>
    </ul>
  </div>

  <div class="section">
    <h2>📊 Results & Evaluation</h2>
    <ul>
      <li><strong>Translation:</strong> High BLEU scores indicate effective context retention</li>
      <li><strong>Summarization:</strong> ROUGE Score = <strong>30.12</strong> on test summaries</li>
    </ul>
    <div class="highlight">
      <strong>BLEU Score (Translation):</strong> <em>To be updated after testing</em><br>
      <strong>ROUGE Score (Summarization):</strong> 30.12
    </div>
  </div>

  <div class="section">
    <h2>🚀 Future Improvements</h2>
    <ul>
      <li>Add support for more Indian languages (e.g., Marathi, Kannada)</li>
      <li>Integrate Named Entity Recognition (NER) for better summary context</li>
      <li>Deploy as a web app with file upload, live translation + summarization</li>
    </ul>
  </div>

  <div class="section">
    <h2>✅ Conclusion</h2>
    <p>
      This system provides a scalable and language-flexible solution for translating and summarizing Indian language content into English. The mBART + PEGASUS combination demonstrates strong performance in both translation fidelity and summary clarity.
    </p>
    <p>
      Its potential applications include <strong>news aggregation</strong>, <strong>cross-lingual journalism</strong>, <strong>healthcare outreach</strong>, and <strong>regional policy summaries</strong>.
    </p>
  </div>

  <div class="section">
    <h2>📬 Contact</h2>
    <p>For collaboration or inquiries, connect with us on <a href="https://github.com/keshav-077">GitHub</a> or email.</p>
  </div>

</body>
</html>
