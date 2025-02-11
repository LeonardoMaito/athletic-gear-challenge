# Athletic Gear - Challenge

## Requirements

You can use any programming language.  

The goal is to validate the **logic** and, more importantly, how you solve the problem.  

We want to hear about **how you learned**, **how you figured things out**, and **why you chose to implement your solution this way**.  

You **don't need to know everything** beforehand to solve the challenge. The idea is to **research, learn, and then implement your solution**.  

We suggest using Google, Stack Overflow, YouTube, technical groups, friends, classmates, teachers—whatever works best for you.  
Just remember to tell us about your learning process later!  

There is **no strict deadline** to complete the challenge. When you're done, send it to us.  

> ⚠️ However, the time you take will also be considered.  
> Don't rush and submit something incomplete or incorrect, but also **don't take a whole year to finish**. 😉

---

## Problem to Solve

Given an **array of password strings**, which can be a constant in your code, **print only the strong passwords**.  

A **strong password** must meet the following criteria:

- ✅ At least **7 characters long**  
- ✅ Contains **at least one uppercase letter**  
- ✅ Contains **at least one lowercase letter**  
- ✅ **(Bonus)** If possible, check if it contains at least **one special character** (you can define the set of special characters yourself).  

---

## Extra / Bonus

You will **earn extra points** if you **use a Git repository** and submit your solution on **GitHub**.  

*(Even better if you fork this one! 🤩)*  

If you're unfamiliar with **Git**, don't worry!  
You can **learn it and tell us how you did it**!  

You **don't need to become an expert**—just learn the basics.  
But we **will ask how you learned it**.  

We want to evaluate your ability to **learn and seek help**.  

There are **plenty of free resources** about Git and GitHub. Use the internet to your advantage!  

> **Regardless, learning Git will be useful for your entire career in IT!** 👍  

---

## Example

Given the following array of strings:
#forTe1 senhafraca Qu@s1 Voce@Consegue!2023

Only **two** lines should be printed:
#forTe1 Voce@Consegue!2023

Since these are the only passwords that meet the strong password requirements.

---

### ✅ Password Analysis  

#### `#forTe1`
- ✅ **>= 7 characters** (7)  
- ✅ **Has an uppercase letter** (T)  
- ✅ **Has a lowercase letter** (fore)  
- ✅ **Has a number** (1)  
- ✅ **Has a special character** (`#`, if you validate special characters)  

#### `senhafraca`
- ✅ **>= 7 characters** (10)  
- ❌ **No uppercase letter**  
- ✅ **Has a lowercase letter** (senhafraca)  
- ❌ **No number**  

#### `Qu@s1`
- ❌ **< 7 characters** (5)  
- ✅ **Has an uppercase letter** (Q)  
- ✅ **Has a lowercase letter** (us)  
- ✅ **Has a number** (1)  
- ✅ **Has a special character** (`@`, if you validate special characters)  

#### `Voce@Consegue!2023`
- ✅ **>= 7 characters** (18)  
- ✅ **Has uppercase letters** (V, C)  
- ✅ **Has lowercase letters** (oceonsegue)  
- ✅ **Has numbers** (2023)  
- ✅ **Has special characters** (`@!`, if you validate special characters)  
