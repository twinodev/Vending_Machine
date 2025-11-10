# Vending Machine Simulator (C)

A **console-based vending machine** written in **C** as a university personal project.

---

## Features
- **Multiple items** (snacks & drinks) with prices
- **Coin insertion** (1, 2, 5, 10 UGX)
- **Exact change calculation** (greedy algorithm)
- **Item dispensing** with change return
- **Inventory tracking** (prevents out-of-stock sales)
- **User-friendly menu interface**

---

## Files
| File        | Description |
|-------------|-------------|
| `Main.c`    | Program entry point with user interface |
| `Vending.c` | Core vending logic (selection, payment, dispensing) |
| `Vending.h` | Function declarations and data structures |
| `change.c`  | Change-making algorithm using available coins |
| `README.md` | This file |
| `LICENSE`   | MIT License |

---

## How to Compile & Run

```bash
# Compile
gcc Main.c Vending.c change.c -o vending

# Run
./vending
```
## Example Usage
```bash
===================================
     VENDING MACHINE (UGX)
===================================

1. Coke     - 5 UGX   [10 left]
2. Fanta    - 5 UGX   [10 left]
3. Water    - 3 UGX   [15 left]
4. Chips    - 7 UGX   [8 left]
5. Exit

Select item: 1
You selected: Coke (5 UGX)

Insert coins (1, 2, 5, 10). Enter 0 to finish:
> 10

Change: 5 UGX
Dispensed: Coke
Thank you!

Press Enter to continue...
```
## Project Structure
```
Vending_Machine/
├── Main.c       → User interaction loop
├── Vending.c    → Item management & selection
├── Vending.h    → Headers & structs
├── change.c     → Change calculation
├── README.md    → Project docs
└── LICENSE      → MIT License
```
## Author
**@twinodev**  
- **Location**: Uganda  
- **X (Twitter)**: [@twinodev](https://x.com/twinodev)  
- **GitHub**: [twinodev](https://github.com/twinodev)  
- **Updated**: November 10, 2025 05:02 PM EAT

# License
This project is licensed under the MIT License – see the LICENSE file for details.  
>Free to use, modify, and distribute.
>
**BUY ME COFFEE🫅**
