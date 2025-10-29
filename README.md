<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мої друзі</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="header">
    <div class="logo">GitHub Pages</div>
    <nav class="nav">
      <button class="menu-btn">Menu ☰</button>
    </nav>
  </header>

  <main class="container">
    <section class="card">
      <img src="https://raw.githubusercontent.com/username/my-friends-site/main/friends.jpg" alt="Мої друзі" class="card-img">
      <h1 class="card-title">Мої друзі</h1>
      <p class="card-text">Ми разом вже багато років. Спілкуємося, подорожуємо та підтримуємо один одного.</p>
      <a href="#" class="about-link">About</a>
    </section>
  </main>

  <footer class="footer">
    <p>© 2025 Мої друзі | Створено для практичної роботи №4</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: 'Segoe UI', Roboto, Arial, sans-serif;
  background-color: #f6f8fa;
  color: #24292f;
}

/* Шапка */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background: #fff;
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.05);
}

.logo {
  font-weight: 700;
  font-size: 1.2rem;
}

.menu-btn {
  background: none;
  border: none;
  font-size: 1rem;
  cursor: pointer;
}

/* Контейнер */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: calc(100vh - 160px);
  padding: 2rem;
}

/* Картка */
.card {
  background: #fff;
  border-radius: 14px;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  padding: 2rem;
  max-width: 480px;
  text-align: center;
}

.card-img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 1.5rem;
}

.card-title {
  font-size: 1.8rem;
  font-weight: 700;
  margin-bottom: 0.8rem;
}

.card-text {
  color: #4a5568;
  line-height: 1.5;
  margin-bottom: 1.5rem;
}

.about-link {
  color: #0366d6;
  text-decoration: none;
  font-weight: 500;
}

.about-link:hover {
  text-decoration: underline;
}

/* Футер */
.footer {
  text-align: center;
  font-size: 0.9rem;
  padding: 1rem;
  color: #6c757d;
}

/* Адаптив */
@media (max-width: 600px) {
  .header {
    padding: 0.8rem 1.5rem;
  }

  .card {
    padding: 1.5rem;
  }
}
