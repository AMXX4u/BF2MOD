<div align="center">

## Paczka BattleField 2.

<img src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/battlefield2.png"></img>

</div>

<p align="center">
  <a href="#requirements">Wymagania ℹ</a> ×
  <a href="#description">Opis 📄</a> ×
  <a href="#configure">Konfiguracja 🛠</a> ×
  <a href="#screenshots">Screenshot 📷</a>
</p>

---


### Description 
- Translacja pl/en
- System Rang (17 rang)
	- **Szeregowy**, **Starszy Szeregowy**, **Kapral**, **Starszy Kapral**, **Plutonowy**, **Sierzant**, **Starszy Sierzant**, **Mlodyszy Chorazy**, **Chorazy**, **Starszy Chorazy**, **Podporucznik**, **Porucznik**, **Kapitan**, **Major**, **Podpulkownik**, **Pulkownik**, **General Brygady**
- Zapis SQL
- System odznak (8 odznak | 5 poziomów)
- Ordery (waluta zdobywana podczas zabójstwa)
- HUD
	- **Zabójstwa**, **Ranga**, **Ordery**
- Menu
	- **Opis rang oraz ich progi**
	- **Statystyki broni, medale, zabójstwa itp.**
	- **Informacje na temat odznak, postępów i nagród**
	- **(ADMIN) Przeprowadzenie resetu bazy**
- Top15
- (ADMIN) Możliwość nadawanie odznak oraz fragów
- Medale
- Sklep

### Configure

<details>
  <summary><b>BattleField 2</b></summary>

```cfg
  - bf2_xp_multiplier "0.1"
    - Mnożnik punktów wymaganych do wbicia poziomu (float)
  - bf2_overlays_language "pl"
    - Język treści na serwerze 'pl' | 'en'
  - bf2_enable_hud "1"
    - Hud włączony-1 | wyłączony-0
  - bf2_min_players "2"
    - Minimalna ilość graczy do naliczania niektórych postępów
```
</details>

### Screenshots

<details>
  <summary><b>Rangi (say /ranga)</b></summary>

  <img src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/cmd_ranks.png"></img>
  <img src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/cmd_ranks2.png"></img>
  <img src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/cmd_ranks3.png"></img>
  <img src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/cmd_ranks4.png"></img>
</details>

<details>
  <summary><b>Statystyki gracza (say /bf2stats)</b></summary>

  <img align="left" width="311" height="111" src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/bf2stats.png"></img>
  <img align="left" width="311" height="111" src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/bf2stats2.png"></img>
  <img align="left" width="311" height="111" src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/bf2stats3.png"></img>
</details>

<details>
  <summary><b>Menu główne (say /menu)</b></summary>

  <img align="left" width="311" height="111" src="https://github.com/AMXX4u/BF2MOD/blob/main/assests/menu.png"></img>
</details>



### Requirements 
- AMXModX 1.9 / AMXModX 1.10
- ReHLDS 3.12.0.780
- ReAPI 5.22.0.254
- ReGameDLL 5.21.0.556
