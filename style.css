* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

body {
  background: #1a1a2e;
  color: white;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Лобби */
.lobby-container {
  background: #16213e;
  padding: 2rem;
  border-radius: 20px;
  box-shadow: 0 0 30px rgba(0,0,0,0.5);
  width: 90%;
  max-width: 600px;
}

.lobby-header {
  text-align: center;
  margin-bottom: 2rem;
}

.lobby-header h1 {
  color: #ffd700;
  font-size: 3rem;
  text-shadow: 0 0 10px rgba(255,215,0,0.5);
}

.lobby-header h2 {
  color: #888;
  margin-top: 0.5rem;
}

.game-code {
  background: #0f3460;
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
  margin-bottom: 2rem;
}

.game-code .code {
  font-size: 2rem;
  font-weight: bold;
  color: #ffd700;
  letter-spacing: 5px;
}

.teams-container {
  display: flex;
  gap: 1rem;
  margin-bottom: 2rem;
}

.team-card {
  flex: 1;
  background: #0f3460;
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
}

.team-card.team1 { border-top: 5px solid #ff4444; }
.team-card.team2 { border-top: 5px solid #4444ff; }
.team-card.team3 { border-top: 5px solid #44ff44; }

.team-card h3 {
  margin-bottom: 1rem;
}

.players-list {
  min-height: 100px;
  list-style: none;
}

.players-list li {
  background: rgba(255,255,255,0.1);
  margin: 0.3rem 0;
  padding: 0.3rem;
  border-radius: 5px;
}

.start-btn {
  width: 100%;
  padding: 1rem;
  background: #ffd700;
  color: #16213e;
  border: none;
  border-radius: 10px;
  font-size: 1.2rem;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}

.start-btn:hover {
  background: #ffed4a;
  transform: scale(1.02);
}

.start-btn:disabled {
  background: #666;
  cursor: not-allowed;
}

/* Экран игрока */
.player-container {
  text-align: center;
}

.join-form {
  background: #16213e;
  padding: 2rem;
  border-radius: 20px;
  width: 90%;
  max-width: 400px;
}

.join-form input {
  width: 100%;
  padding: 1rem;
  margin: 1rem 0;
  border: none;
  border-radius: 10px;
  background: #0f3460;
  color: white;
  font-size: 1rem;
}

.join-form input::placeholder {
  color: #888;
}

.join-form select {
  width: 100%;
  padding: 1rem;
  margin: 1rem 0;
  border: none;
  border-radius: 10px;
  background: #0f3460;
  color: white;
  font-size: 1rem;
  cursor: pointer;
}

.join-btn {
  width: 100%;
  padding: 1rem;
  background: #ffd700;
  color: #16213e;
  border: none;
  border-radius: 10px;
  font-size: 1.2rem;
  font-weight: bold;
  cursor: pointer;
}

.game-canvas {
  display: none;
  border: 3px solid #333;
  border-radius: 10px;
  background: #2a2a4a;
  margin-top: 1rem;
}

.controls {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  max-width: 200px;
  margin: 1rem auto;
}

.control-btn {
  padding: 1rem;
  background: #ffd700;
  color: #16213e;
  border: none;
  border-radius: 10px;
  font-size: 1.5rem;
  font-weight: bold;
  cursor: pointer;
}

.control-btn.up { grid-column: 2; }
.control-btn.left { grid-column: 1; }
.control-btn.down { grid-column: 2; }
.control-btn.right { grid-column: 3; }

.team-score {
  position: absolute;
  top: 1rem;
  right: 1rem;
  background: #16213e;
  padding: 0.5rem 1rem;
  border-radius: 10px;
  font-weight: bold;
}

.question-popup {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: #16213e;
  padding: 2rem;
  border-radius: 20px;
  box-shadow: 0 0 30px black;
  display: none;
  width: 90%;
  max-width: 400px;
}

.question-popup.active {
  display: block;
}

.question-popup h3 {
  color: #ffd700;
  margin-bottom: 1rem;
}

.question-popup input {
  width: 100%;
  padding: 1rem;
  margin: 1rem 0;
  border: none;
  border-radius: 10px;
  background: #0f3460;
  color: white;
}

.question-popup button {
  width: 100%;
  padding: 1rem;
  background: #ffd700;
  color: #16213e;
  border: none;
  border-radius: 10px;
  font-weight: bold;
  cursor: pointer;
}

.caught-message {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: rgba(255,0,0,0.9);
  padding: 2rem;
  border-radius: 20px;
  display: none;
  text-align: center;
}

.caught-message.active {
  display: block;
}

/* Экран учителя (карта) */
.teacher-container {
  display: none;
  width: 100%;
  max-width: 1000px;
  padding: 1rem;
}

.game-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
}

.team-scores {
  display: flex;
  gap: 2rem;
}

.team-score-badge {
  padding: 0.5rem 1rem;
  border-radius: 10px;
  font-weight: bold;
}

.team-score-badge.team1 { background: #ff4444; }
.team-score-badge.team2 { background: #4444ff; }
.team-score-badge.team3 { background: #44ff44; color: black; }

#gameCanvas {
  width: 100%;
  aspect-ratio: 1;
  background: #2a2a4a;
  border: 3px solid #ffd700;
  border-radius: 10px;
  cursor: crosshair;
}

.back-btn {
  padding: 0.5rem 1rem;
  background: #ffd700;
  color: #16213e;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
