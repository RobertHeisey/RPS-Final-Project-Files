```mermaid
classDiagram
  class GameState {
    int currentStreak
    int highestStreak
    String playerChoice
    String computerChoice
    String result
    GameState(int currentStreak, int highestStreak, String playerChoice, String computerChoice, String result)
  }
