
# COS 101: Introduction to Computing – Structured Quiz Data 💻

A robust collection of Computer Science fundamental questions and answers, digitized and formatted as JavaScript objects. This repository serves as a data layer for building study applications, CBT simulators, and educational tools specifically tailored for the **COS 101** curriculum.

## 🎓 About the Author

I am a **Computer Science with Economics student at Obafemi Awolowo University (OAU)**. This project was born out of a desire to modernize our study materials—taking traditional past questions and converting them into a machine-readable format that any student developer can use to build "Great Ife" tech solutions.

## 📚 Data Content & Sources

The questions in this repository are curated from two primary high-quality sources to ensure full coverage of the syllabus:

1. **Aureus Medicos Academic Committee (OAU):** Localized past questions and course summaries specific to the OAU COS 101 exam format.
2. **Sanfoundry (Computer Fundamentals Series):** Industry-standard MCQs focusing on **Binary Number Systems**, Input/Output Units, and Processor Architecture.

## 🛠 Data Structure

To maintain consistency and ease of use, every question follows this exact schema:

```javascript
{ 
  q: "What is the native, low-level language consisting of only 0s and 1s?", 
  o: ["Assembly Language", "Machine Language", "High-Level Language", "Scripting Language"], 
  a: "Machine Language" 
}

```

## 🚀 Key Topics Covered

* **Computer Evolution:** 1st to 5th generations (Vacuum tubes to Artificial Intelligence).
* **Hardware Architecture:** Motherboard components, CPU (ALU/Control Unit), and Bus systems.
* **Number Systems:** Binary, Octal, Decimal, and Hexadecimal conversions.
* **Storage Hierarchy:** Primary vs. Secondary storage and data units (Bits to Yottabytes).
* **I/O Devices:** Detailed functionality of scanners, printers, and modern display technologies (LED/LCD/CRT).

## 💻 How to use in your project

If you are a student developer at OAU, you can easily fetch this data into your app:

```javascript
// Example: Randomizing a question for a user
const getQuestion = (quizArray) => {
  const randomIndex = Math.floor(Math.random() * quizArray.length);
  return quizArray[randomIndex];
};

console.log(getQuestion(cos101Data).q);

```

## 🤝 Contribution

Fellow **Great Ife** students and developers are encouraged to contribute! If you have fresh questions from recent COS 101 tests:

1. Fork the repo.
2. Add the questions to the corresponding JS file.
3. Submit a Pull Request.

---

**Curated with ❤️ at OAU (Obafemi Awolowo University).**

---

