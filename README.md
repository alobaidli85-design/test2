:root {
  --bg: #06101d;
  --panel: #0d1f37;
  --text: #ffffff;
  --muted: #c7d8ee;
  --accent: #8fd3ff;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  background: var(--bg);
  color: var(--text);
}

a {
  color: inherit;
  text-decoration: none;
}

.skip-link {
  position: absolute;
  top: -40px;
  left: 10px;
  background: var(--accent);
  color: #000;
  padding: 8px 12px;
  border-radius: 6px;
  font-weight: 600;
}

.skip-link:focus {
  top: 10px;
}

.nav {
  position: fixed;
  top: 0;
  width: 100%;
  background: rgba(6, 16, 29, 0.85);
  backdrop-filter: blur(10px);
}

.nav-inner {
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
}

.menu {
  display: flex;
  gap: 1rem;
}

.hero {
  min-height: 100vh;
  display: grid;
  place-items: center;
  text-align: center;
  padding-top: 80px;
}

.hero-image {
  max-width: 100%;
  margin-top: 2rem;
  border-radius: 20px;
}

.section {
  padding: 5rem 1rem;
}

.wrap {
  max-width: 1200px;
  margin: auto;
}

.feature-grid {
  display: grid;
  gap: 1.5rem;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

.item {
  background: var(--panel);
  padding: 1.5rem;
  border-radius: 16px;
}

.footer {
  text-align: center;
  padding: 2rem;
  opacity: 0.7;
}
