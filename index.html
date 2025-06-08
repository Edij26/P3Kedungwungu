<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Page</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body class="bg-light">
  <div class="container mt-5">
    <div class="card shadow p-4">
      <h3 class="text-center mb-4">Login</h3>
      <form id="loginForm">
        <div class="form-group">
          <label>Email address</label>
          <input type="text" class="form-control" id="email" placeholder="Enter email" required>
        </div>
        <div class="form-group">
          <label>Password</label>
          <input type="password" class="form-control" id="password" placeholder="Password" required>
        </div>
        <button type="submit" class="btn btn-success btn-block">Sign in</button>
        <p id="message" class="text-danger mt-3 text-center"></p>
      </form>
    </div>
  </div>

  <script>
    document.getElementById("loginForm").addEventListener("submit", function (e) {
      e.preventDefault();

      const email = document.getElementById("email").value.trim();
      const password = document.getElementById("password").value.trim();

      if (!email || !password) {
        document.getElementById("message").textContent = "Email dan password wajib diisi.";
        return;
      }

      fetch("https://script.google.com/macros/s/AKfycbzlOY5vwhf05bG70caTCsRob5zm6HQgW28GvqahCUY32jsfV9PbwacbaV8Rg1p53CWGrA/exec", {
        method: "POST",
        body: new URLSearchParams({
          action: "login",
          email: email,
          password: password
        })
      })
      .then(res => res.json())
      .then(data => {
        if (data.status === "success") {
          // Simpan info user jika perlu (contoh: sessionStorage)
          // sessionStorage.setItem("user", JSON.stringify(data.user));

          window.location.href = "dashboard.php";
        } else {
          document.getElementById("message").textContent = data.message;
        }
      })
      .catch(error => {
        console.error("Login Error:", error);
        document.getElementById("message").textContent = "Terjadi kesalahan saat login.";
      });
    });
  </script>
</body>
</html>
