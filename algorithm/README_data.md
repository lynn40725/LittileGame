# Mock dataset for "Game Purchase & Playtime Planner"

- `games.json`: 40 fictional games with tags, playtime, rating, discount, price, platforms, and `groupId` for version grouping (Union-Find).
- `players.json`: 60 fictional players with 4D preference vectors (0–10) and owned game libraries for KNN neighbor search + candidate mining.

Tags (4D):
- action
- narrative
- puzzle
- text

Notes:
- `groupId` may repeat across two games to simulate "same game different editions/platforms".
- `archetype` in players is for debugging/demo and can be removed for submission if you want.
