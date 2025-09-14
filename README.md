<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Best Website with 3 Dots Menu</title>
  

  <style>
  body {
  font-family: Arial, sans-serif;
  background: #f5f5f5;
  margin: 0;
  padding: 0;
}

/* Chat Icon */
#chat-icon {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: blue;
  color: white;
  padding: 12px;
  border-radius: 50%;
  cursor: pointer;
  font-size: 22px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
  z-index: 1000;
}

/* Chat Box */
#chat-box {
  position: fixed;
  bottom: 70px;
  right: 20px;
  width: 90%;
  max-width: 320px;
  height: 400px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
  display: none;
  flex-direction: column;
  z-index: 999;
}

/* Header */
#chat-header {
  background: #333;
  color: white;
  padding: 10px;
  border-radius: 10px 10px 0 0;
  font-size: 16px;
}

/* Messages Area */
#chat-messages {
  flex: 1;
  padding: 10px;
  overflow-y: auto;
  font-size: 14px;
}

/* Message Styling */
.msg {
  margin: 5px 0;
  padding: 8px;
  border-radius: 8px;
  word-wrap: break-word;
}

.bot {
  background: #e6e6e6;
  text-align: left;
}

.user {
  background: #d1e7ff;
  text-align: right;
}

/* Input Area */
#chat-input {
  display: flex;
  padding: 8px;
  border-top: 1px solid #ddd;
}

#chat-input input {
  flex: 1;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 6px;
}

#chat-input button {
  background: #333;
  color: white;
  border: none;
  padding: 8px 12px;
  margin-left: 5px;
  border-radius: 6px;
  cursor: pointer;
}
      * { margin:0; padding:0; box-sizing:border-box; }  
      <script>
  // Menu toggle
  document.addEventListener("DOMContentLoaded", function () {
    const kebabBtn = document.getElementById("kebabBtn");
    const kebabMenu = document.getElementById("kebabMenu");

    kebabBtn.addEventListener("click", function () {
      kebabMenu.classList.toggle("show");
    });

    // Agar user menu ke bahar click kare to menu band ho jaye
    document.addEventListener("click", function (e) {
      if (!kebabBtn.contains(e.target) && !kebabMenu.contains(e.target)) {
        kebabMenu.classList.remove("show");
      }
    });
  });
