❓ What is this tool?

If you are following a chess tournament with multiple ongoing boards,
tracking who is winning across all games can be difficult. 
Now this tool solves this by aggregating a Lichess Broadcast into a single, highly visual dashboard.
Instead of clicking through individual games, this tool gives you a bird's-eye view of all matches, 
complete with live Stockfish evaluations, material advantages, and remaining time on the players' clocks.



🌟 Key Features:

1) Live Broadcast Sync: Paste any Lichess Broadcast URL to instantly load all ongoing and finished games from that round.
2) Dynamic Evaluation Bars: Real-time advantage bars that shift smoothly based on engine evaluations or material imbalances.
3) Ticking Clocks: Client-side ticking clocks that sync with the live broadcast data.
4) Game Conclusion Alerts: Audio chimes and a flashing red visual alert trigger the moment a game finishes, followed by a stylized display of the final result (1-0, 0-1, or ½-½).
5) Custom Themes: Seven built-in color gradients (Scoreable Default, Black & White, Green, Electric Blue, Magenta, Gold, and Crimson) to customize your viewing experience.
6) Filtering: Toggle switches to hide or show "Live" and "Finished" games to keep your dashboard clutter-free.



🚀 How to Use

1) Clone the repository: git clone https://github.com/Sa8marth/scoreable-studio.git
2) Simply double-click EvaluationBar.html to open it in any modern web browser.
3) Go to Lichess Broadcasts, Copy the URL of an active round (e.g., https://lichess.org/broadcast/fide-candidates-2024/round-1/xxxxxx). Paste the URL into the input field in Scoreable Studio and click "Load True Live Data".



🛠️ Built With

👉 HTML5 / CSS3
👉 Vanilla JavaScript
👉 chess.js - For PGN parsing and FEN generation.
👉 Lichess API - For live broadcast data and cloud engine evaluations.
