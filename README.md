# 📄 Resume Template Automation using Python

## 🚀 Project Overview

This project is a **Python-based document automation tool** that dynamically replaces placeholders in a Microsoft Word (`.docx`) resume template with user-provided details such as **name, phone number, and email address**.

It is designed to help **professionals** quickly generate personalized profile summaries or resumes without manually editing Word documents.

This project demonstrates:

* Python automation skills
* Practical use of external libraries
* Real-world document processing
* Clean and reusable code structure

---

## 🎯 Use Case

Imagine you have a **resume or profile summary template** with placeholders like:

```
{name}
{phone}
{email}
```

Instead of opening the document and editing it manually every time, this script:

1. Takes user input from the terminal
2. Replaces placeholders automatically
3. Generates a new updated Word document

✅ Ideal for:

* Resume automation
* Profile summary generation
* HR / recruitment workflows
* Data analyst portfolio projects

---

## 🛠️ Technologies Used

* **Python 3**
* **python-docx** (for Word document processing)

---

## 📂 Project Structure

```
resume-template-automation/
│
├── main.py              # Python script for placeholder replacement
├── template.docx        # Word template with placeholders (user-provided)
├── output.docx          # Generated document after replacement
├── README.md            # Project documentation
```

---

## 📌 Placeholders Format

Your Word document (`.docx`) should contain the following placeholders or you can change the placeholder according to your need:

| Placeholder | Description    |
| ----------- | -------------- |
| `{name}`    | Full Name      |
| `{phone}`   | Contact Number |
| `{email}`   | Email Address  |

⚠️ **Important:** Placeholders must exactly match the format shown above.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/resume-template-automation.git
cd resume-template-automation
```

### 2️⃣ Install Required Library

```bash
pip install python-docx
```

---

## ▶️ How to Run the Script

1. Update the file paths inside the script:

```python
input_file = r"PATH_TO_TEMPLATE_FILE.docx"
output_file = r"PATH_TO_OUTPUT_FILE.docx"
```

2. Run the script:

```bash
python main.py
```

3. Enter details when prompted:

```
Enter name: John Doe
Enter phone number: +92-300-1234567
Enter email: johndoe@email.com
```

4. 🎉 Your updated document will be saved successfully.

---

## 🧠 Code Explanation (High Level)

* `replace_placeholders()`
  Iterates through document paragraphs and replaces placeholders with user input.

* `main()`
  Handles:

  * User input
  * Placeholder mapping
  * File loading and saving

This modular approach makes the script **easy to extend** in the future.

---

## 🔮 Future Enhancements

This project can be expanded to include:

* Multiple resume sections (skills, experience, education)
* PDF export functionality
* Integration with ATS systems

---

## 👤 Author

**Muhammad Abssar Hussain**
📊 Data Analyst | Python Automation Enthusiast

📧 Email: *abssarh@gmail.com*

---

## 📜 License

This project is open-source and available under the **MIT License**.
Feel free to use, modify, and share.

---

# Filed_replacer_in_Doc
Take input from user and replace that text into the doc
