## Hi there 👋
<!DOCTYPE html>
<html>
<head>
    <title>Task Wallet | Welcome</title>
    <link rel="stylesheet" type="text/css" href="style.css"> <!-- Link to CSS file -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsive Design -->
</head>
<body>
    <!-- Navigation Bar -->
    <div class="navbar">
        <div class="logo">Task Wallet</div>
        <ul>
            <li><a href="#signupPage">Sign Up</a></li>
            <li><a href="#loginPage">Login</a></li>
            <li><a href="#contactPage">Contact</a></li>
        </ul>
    </div>

    <!-- Welcome Header -->
    <div class="header">
        <h1>Welcome to Task Wallet</h1>
        <p>Your gateway to earning through tasks!</p>
    </div>

    <!-- Signup Page -->
    <div class="container" id="signupPage">
        <h2>Sign Up</h2>
        <form id="signupForm">
            <input type="text" id="newUsername" placeholder="Username" required>
            <input type="password" id="newPassword" placeholder="Password" required>
            <button type="submit">Sign Up</button>
        </form>
    </div>

    <!-- Login Page -->
    <div class="container" id="loginPage" style="display:none;">
        <h2>Login</h2>
        <form id="loginForm">
            <input type="text" id="username" placeholder="Username" required>
            <input type="password" id="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>

    <!-- Payment Page -->
    <div class="container" id="paymentPage" style="display:none;">
        <h2>Make Payment</h2>
        <form id="paymentForm">
            <select id="paymentMethod">
                <option value="jazzcash">JazzCash</option>
                <option value="easypaisa">EasyPaisa</option>
            </select>
            <input type="text" id="trxID" placeholder="Transaction ID (TRX ID)" required>
            <button type="submit">Submit Payment</button>
        </form>
    </div>

    <!-- Task Selection Page -->
    <div class="container" id="taskPage" style="display:none;">
        <h2>Select Task</h2>
        <button onclick="selectTask('TikTok Task')">TikTok Task</button>
        <button onclick="selectTask('Assignment Task')">Assignment Task</button>
    </div>

    <!-- Invite and Communication Page -->
    <div class="container" id="invitePage" style="display:none;">
        <h2>Invite Friends</h2>
        <button onclick="generateInviteLink()">Generate Invite Link</button>
        <p id="inviteLink" style="display:none;"></p>

        <h2>Chat</h2>
        <textarea id="chatMessage" placeholder="Write a message..."></textarea>
        <button onclick="sendMessage()">Send Message</button>
    </div>

    <!-- Withdrawal Page -->
    <div class="container" id="withdrawalPage" style="display:none;">
        <h2>Request Withdrawal</h2>
        <form id="withdrawalForm">
            <input type="text" id="withdrawPhone" placeholder="Phone Number" required>
            <input type="text" id="withdrawAccount" placeholder="Account Number" required>
            <input type="text" id="withdrawName" placeholder="Account Holder Name" required>
            <button type="submit">Withdraw</button>
        </form>
    </div>

    <!-- Contact Page -->
    <div class="container" id="contactPage" style="display:none;">
        <h2>Contact Us</h2>
        <p>If you have any questions, please feel free to reach out.</p>
        <p>Email: support@taskwallet.com</p>
    </div>

    <script src="script.js"></script> <!-- Link to JavaScript file -->
</body>
</html>
<!--
**Taskwale/Taskwale** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
