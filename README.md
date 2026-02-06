<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub · Home</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:-apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

body{
  background:#0d1117;
  color:#c9d1d9;
}

/* ===== NAVBAR ===== */
.navbar{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:12px 20px;
  background:#161b22;
  border-bottom:1px solid #30363d;
}

.left{
  display:flex;
  align-items:center;
  gap:15px;
}

.logo{
  font-size:18px;
  font-weight:bold;
}

.search{
  padding:6px 10px;
  background:#0d1117;
  border:1px solid #30363d;
  border-radius:6px;
  color:#c9d1d9;
}

.right{
  display:flex;
  align-items:center;
  gap:12px;
}

.avatar{
  width:32px;
  height:32px;
  border-radius:50%;
}

/* ===== BUTTON ===== */
.btn-green{
  background:#238636;
  border:none;
  padding:6px 14px;
  border-radius:6px;
  color:white;
  cursor:pointer;
}

.btn-green:hover{
  background:#2ea043;
}

/* ===== LAYOUT ===== */
.container{
  display:flex;
}

/* ===== SIDEBAR ===== */
.sidebar{
  width:260px;
  padding:25px;
  border-right:1px solid #30363d;
}

.sidebar h3{
  margin-bottom:15px;
}

.sidebar li{
  font-size:14px;
  margin-bottom:10px;
  list-style:none;
  color:#8b949e;
}

/* ===== MAIN ===== */
.main{
  flex:1;
  padding:40px;
}

.main h1{
  font-size:28px;
  margin-bottom:10px;
}

.subtitle{
  color:#8b949e;
  margin-bottom:30px;
}

/* ===== CARDS ===== */
.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.card{
  background:#161b22;
  border:1px solid #30363d;
  border-radius:8px;
  padding:20px;
}

.card h3{
  margin-bottom:10px;
}

.card p{
  font-size:14px;
  color:#8b949e;
  margin-bottom:15px;
}

.card button{
  padding:6px 12px;
  border-radius:6px;
  border:1px solid #30363d;
  background:transparent;
  color:#c9d1d9;
  cursor:pointer;
}

.card button:hover{
  background:#21262d;
}
</style>
</head>

<body>

<!-- ===== NAVBAR ===== -->
<div class="navbar">
  <div class="left">
    <div class="logo">🐙 GitHub</div>
    <input class="search" type="text" placeholder="Search or jump to...">
  </div>
  <div class="right">
    <button class="btn-green">+ New</button>
    <img src="https://via.placeholder.com/32" class="avatar">
  </div>
</div>

<!-- ===== BODY ===== -->
<div class="container">

  <!-- SIDEBAR -->
  <aside class="sidebar">
    <h3>Get started</h3>
    <ul>
      <li>✔ Create a repository</li>
      <li>✔ Complete your profile</li>
      <li>✔ Explore GitHub</li>
    </ul>
  </aside>

  <!-- MAIN CONTENT -->
  <main class="main">
    <h1>Welcome to GitHub 👋</h1>
    <p class="subtitle">
      Ready to build? Start by creating your first repository.
    </p>

    <div class="cards">
      <div class="card">
        <h3>Create a repository</h3>
        <p>A repository contains all your project files.</p>
        <button class="btn-green">New repository</button>
      </div>

      <div class="card">
        <h3>Import a repository</h3>
        <p>Bring code from another platform.</p>
        <button>Import</button>
      </div>

      <div class="card">
        <h3>Explore GitHub</h3>
        <p>Discover trending repositories.</p>
        <button>Explore</button>
      </div>
    </div>
  </main>

</div>

</body>
</html>
