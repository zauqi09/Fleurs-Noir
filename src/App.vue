<template>
  <div class="app">
    <header>
      <h1>Fleurs Noir</h1>
      <p>By Fuad Zauqi Nur</p>
    </header>

    <section class="about">
      <h2>About the Artist</h2>
      <p>
        Terinspirasi dari aliran J-Pop dan J-Rock seperti L'Arc~En~Ciel dan J-Rocks, Fleurs Noir membangun diskografi yang penuh warna, dramatis, namun enerjik dan kaya akan eksplorasi suara.
      </p>
    </section>

    <section class="music-list">
      <h2>Discography</h2>
      <ul>
        <li>1. Melepas Rasa</li>
        <li>2. Kata-kata Hari Ini</li>
        <li>3. Tak Bersama</li>
        <li>4. Dua Hati</li>
        <li>5. Mentari Air Mata</li>
      </ul>
    </section>

    <footer>
      <p>&copy; 2025 Fleurs Noir. All rights reserved.</p>
    </footer>
  </div>
</template>

<style scoped>
.app {
  font-family: 'Georgia', serif;
  background: #0b0b0b;
  color: #e0d4f7;
  padding: 2rem;
  max-width: 700px;
  margin: auto;
  text-align: center;
  border-radius: 20px;
  box-shadow: 0 0 30px rgba(128, 0, 128, 0.3);
}

header h1 {
  font-size: 3rem;
  color: #b889f4;
  margin-bottom: 0.2rem;
}

header p {
  font-style: italic;
  color: #d8c2ff;
}

.about, .music-list {
  margin-top: 2rem;
}

.music-list ul {
  list-style: none;
  padding: 0;
}

.music-list li {
  background: rgba(255, 255, 255, 0.05);
  margin: 0.5rem 0;
  padding: 0.7rem;
  border-radius: 10px;
  transition: background 0.3s ease;
}

.music-list li:hover {
  background: rgba(255, 255, 255, 0.1);
}

footer {
  margin-top: 3rem;
  font-size: 0.9rem;
  color: #888;
}
</style>