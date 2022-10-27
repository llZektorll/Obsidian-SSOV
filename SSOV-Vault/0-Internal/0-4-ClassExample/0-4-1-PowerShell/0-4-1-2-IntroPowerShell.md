---
created: "2022-10-22 at 18:10"
aliases: "📜 - Class Note: Introduction to PowerShell"
tags: 
- "Course/IntoPowerShell/Note"
011Version: 1.0
---
---
# ❗❓ Information
Related to Course:: [[0-4-1-1-PowerShellIndex|🏫 - Class: Automate administrative tasks by using PowerShell]]
Date:: 2022-10-22
Tags:: #Programming #PowerShell #Microsoft #Microsoft/Learn
Speakers:: None

---
# ❗ Topic
- Learn about the basics of PowerShell. This cross-platform command-line shell and scripting language is built for task automation and configuration management. You'll learn basics like what PowerShell is, what it's used for, and how to use it.
 ---
## 📦 Resources
- [Lecture Information](https://learn.microsoft.com/en-us/training/modules/introduction-to-powershell/)
## 🔑 Key Points
- What is PowerShell
- Locate Commands
## ❓ Prerequisites
- None 
## ❓ Q & A
1. What is PowerShell ?
	1. PowerShell consists of two parts: a command-line shell and a scripting language. It started out as a framework to automate administrative tasks in Windows. PowerShell has grown into a cross-platform tool that's used for many kinds of tasks.
2. How to locate commands ?
	1. When you run the `Get-Command` cmdlet in PowerShell, you get a list of every command that's installed in PowerShell. Because thousands of commands are installed, you need a way to filter the response so you can quickly locate the command that you need.
## 🎯 Learning objectives
- [ ] Understand what PowerShell is and how it works
## 📃 Summary of Notes
- PowerShell is a command-line shell and a scripting language all in one. It was designed as a task engine that uses cmdlets to wrap tasks that people need to do. In PowerShell, you can run commands on local or remote machines. You can do tasks like managing users and automating workflows.
- A [[0-6-1-CMDLET|💬 - CMDLET]] (pronounced "command-let") is a compiled command. A [[0-6-1-CMDLET|💬 - CMDLET]] can be developed in .NET or .NET Core and invoked as a command within PowerShell. Thousands of cmdlets are available in your PowerShell installation. The challenge lies in discovering what they are and what they can do for you.
- [[0-6-1-CMDLET|💬 - CMDLET]] are named according to a verb-noun naming standard. This pattern can help you to understand what they do and how to search for them. It also helps [[0-6-1-CMDLET|💬 - CMDLET]] developers create consistent names. You can see the list of approved verbs by using the `Get-Verb` cmdlet. Verbs are organized by activity type and function.
![[Pasted image 20221022195457.png]]