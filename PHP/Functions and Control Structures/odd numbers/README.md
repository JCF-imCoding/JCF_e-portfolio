# Odd Numbers 1–100 — `while` Loop (PHP Chapter 2)

**Topic:** Control Structures → Repetition (`while`)  
**Concepts practiced:** `while` loops, counters, incrementing by step, simple output

## 📘 Overview
This exercise prints **all odd numbers between 1 and 100** using a `while` loop.  
The loop starts at 1 and increases by 2 each iteration, efficiently generating only odd values.

## 🧠 What I Practiced / Learned
- Writing a `while` loop with a **termination condition** (`$num <= 100`)
- Using a **counter** that increments by a step other than 1 (`$num += 2`)
- Producing **formatted output** in a single line

## 🗂️ Files
- `OddNumbers.php` — main script that outputs odd numbers from 1 to 100.

## 🧩 Core Logic
```php
$num = 1;
while ($num <= 100) {
    echo $num . ' ';
    $num += 2; // jump to the next odd number
}
