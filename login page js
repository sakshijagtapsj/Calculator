function login() {
    var username = document.getElementById('username').value;
    var password = document.getElementById('password').value;

    // Check credentials (replace with server-side authentication)
    if (username === 'user' && password === 'password') {
        // Store username in local storage
        localStorage.setItem('username', username);
        
        // Redirect to secured page or perform other actions
        window.location.href = 'secured-page.html';
    } else {
        document.getElementById('error').innerText = 'Invalid username or password';
    }
}
