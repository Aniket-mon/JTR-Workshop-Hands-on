# JTR-Workshop: Hands-On Demonstration


This is the official repository for the **"John The Ripper: Hands-On Workshop"** hosted by the **Cloud and Cybersecurity Club**, Amity University Noida. Welcome to the **Hands-On** segment.

In this part, we will **learn and practice** how to use John the Ripper step-by-step. Think of it as a guided lab where you’ll understand the workflow, crack a few example hashes, and get comfortable with the tool before attempting the real challenge.

---

##  Objective

By the end of this session, you will:

* Understand the basics of John the Ripper.
* Learn different cracking modes and options.
* Practice on sample password hashes.
* Be ready to take on the challenge round with confidence.

---

##  Getting Started

Follow the setup instructions below to prepare your environment.

### **1. For Codespace Users**

```bash
apt-get update && apt-get dist-upgrade -y
apt-get install -y john python3 python3-pip unzip curl
curl -L "https://drive.google.com/uc?export=download&id=1L_HO6jcysbGFaJP-QwV5Ao2lkymq4ssY" -o rockyou.txt
```

### **2. For Local (Non-Codespace) Users**

```bash
git clone https://github.com/Aniket-mon/JTR-Workshop-Hands-on.git
cd JTR-Workshop-Hands-on
sudo apt-get update && sudo apt-get dist-upgrade -y
sudo apt-get install -y john python3 python3-pip unzip curl
curl -L "https://drive.google.com/uc?export=download&id=1L_HO6jcysbGFaJP-QwV5Ao2lkymq4ssY" -o rockyou.txt
```

---

##  What We’ll Do

During the hands-on session, we will cover:

1. **Introduction to John the Ripper**

   * What it is and when to use it.
   * Types of password hashes.

2. **Basic Commands**

   * Cracking a simple password hash.
   * Using the default wordlist.

3. **Custom Wordlists**

   * Using `rockyou.txt`.

4. **Different Formats**

   * MD5, SHA, ZIP, SSH, and more.

5. **Practical Examples**

   * Step-by-step cracking of a sample file.
   * Interpreting John’s output.

---


##  Pro Tips

* Always check the hash format before cracking.
* Use `--format` when John doesn’t detect it automatically.
* Save your cracked results with `--pot` file.
* Experiment — the hands-on is a safe place to try things out.

---

**Next Step:**
Once you’ve completed this hands-on session, you’ll be fully ready to tackle the [JTR Challenge] and compete for the top spot!

---
