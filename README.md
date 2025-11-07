# 💀 The Hexorcist - BaseBoi 3000 🔥

Welcome to **BaseBoi 3000**, the drippiest base conversion tool built different! This Python program converts numbers between different number bases (2-36) with style and personality.

## ✨ Features

- 🔄 **Convert between any base from 2 to 36**
- 🧠 **Supports hexadecimal, binary, octal, and more**
- 🎯 **Clean two-step conversion process** (input → decimal → target base)
- 🗿 **SECRET EASTER EGG**: Try the number 67... if you dare
- 💅 **Gen-Z approved interface** with personality for days

## 🚀 How to Use

### Requirements
- Python 3.x

### Running the Program

1. Clone or download this repository
2. Open a terminal/command prompt in the project directory
3. Run the program:
   ```bash
   python hexorcist.py
   ```

### Example Usage

```
💀 Yo what's good! Welcome to **BaseBoi 3000** 🔥

I convert bases faster than your Wi-Fi drops during Zoom class 🧠💨
Max base is 36 cuz anything higher and my brain melts 🧍‍♂️

👉 Drop the number (no goofy letters plz): FF
📟 What base we starting from? 16
🎯 What base we converting to, chief? 10

💅 Bet. Converting...
✨ FF (base 16) ➡ 255 (base 10) ✨

🧃 Boom. You're welcome. That number's dripping with new base energy 💅💅

🫡 Thanks for using BaseBoi 3000 — built different since 2025 🔥🔥🔥
```

## 📚 How It Works

### Conversion Process

1. **Input → Decimal**: Takes your input number and converts it to decimal (base 10)
2. **Decimal → Target**: Converts the decimal result to your desired target base

### Supported Bases

- **Base 2** (Binary): 0-1
- **Base 8** (Octal): 0-7
- **Base 10** (Decimal): 0-9
- **Base 16** (Hexadecimal): 0-9, A-F
- **Base 36** (Maximum): 0-9, A-Z

## 🎮 Easter Egg

Try entering "67" as your input number or converting to/from a base that results in 67... something legendary might happen! 🗿⚡

## 🔧 Technical Details

### Functions

- `to_decimal(number_string, original_base)`: Converts a number from any base to decimal
- `from_decimal(decimal_number, target_base)`: Converts a decimal number to any target base
- `summon_67_kid()`: 🤫 Top secret function
- `main()`: Main program loop handling user input and conversions

### Algorithm

The program uses positional notation for base conversion:
- For conversion **to decimal**: Multiply each digit by the base raised to its position power
- For conversion **from decimal**: Repeatedly divide by target base and collect remainders

## 📝 Example Conversions

| Input | Original Base | Target Base | Result |
|-------|--------------|-------------|---------|
| 1010 | 2 (Binary) | 10 (Decimal) | 10 |
| FF | 16 (Hex) | 10 (Decimal) | 255 |
| 100 | 10 (Decimal) | 16 (Hex) | 64 |
| ZZ | 36 | 10 (Decimal) | 1295 |

## ⚠️ Error Handling

The program handles:
- Invalid number inputs (non-numeric/non-alphabetic characters)
- Invalid bases (only 2-36 supported)
- General exceptions with helpful error messages

## 📜 License

Built different since 2025. Free to use and modify.

---

**Pro Tip**: This program slaps different when you're converting between binary, octal, decimal, and hex for your CS homework. No cap. 💯
