# Marc's Open Chess Tournament

This is an open chess tournament where ANYONE can play. That's the fun part.  
It's your turn to play! Move a <!-- BEGIN TURN -->black<!-- END TURN --> piece.

<!-- BEGIN CHESS BOARD -->
|   | H | G | F | E | D | C | B | A |   |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **1** | <img src="img/white/rook.png" width=50px> | <img src="img/white/knight.png" width=50px> | <img src="img/white/bishop.png" width=50px> | <img src="img/white/king.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/white/bishop.png" width=50px> | <img src="img/white/knight.png" width=50px> | <img src="img/white/rook.png" width=50px> | **1** |
| **2** | <img src="img/white/pawn.png" width=50px> | <img src="img/white/pawn.png" width=50px> | <img src="img/white/pawn.png" width=50px> | <img src="img/white/pawn.png" width=50px> | <img src="img/white/pawn.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/white/pawn.png" width=50px> | <img src="img/white/pawn.png" width=50px> | **2** |
| **3** | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | **3** |
| **4** | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/white/pawn.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/white/queen.png" width=50px> | **4** |
| **5** | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | **5** |
| **6** | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/black/pawn.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/blank.png" width=50px> | **6** |
| **7** | <img src="img/black/pawn.png" width=50px> | <img src="img/black/pawn.png" width=50px> | <img src="img/black/pawn.png" width=50px> | <img src="img/black/pawn.png" width=50px> | <img src="img/blank.png" width=50px> | <img src="img/black/pawn.png" width=50px> | <img src="img/black/pawn.png" width=50px> | <img src="img/black/pawn.png" width=50px> | **7** |
| **8** | <img src="img/black/rook.png" width=50px> | <img src="img/black/knight.png" width=50px> | <img src="img/black/bishop.png" width=50px> | <img src="img/black/king.png" width=50px> | <img src="img/black/queen.png" width=50px> | <img src="img/black/bishop.png" width=50px> | <img src="img/black/knight.png" width=50px> | <img src="img/black/rook.png" width=50px> | **8** |
|   | **H** | **G** | **F** | **E** | **D** | **C** | **B** | **A** |   |
<!-- END CHESS BOARD -->

**It's your turn to move! Choose one from the following table**
<!-- BEGIN MOVES LIST -->
**CHECK!** Choose your move wisely!
|  FROM  | TO (Just click a link!) |
| :----: | :---------------------- |
| **B7** | [B5](https://github.com/marcizhu/marcizhu/issues/new?body=Please+do+not+change+the+title.+Just+click+%22Submit+new+issue%22.+You+don%27t+need+to+do+anything+else+%3AD&title=Chess%3A+Move+B7+to+B5) |
| **B8** | [C6](https://github.com/marcizhu/marcizhu/issues/new?body=Please+do+not+change+the+title.+Just+click+%22Submit+new+issue%22.+You+don%27t+need+to+do+anything+else+%3AD&title=Chess%3A+Move+B8+to+C6), [D7](https://github.com/marcizhu/marcizhu/issues/new?body=Please+do+not+change+the+title.+Just+click+%22Submit+new+issue%22.+You+don%27t+need+to+do+anything+else+%3AD&title=Chess%3A+Move+B8+to+D7) |
| **C7** | [C6](https://github.com/marcizhu/marcizhu/issues/new?body=Please+do+not+change+the+title.+Just+click+%22Submit+new+issue%22.+You+don%27t+need+to+do+anything+else+%3AD&title=Chess%3A+Move+C7+to+C6) |
| **C8** | [D7](https://github.com/marcizhu/marcizhu/issues/new?body=Please+do+not+change+the+title.+Just+click+%22Submit+new+issue%22.+You+don%27t+need+to+do+anything+else+%3AD&title=Chess%3A+Move+C8+to+D7) |
| **D8** | [D7](https://github.com/marcizhu/marcizhu/issues/new?body=Please+do+not+change+the+title.+Just+click+%22Submit+new+issue%22.+You+don%27t+need+to+do+anything+else+%3AD&title=Chess%3A+Move+D8+to+D7) |
<!-- END MOVES LIST -->

Having fun? Ask a friend to do the next move!

#### How it works

When you click on a link and submit a new issue with the desired move, a GitHub action is triggered, which in turn runs a small python script that performs the specified movement, updates this README file and commits the changes.

Have you spotted a bug? Something missing? Feel free to open an [issue](https://github.com/marcizhu/readme-chess/issues) and I will try to fix it as soon as possible :D


<details>
  <summary>Last 5 moves in this game</summary>
  <!-- BEGIN LAST MOVES -->

| Move | Author |
| :--: | :----- |
| `D1` to `A4` | [ @JohnyP36](https://github.com/JohnyP36) |
| `D7` to `D6` | [ @JVthearchitect](https://github.com/JVthearchitect) |
| `C2` to `C4` | [ @JohnyP36](https://github.com/JohnyP36) |
| `Start game` | [ @JohnyP36](https://github.com/JohnyP36) |

<!-- END LAST MOVES -->
</details>

<details>
  <summary>Top 10 most moves across all games</summary>
  <!-- BEGIN TOP MOVES -->

| Total moves |  User  |
| :---------: | :----- |
| 657 | [@JohnyP36](https://github.com/JohnyP36) |
| 352 | [@mishmanners](https://github.com/mishmanners) |
| 342 | [@marcizhu](https://github.com/marcizhu) |
| 196 | [@KubaRocks](https://github.com/KubaRocks) |
| 109 | [@viktoriussuwandi](https://github.com/viktoriussuwandi) |
| 67 | [@N-NeelPatel](https://github.com/N-NeelPatel) |
| 62 | [@herndev](https://github.com/herndev) |
| 61 | [@1TusharSharma1](https://github.com/1TusharSharma1) |
| 60 | [@LeonardoRamirezAndrade](https://github.com/LeonardoRamirezAndrade) |
| 48 | [@DatGreekChick](https://github.com/DatGreekChick) |

<!-- END TOP MOVES -->
</details>

---

Do you want to make your own? Check out my [readme chess template](https://github.com/marcizhu/readme-chess)!
![](https://hit.yhype.me/github/profile?user_id=6199781)
