<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nullsto Temp Mail - Secure Anonymous Email</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <!-- Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --bg-color: #0b0b0b;
            --card-bg: #1a1a1a;
            --text-main: #ffffff;
            --text-muted: #a1a1a1;
            --accent: #22c55e;
            --accent-hover: #16a34a;
            --border: #333;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
        
        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            overflow-x: hidden;
        }

        a { text-decoration: none; color: inherit; }
        
        /* Header */
        header {
            background: rgba(11, 11, 11, 0.95);
            border-bottom: 1px solid var(--border);
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo { font-size: 1.5rem; font-weight: 800; letter-spacing: -1px; }
        .logo span { color: var(--accent); }

        .nav-btn {
            padding: 8px 20px;
            border: 1px solid var(--accent);
            color: var(--accent);
            border-radius: 4px;
            font-weight: 600;
            transition: 0.3s;
        }
        .nav-btn:hover { background: var(--accent); color: #000; }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: radial-gradient(circle at top, #1f1f1f 0%, #0b0b0b 100%);
        }

        .hero h1 {
            font-size: 3rem;
            font-weight: 800;
            margin-bottom: 15px;
            line-height: 1.1;
        }
        
        .hero h1 span { color: var(--accent); }
        .hero p { color: var(--text-muted); font-size: 1.1rem; margin-bottom: 40px; }

        /* Email Generator Box */
        .email-generator {
            background: var(--card-bg);
            border: 1px solid var(--border);
            padding: 30px;
            border-radius: 12px;
            max-width: 700px;
            margin: 0 auto 50px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            position: relative;
            overflow: hidden;
        }

        .email-generator::before {
            content: '';
            position: absolute;
            top: 0; left: 0; width: 100%; height: 4px;
            background: var(--accent);
        }

        .generated-email {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #000;
            padding: 15px;
            border-radius: 6px;
            border: 1px solid var(--border);
            margin-bottom: 20px;
        }

        .email-text {
            font-size: 1.5rem;
            font-family: monospace;
            color: var(--text-main);
            word-break: break-all;
        }

        .action-btn {
            background: var(--accent);
            color: #000;
            border: none;
            padding: 12px 25px;
            border-radius: 6px;
            font-weight: 700;
            cursor: pointer;
            font-size: 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: 0.3s;
        }

        .action-btn:hover { background: var(--accent-hover); }
        
        .action-btn.secondary {
            background: transparent;
            border: 1px solid var(--border);
            color: var(--text-main);
            width: 100%;
            justify-content: center;
            margin-top: 10px;
        }
        .action-btn.secondary:hover { border-color: var(--accent); color: var(--accent); }

        /* Inbox Section */
        .inbox-section {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px 80px;
        }

        .inbox-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            border-bottom: 1px solid var(--border);
            padding-bottom: 10px;
        }

        .inbox-list {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .email-item {
            background: var(--card-bg);
            border: 1px solid var(--border);
            padding: 20px;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.2s;
            animation: slideIn 0.5s ease;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .email-item:hover {
            border-color: var(--accent);
            transform: translateX(5px);
        }

        .email-sender { font-weight: 700; margin-bottom: 5px; color: #fff; }
        .email-subject { color: var(--accent); font-size: 0.9rem; margin-bottom: 8px; }
        .email-preview { color: var(--text-muted); font-size: 0.85rem; line-height: 1.4; }

        .empty-inbox {
            text-align: center;
            color: var(--text-muted);
            padding: 40px;
            border: 1px dashed var(--border);
            border-radius: 8px;
        }

        /* Toast Notification */
        .toast {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            background: var(--accent);
            color: #000;
            padding: 10px 20px;
            border-radius: 4px;
            font-weight: 600;
            opacity: 0;
            pointer-events: none;
            transition: 0.3s;
            z-index: 1000;
        }
        .toast.show { opacity: 1; bottom: 40px; }

        /* Footer */
        footer {
            text-align: center;
            padding: 40px;
            color: var(--text-muted);
            font-size: 0.9rem;
            border-top: 1px solid var(--border);
        }

        @media (max-width: 600px) {
            .hero h1 { font-size: 2rem; }
            .email-text { font-size: 1.1rem; }
            .generated-email { flex-direction: column; gap: 15px; text-align: center; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <a href="#" class="logo">NULLSTO<span>.MAIL</span></a>
            <nav>
                <a href="#" class="nav-btn">Home</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <h1>Anonymous <span>Temp Mail</span></h1>
        <p>Protect your personal email from spam. Generate disposable addresses instantly.</p>

        <div class="email-generator">
            <div class="generated-email">
                <span class="email-text" id="emailAddress">loading...</span>
                <button class="action-btn" onclick="copyEmail()">
                    <i class="fas fa-copy"></i> Copy
                </button>
            </div>
            <button class="action-btn secondary" onclick="refreshEmail()">
                <i class="fas fa-redo"></i> Get New Email
            </button>
        </div>
    </section>

    <section class="inbox-section">
        <div class="inbox-header">
            <h2>Inbox <span id="inboxCount" style="font-size:0.8em; color:var(--text-muted)">(0)</span></h2>
            <button onclick="clearInbox()" style="background:none; border:none; color:var(--text-muted); cursor:pointer;">Clear All</button>
        </div>
        
        <div class="inbox-list" id="inboxList">
            <!-- Emails will appear here -->
            <div class="empty-inbox">
                <i class="fas fa-inbox" style="font-size: 2rem; margin-bottom:10px; opacity:0.5;"></i><br>
                Waiting for incoming messages...
            </div>
        </div>
    </section>

    <div class="toast" id="toast">Copied to clipboard!</div>

    <footer>
        <p>&copy; 2023 Nullsto Temp Mail. Secure & Fast.</p>
    </footer>

    < Domain forscript>
        // the temp email
        const domain = "@nullsto.com";
        let currentEmail = "";

        // Function to generate random string
        function generateString(length) {
            const characters = 'abcdefghijklmnopqrstuvwxyz0123456789';
            let result = '';
            for (let i = 0; i < length; i++) {
                result += characters.charAt(Math.floor(Math.random() * characters.length));
            }
            return result;
        }

        // Initialize Email
        function refreshEmail() {
            const randomUser = generateString(10);
            currentEmail = randomUser + domain;
            document.getElementById('emailAddress').innerText = currentEmail;
            
            // Clear inbox when new email is generated
            clearInbox();
            showToast("New Email Generated!");
        }

        // Copy to Clipboard
        function copyEmail() {
            navigator.clipboard.writeText(currentEmail).then(() => {
                showToast("Email Copied to Clipboard!");
            });
        }

        // Show Toast Notification
        function showToast(message) {
            const toast = document.getElementById('toast');
            toast.innerText = message;
            toast.classList.add('show');
            setTimeout(() => {
                toast.classList.remove('show');
            }, 3000);
        }

        // Clear Inbox Logic
        function clearInbox() {
            const list = document.getElementById('inboxList');
            list.innerHTML = `
            <div class="empty-inbox">
                <i class="fas fa-inbox" style="font-size: 2rem; margin-bottom:10px; opacity:0.5;"></i><br>
                Waiting for incoming messages...
            </div>`;
            document.getElementById('inboxCount').innerText = "(0)";
        }

        // Simulate Incoming Emails (DEMO ONLY)
        // In a real app, you would fetch this from a backend API
        const fakeEmails = [
            { from: "newsletter@amazon.com", subject: "Your Order #112-987 has shipped", body: "Your package is on its way. Track it now..." },
            { from: "verify@spotify.com", subject: "Verify your email address", body: "Click the link below to verify your account..." },
            { from: "support@netflix.com", subject: "Welcome to Netflix", body: "Enjoy your favorite movies and shows..." }
        ];

        // Wait 3 seconds then show a fake email
        setTimeout(() => {
            addEmailToInbox(fakeEmails[0]);
        }, 3000);

        // Wait 8 seconds then show another fake email
        setTimeout(() => {
            addEmailToInbox(fakeEmails[1]);
        }, 8000);

        function addEmailToInbox(emailData) {
            const list = document.getElementById('inboxList');
            
            // Remove empty state if exists
            if(list.querySelector('.empty-inbox')) {
                list.innerHTML = '';
            }

            const div = document.createElement('div');
            div.className = 'email-item';
            div.innerHTML = `
                <div class="email-sender">From: ${emailData.from}</div>
                <div class="email-subject">${emailData.subject}</div>
                <div class="email-preview">${emailData.body}</div>
            `;
            
            list.prepend(div); // Add to top
            
            // Update count
            const count = list.children.length;
            document.getElementById('inboxCount').innerText = `(${count})`;
            
            // Optional notification sound or toast could go here
        }

        // Run on load
        refreshEmail();
    </script>
</body>
</html>
