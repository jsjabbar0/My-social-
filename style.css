// Simple Login
function login() {
    let username = document.getElementById("username").value;
    let password = document.getElementById("password").value;

    if (username && password) {
        localStorage.setItem("user", username);
        window.location.href = "home.html";
    } else {
        alert("Please enter username and password!");
    }
}

// Logout
function logout() {
    localStorage.removeItem("user");
    window.location.href = "index.html";
}

// Create Post
function createPost() {
    let postText = document.getElementById("postText").value;
    if (postText.trim() === "") return;

    let feed = document.getElementById("feed");
    let post = document.createElement("div");
    post.classList.add("post");
    post.innerHTML = `<strong>${localStorage.getItem("user")}</strong><p>${postText}</p>`;
    
    feed.prepend(post);
    document.getElementById("postText").value = "";
}