</script>
    body { font-family: Arial, sans-serif; line-height:1.6; background:#f5f5f5; }  
  
    /* --- Header --- */  
    header {  
      background:#333; color:#fff;  
      padding:15px 20px;  
      display:flex; justify-content:space-between; align-items:center;  
      position:sticky; top:0; z-index:1000;  
    }  
    header h1 { font-size:22px; }  
  
    /* --- 3 Dot Menu --- */  
    .kebab { position:relative; display:inline-block; }  
    .kebab button { background:transparent; border:none; cursor:pointer; padding:6px; border-radius:6px; }  
    .dot { width:6px; height:6px; border-radius:50%; background:#fff; display:block; margin:3px 0; }  
    .menu {  
      position:absolute; right:0; top:40px; background:#fff; min-width:160px;  
      box-shadow:0 6px 18px rgba(0,0,0,.15); border-radius:8px; display:none; z-index:100;  
    }  
    .menu a { display:block; padding:10px 12px; text-decoration:none; color:#333; }  
    .menu a:hover { background:#f3f3f3; }  
    .menu.show { display:block; }  
  
    /* --- Hero Section --- */  
    .hero {  
      height:65vh; background:url(sir.jpg) center/cover no-repeat;  
      display:flex; flex-direction:column; justify-content:center; align-items:center;  
      text-align:center; color:white;  
    }  
    .hero h2 { font-size:20px; margin-bottom:10px; text-shadow:2px 2px 8px rgba(0,0,0,0.7); }  
    .hero p { font-size:20px; margin-bottom:20px; color:yellow;}  
    .hero a { padding:12px 25px; background:#00c8ff; color:white; border-radius:30px; text-decoration:none; font-weight:bold; transition:background 0.3s; }  
    .hero a:hover { background:#0099cc; }  
  
    /* --- Sections --- */  
    section { padding:60px 30px; text-align:center; background:white; margin:20px auto; border-radius:12px; max-width:1000px; box-shadow:0 4px 12px rgba(0,0,0,0.1); }  
    section h2 { margin-bottom:20px; font-size:32px; }  
    section p { color:#555; }  
  
    /* --- Footer --- */  
    footer { background:#333; color:white; text-align:center; padding:20px; margin-top:40px; }
    /* --- Header --- */
    header {
      background:#333; color:#fff;
      padding:15px 20px;
      display:flex; justify-content:space-between; align-items:center;
      position:sticky; top:0; z-index:1000;
    }
    header h1 { font-size:22px; }

    /* --- 3 Dot Menu --- */
    .kebab { position:relative; display:inline-block; }
    .kebab button {
      background:transparent; border:none; cursor:pointer;
      padding:6px; border-radius:6px;
    }
    .dot {
      width:6px; height:6px; border-radius:50%;
      background:#fff; display:block; margin:3px 0;
    }
    .menu {
      position:absolute; right:0; top:40px;
      background:#fff; min-width:160px;
      box-shadow:0 6px 18px rgba(0,0,0,.15);
      border-radius:8px; display:none; z-index:100;
    }
    .menu a {
      display:block; padding:10px 12px;
      text-decoration:none; color:#333;
    }
    .menu a:hover { background:#f3f3f3; }
    .menu.show { display:block; }

    /* --- Hero Section --- */
    .hero {
      height:65vh;
      background:url(sir.jpg) center/cover no-repeat;
      display:flex; flex-direction:column; justify-content:center; align-items:center;
      text-align:center; color:white;
    }
    .hero h2 { font-size:20px; margin-bottom:10px; text-shadow:2px 2px 8px rgba(0,0,0,0.7); }
    .hero p { font-size:20px; margin-bottom:20px; 
    color:yellow;}
    .hero a {
      padding:12px 25px; background:#00c8ff; color:white; border-radius:30px;
      text-decoration:none; font-weight:bold; transition:background 0.3s;
    }
    .hero a:hover { background:#0099cc; }

    /* --- Sections --- */
    section { padding:60px 30px; text-align:center; background:white; margin:20px auto; border-radius:12px; max-width:1000px; box-shadow:0 4px 12px rgba(0,0,0,0.1); }
    section h2 { margin-bottom:20px; font-size:32px; }
    section p { color:#555; }

    /* --- Footer --- */
    footer { background:#333; color:white; text-align:center; padding:20px; margin-top:40px; }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Library Website</h1>
    <div class="kebab" id="kebab1">
      <button id="kebabBtn">
        <span class="dot"></span>
        <span class="dot"></span>
        <span class="dot"></span>
      </button>
      <div class="menu" id="kebabMenu">
        <a href="Home.html"> Home</a>
        <a href="Addmission.html">Addmission</a>
        <a href="Services.html"> Services</a>
        <a href="Achievement.html"> Achievement </a>
        <a href="Photo.html">Photo</a>
         <a href="sir ambedkar.html ">Sir ambdaker examination</a>
        <a href="About.html">About</a>
       
      </div>
    </div>
  </header>


  <!-- Hero -->
  <section class="hero" id="home">
      
    
  </section>
  <!-- About -->
  <section id="about">
    <h2>Library Rules</h2>
    <p>
  
  <ol>
    <pre>पुस्तकालय में हर समय शांति बनाए रखें।
पुस्तकों और सामग्रियों को सावधानी से संभालें।
उधार ली गई पुस्तकों को नियत तिथि पर या उससे पहले लौटा दें।
पुस्तकालय के अंदर मोबाइल फ़ोन को साइलेंट मोड पर रखें।
अंदर खाने-पीने की कोई भी चीज़ ले जाने की अनुमति नहीं है।
पुस्तकालय के संसाधनों का उपयोग केवल अध्ययन और शोध के लिए करें।
पुस्तकालय द्वारा दिए निर्देशों का पालन करें।
पुस्तकों या फ़र्नीचर पर न लिखें और न ही निशान लगाएँ।
अनुशासन और सम्मानजनक माहौल बनाए रखें।
उपयोग में न होने पर लाइट, पंखे या सिस्टम बंद कर दें।</pre>
  </section>
    <section id="about">
    <h2>Our motive</h2>
    <p>सामाजिक और निःशुल्क पुस्तकालय (Social & Free Library) का विचार बच्चों और युवाओं के लिए बहुत उपयोगी हो सकता है। यह केवल पढ़ाई का स्थान नहीं होगा, बल्कि सामाजिक विकास, संस्कार और रचनात्मकता का भी केंद्र बनेगा।
बच्चा सिर्फ पढ़ा-लिखा इंसान नहीं बनेगा, बल्कि एक संवेदनशील, जिम्मेदार और समाज-सेवी नागरिक बनेगा।

समाज में एक नई पीढ़ी तैयार होगी जो केवल नौकरी की सोच से बाहर निकलकर, समाज के लिए काम करेगी। </p>
  </section>

<style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #000;
    }

    /* Slideshow container */
    .slideshow-container {
      position: relative;
      width: 100%;
      max-width: 100%;
      height: 30vh; /* device ki 65% height */
      overflow: hidden;
    }

    /* Slides */
    .mySlides {
      position: absolute;
      width: 100%;
      height: 100%;
      opacity: 0;
      animation: fade 20s infinite; /* 5 slides × 4s = 20s */
    }

    .mySlides img {
      width: 100%;
      height: 100%;
      object-fit: cove#42445Ar;
    }

    /* Fade animation */
    @keyframes fade {
      0%   { opacity: 0; }
      8%   { opacity: 1; }
      20%  { opacity: 1; }
      28%  { opacity: 0; }
      100% { opacity: 0; }
    }

    /* Slide delays */
    .mySlides:nth-child(1) { animation-delay: 0s; }
    .mySlides:nth-child(2) { animation-delay: 4s; }
    .mySlides:nth-child(3) { animation-delay: 8s; }
    .mySlides:nth-child(4) { animation-delay: 12s; }
    .mySlides:nth-child(5) { animation-delay: 16s; }
    /* Dots container */
    .dots {
      text-align: center;
      position: absolute;
      bottom: 25px;
      width: 100%;
    }

    .dot {
      display: inline-block;
      width: 6px;   /* chhoti size */
      height: 6px;
      margin: 0 3px;
      border: 2px solid #fff; /* border wali circle */
      border-radius: 50%;
      background-color: transparent;
      animation: dotAnim 20s infinite;
    }

    /* Dot animation (sync with slides) */
    .dot:nth-child(1) { animation-delay: 0s; }
    .dot:nth-child(2) { animation-delay: 4s; }
    .dot:nth-child(3) { animation-delay: 8s; }
    .dot:nth-child(4) { animation-delay: 12s; }
    .dot:nth-child(5) { animation-delay: 16s; }

    @keyframes dotAnim {
      0%   { background-color: transparent; }
      8%   { background-color: #fff; }
      20%  { background-color: #fff; }
      28%  { background-color: transparent; }
      100% { background-color: transparent; }
    }
  </style>
</head>
<body>

  <div class="slideshow-container">

    <div class="mySlides">
      <img src="IMG-20250901-WA0060.jpg" alt="Image 1">
    </div>

    <div class="mySlides">
      <img src="IMG-20250902-WA0003.jpg" alt="Image 2">
    </div>

    <div class="mySlides">
      <img src="IMG-20250902-WA0004.jpg" alt="Image 3">
    </div>

    <div class="mySlides">
      <img src="IMG-20250828-WA0025.jpg" alt="Image 4">
    </div>
    <div class="mySlides">
      <img src="IMG-20250831-WA0012.jpg" alt="Image 5">
    </div>
    
    <!-- Dots -->
    <div class="dots">
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
    </div>
  </div>
    <section id="about">
    <h2>About This Library</h2>
    <p>
पुस्तकालय ज्ञान और सीखने का एक स्थान है, जहाँ सभी के लिए पुस्तकें, पत्रिकाएँ और डिजिटल संसाधन उपलब्ध हैं। यह एक शांतिपूर्ण वातावरण प्रदान करता है जो पढ़ने, शोध और रचनात्मकता को प्रोत्साहित करता है। जिज्ञासा और अनुशासन को पोषित करके, पुस्तकालय आजीवन सीखने को प्रेरित करता है और समाज को आकार देने में महत्वपूर्ण भूमिका निभाता है।
</p>
  </section>

</body>
</html>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: Anujmrt0026@mail.com</p>
    <p>Phone: +91 +919627055428</p>
    <p>Add:</p>
    <p>Mohalla khalsa village abdullapur Meerut U.P 250001</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Website | All Rights Reserved Makeing by Daksh kumar</p>
  </footer>
  
  <script>
  // Menu toggle
  document.addEventListener("DOMContentLoaded", function() {
    const kebabBtn = document.getElementById("kebabBtn");
    const kebabMenu = document.getElementById("kebabMenu");
    
    kebabBtn.addEventListener("click", function() {
      kebabMenu.classList.toggle("show");
    });
    
    // Agar user menu ke bahar click kare to menu band ho jaye
    document.addEventListener("click", function(e) {
      if (!kebabBtn.contains(e.target) && !kebabMenu.contains(e.target)) {
        kebabMenu.classList.remove("show");
      }
    });
  });
</script>
  

</body>
</html>

  
    </div>
  </div>

  <!-- JavaScript -->
  <script>
    const chatIcon = document.getElementById("chat-icon");
    const chatBox = document.getElementById("chat-box");
    const chatMessages = document.getElementById("chat-messages");
    const sendBtn = document.getElementById("sendBtn");
    const input = document.getElementById("userInput");

    // Toggle Chat Box
    chatIcon.addEventListener("click", () => {
      chatBox.style.display = chatBox.style.display === "flex" ? "none" : "flex";
    });

    // Send Message
    sendBtn.addEventListener("click", sendMessage);
    input.addEventListener("keypress", (e) => {
      if (e.key === "Enter") sendMessage();
    });

    function sendMessage() {
      const text = input.value.trim();
      if (text === "") return;

      // User Message
      const userMsg = document.createElement("div");
      userMsg.className = "msg user";
      userMsg.textContent = text;
      chatMessages.appendChild(userMsg);

      // Bot Reply
      setTimeout(() => {
        const botMsg = document.createElement("div");
        botMsg.className = "msg bot";

        if (text.includes("किताब") || text.includes("book")) {
          botMsg.textContent = "📚 आप लाइब्रेरी कैटलॉग से किताबों की सूची देख सकते हैं।";
        } else if (text.includes("मेंबर") || text.includes("membership")) {
          botMsg.textContent = "📝 लाइब्रेरी सदस्यता फॉर्म भरने के लिए Admission Form देखें।";
        } else if (text.includes("नियम") || text.includes("rules")) {
          botMsg.textContent = "📖 लाइब्रेरी नियम: शांति बनाए रखें, समय पर किताबें लौटाएँ।";
        } else {
          botMsg.textContent = "ℹ️ धन्यवाद! आपका प्रश्न हमें प्राप्त हुआ।";
        }

        chatMessages.appendChild(botMsg);
        chatMessages.scrollTop = chatMessages.scrollHeight;
      }, 800);

      input.value = "";
      chatMessages.scrollTop = chatMessages.scrollHeight;
    }
  </script>
</body>
</html>
