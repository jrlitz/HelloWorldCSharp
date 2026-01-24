# 🚀 C# Hello World Project

## Lesson Snapshot
Build your first C# program that shows welcome messages on the screen. (Ages 8-18)

## Folder & File Map
```
HelloCoderDojo/
├── .git/
├── HelloCoderDojo.csproj
└── Program.cs
```

## Step-by-Step Build Guide

### 1. Fork and Clone the Repository ✅
- **What to do**: Go to https://github.com/PhillyCoderDojo/HelloWorldCSharp → Click "Fork" button in top right → Then open GitHub Desktop → Click "Clone a repository from the Internet" → Select your fork → Choose a location on your computer → Click "Clone"
- **Where we're working**: Making your own copy of our starter project, like getting your own LEGO set that matches the teacher's
- **Code snippet**: None
- **Why it matters**: This gives you your own version of the project to change without affecting the original, just like saving a game to your own memory card
- **Git command**: `git clone https://github.com/YOUR-USERNAME/HelloWorldCSharp.git`
- [**Documentation Link**](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
- **📸 SCREENSHOT**: 
![Rider](https://github.com/user-attachments/assets/e2ce6bf6-8f47-42ca-95e6-11ae700e011a)

![Rider](https://github.com/user-attachments/assets/09281c21-225a-43f5-a52d-8cdaa2a06633)


### 2. Open Repository Folder ✅
- **What to do**: Find and open the folder you just created for your repository
- **Where we're working**: Looking inside your new project home
- **Code snippet**: None
- **Why it matters**: We need to see where our code will live
- **Git command**: `cd HelloCoderDojo`
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/b2d886ea-364b-42c8-b6da-d20afbc909d1)
![Visual Studio – repo folder open](fwdhelloworldctutorial/Screenshot%202026-01-22%20214801.png)

### 3. Launch JetBrains Rider ✅
- **What to do**: Find Rider in your Start Menu/Applications folder and open it
- **Where we're working**: Starting up our coding tool
- **Code snippet**: None
- **Why it matters**: We need our coding workshop to start building
- **Git command**: None
- **📸 SCREENSHOT**:
![Rider](https://github.com/user-attachments/assets/b1336430-3f36-477c-b5d8-b718a0127b49)
![Visual Studio – start page](fwdhelloworldctutorial/Screenshot%202026-01-19%20130619.png)

### 4. Create New Project ✅
- **What to do**: Click "New Solution" on the welcome screen
- **Where we're working**: Setting up our coding project
- **Code snippet**: None
- **Why it matters**: This is like starting a new LEGO set with instructions
- **Git command**: None
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/78ab7e24-c5ed-4a94-ad60-01ce7a46d0b1)
![Visual Studio – New Project dialog](fwdhelloworldctutorial/Screenshot%202026-01-19%20130744.png)
![Visual Studio – Project details](fwdhelloworldctutorial/Screenshot%202026-01-19%20130805.png)
![Visual Studio – Location selection](fwdhelloworldctutorial/Screenshot%202026-01-19%20131438.png)


### 5. Set Up Console App ✅
- **What to do**: Select "Console Application" → Name it "HelloCoderDojo" → Choose your repository folder as location → Select .NET 8.0 → Click Create
- **Where we're working**: Creating the blueprint for your program
- **Code snippet**: None
- **Why it matters**: Tells the computer what kind of program we're making
- **Git command**: None
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/3eb112a6-c162-49cd-bbcd-4b1f11d09d56)
![Visual Studio – Console template selected](fwdhelloworldctutorial/Screenshot%202026-01-19%20131534.png)
![Visual Studio – Framework selection](fwdhelloworldctutorial/Screenshot%202026-01-19%20131622.png)
![Visual Studio – Create project confirmation](fwdhelloworldctutorial/Screenshot%202026-01-19%20131712.png)
![Visual Studio – Solution view](fwdhelloworldctutorial/Screenshot%202026-01-19%20131733.png)

### 6. Create a .gitignore File ✅
- **What to do**: In your project folder, create a new file named ".gitignore"
- **Where we're working**: Making a special list that tells Git which files to ignore
- **Code snippet**:
```
# Build results
[Dd]ebug/
[Dd]ebugPublic/
[Rr]elease/
[Rr]eleases/
x64/
x86/
[Bb]in/
[Oo]bj/
[Ll]og/
[Ll]ogs/

# Visual Studio / Rider files
.vs/
.idea/
*.suo
*.user
*.userosscache
*.sln.docstates
*.userprefs

# .NET Core
project.lock.json
project.fragment.lock.json
artifacts/

# NuGet Packages
*.nupkg
*.snupkg
**/[Pp]ackages/*
!**/[Pp]ackages/build/

# MSTest test Results
[Tt]est[Rr]esult*/
[Bb]uild[Ll]og.*

# Files built by Visual Studio
*_i.c
*_p.c
*_h.h
*.ilk
*.meta
*.obj
*.pch
*.pdb
*.ipdb
*.pgc
*.pgd
*.rsp
*.sbr
*.tlb
*.tli
*.tlh
*.tmp
```
- **Why it matters**: Keeps your project clean by not tracking files that your computer creates automatically
- **Git command**: None yet
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/6805e630-177c-4feb-9f16-f9dd736b363f)
![Rider](https://github.com/user-attachments/assets/9ef9c78b-4c63-4ff5-8c32-b94e193ac923)

### 7. First Commit ✅
- **What to do**: Go back to GitHub Desktop → Review changes → Enter "Initial project setup" as commit message → Click "Commit to main"
- **Where we're working**: Saving your project's starting point
- **Code snippet**: None
- **Why it matters**: Like taking a snapshot of your LEGO creation so far
- **Git command**: `git add . && git commit -m "Initial project setup"`
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/36fd29e6-1d84-460f-8b55-9495147e7efb)


### 8. Explore Your Project ✅
- **What to do**: In Rider, look at Solution Explorer (usually on the left side)
- **Where we're working**: Looking at all the pieces of your project
- **Code snippet**: None
- **Why it matters**: Finding all the parts we need to build with
- **Git command**: None
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/f75ecc15-7c89-4202-a72c-98b0319d9b54)
![Visual Studio – Solution Explorer](fwdhelloworldctutorial/Screenshot%202026-01-19%20131923.png)


### 9. Find Program.cs ✅
- **What to do**: Double-click on Program.cs in Solution Explorer
- **Where we're working**: Opening the main file where we'll write our code
- **Code snippet**: None
- **Why it matters**: This is your blank canvas for writing instructions
- **Git command**: None
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/9e8e4cf8-c277-4d2c-b136-dd107527288a)
![Visual Studio – Open Program.cs](fwdhelloworldctutorial/Screenshot%202026-01-19%20142240.png)


### 10. Write Welcome Messages ✅
- **What to do**: Delete any existing code and type these three lines
- **Where we're working**: Writing in the Program.cs file
- **Code snippet**:
```csharp
Console.WriteLine("Hello, Philly CoderDojo!");
Console.WriteLine("Welcome to C# programming!");
Console.WriteLine("Today is Saturday, June 14, 2025");
```
- **Why it matters**: Telling the computer what words to show on screen
- **Git command**: None yet
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/8dc4d9da-6f6e-4e7b-a8a2-7f2750b28ab4)
![Visual Studio – Editing Program.cs](fwdhelloworldctutorial/Screenshot%202026-01-19%20142254.png)
![Visual Studio – Code entered](fwdhelloworldctutorial/Screenshot%202026-01-19%20142303.png)


### 11. Run Your Program ▶️
- **What to do**: Click the green ▶️ button at the top or press Ctrl+F5
- **Where we're working**: Testing your program to see if it works
- **Code snippet**: None
- **Why it matters**: See your program come to life!
- **Git command**: None
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/c414e792-02c5-4d18-a927-6fe01143221d)
![Visual Studio – Build succeeded](fwdhelloworldctutorial/Screenshot%202026-01-19%20142449.png)
![Visual Studio – Run output](fwdhelloworldctutorial/Screenshot%202026-01-19%20142756.png)
![Visual Studio – Output window](fwdhelloworldctutorial/Screenshot%202026-01-19%20142828.png)
![Visual Studio – Debug console](fwdhelloworldctutorial/Screenshot%202026-01-19%20143037.png)

### 12. Commit Your Changes ✅
- **What to do**: Go to GitHub Desktop → Review changes → Enter "Add welcome messages" as commit message → Click "Commit to main"
- **Where we're working**: Saving your progress in the magical notebook
- **Code snippet**: None
- **Why it matters**: Taking another snapshot of your work
- **Git command**: `git add Program.cs && git commit -m "Add welcome messages"`
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/4f27cbb5-7047-4e1b-b2fa-be16bb1dad88)
![Rider](https://github.com/user-attachments/assets/147b6d4d-f4d6-4671-9c5d-5087f347003d)
![Visual Studio – Commit view](fwdhelloworldctutorial/Screenshot%202026-01-19%20163637.png)

### 13. Make It Personal ✅
- **What to do**: Change the messages to include your information
- **Where we're working**: Changing the words in Program.cs
- **Code snippet**:
```csharp
Console.WriteLine("Hello, my name is [YOUR NAME]");
Console.WriteLine("I am [AGE] years old");
Console.WriteLine("I want to learn programming because [REASON]");
```
- **Why it matters**: Making the computer say things about YOU
- **Git command**: None yet
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/ac99a01d-7af1-4b25-8542-a2bf62a8c199)
![Visual Studio – Personalizing code](fwdhelloworldctutorial/Screenshot%202026-01-19%20163705.png)


### 14. Run Again ▶️
- **What to do**: Click the green ▶️ button again to see your changes
- **Where we're working**: Testing your personalized program
- **Code snippet**: None
- **Why it matters**: Making sure your changes worked correctly
- **Git command**: None
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/c3f2ba65-d43b-4163-99d4-a71dd61cfe11)
![Visual Studio – Re-run](fwdhelloworldctutorial/Screenshot%202026-01-19%20165107.png)
![Visual Studio – Console output](fwdhelloworldctutorial/Screenshot%202026-01-19%20165118.png)


### 15. Commit Personal Changes ✅
- **What to do**: Go to GitHub Desktop → Review changes → Enter "Add personal information" as commit message → Click "Commit to main"
- **Where we're working**: Saving your personalized version
- **Code snippet**: None
- **Why it matters**: Taking a snapshot of your customized program
- **Git command**: `git add Program.cs && git commit -m "Add personal information"`
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/6395321e-6aae-4085-875e-d10e6f6e7ab8)
![Visual Studio – Staging changes](fwdhelloworldctutorial/Screenshot%202026-01-19%20165256.png)
![Visual Studio – Commit confirmation](fwdhelloworldctutorial/Screenshot%202026-01-19%20165341.png)


### 16. Push to GitHub ✅
- **What to do**: In GitHub Desktop, click "Push origin" to upload all your commits
- **Where we're working**: Sending your project to the internet cloud
- **Code snippet**: None
- **Why it matters**: Backing up your code so it's safe forever
- **Git command**: `git push origin main`
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/805146c8-24cc-428d-bef9-7af1f54802ce)
![Visual Studio – Push to origin](fwdhelloworldctutorial/Screenshot%202026-01-22%20215050.png)
![Visual Studio – Publish dialog](fwdhelloworldctutorial/Screenshot%202026-01-22%20215059.png)
![Visual Studio – Publish complete](fwdhelloworldctutorial/Screenshot%202026-01-22%20215135.png)


## Run & Test ▶️
- Click the green ▶️ button in Rider or press Ctrl+F5
- You should see your messages appear in the console window
- **Common Error**: If you see red underlines, check for missing semicolons (;) at the end of each line
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/3cacd169-29bf-4d79-a083-e3ba648c25fd)
![Rider](https://github.com/user-attachments/assets/5359fd2b-d989-49a1-8b14-27ff67171dbc)


## Bonus Challenge 🔥
Make your program ask for the user's name and say hello to them!

**Hint**:
```csharp
Console.Write("What is your name? ");
string name = Console.ReadLine();
Console.WriteLine($"Hello, {name}!");
```
- **📸 SCREENSHOT**: ![Rider](https://github.com/user-attachments/assets/fb3a9389-683f-4d88-b11b-cc4743a564d6)

- **Git command**: `git add Program.cs && git commit -m "Add interactive name prompt"`

## IDE Screenshots
All images below are stored in `fwdhelloworldctutorial/`.
- Rider/GitHub Desktop: the tutorial images in the steps above (hosted via GitHub attachments).
- Visual Studio: the local captures below.

![Visual Studio – Screenshot 2026-01-19 130619](fwdhelloworldctutorial/Screenshot%202026-01-19%20130619.png)
![Visual Studio – Screenshot 2026-01-19 130744](fwdhelloworldctutorial/Screenshot%202026-01-19%20130744.png)
![Visual Studio – Screenshot 2026-01-19 130805](fwdhelloworldctutorial/Screenshot%202026-01-19%20130805.png)
![Visual Studio – Screenshot 2026-01-19 131438](fwdhelloworldctutorial/Screenshot%202026-01-19%20131438.png)
![Visual Studio – Screenshot 2026-01-19 131534](fwdhelloworldctutorial/Screenshot%202026-01-19%20131534.png)
![Visual Studio – Screenshot 2026-01-19 131622](fwdhelloworldctutorial/Screenshot%202026-01-19%20131622.png)
![Visual Studio – Screenshot 2026-01-19 131712](fwdhelloworldctutorial/Screenshot%202026-01-19%20131712.png)
![Visual Studio – Screenshot 2026-01-19 131733](fwdhelloworldctutorial/Screenshot%202026-01-19%20131733.png)
![Visual Studio – Screenshot 2026-01-19 131923](fwdhelloworldctutorial/Screenshot%202026-01-19%20131923.png)
![Visual Studio – Screenshot 2026-01-19 142240](fwdhelloworldctutorial/Screenshot%202026-01-19%20142240.png)
![Visual Studio – Screenshot 2026-01-19 142254](fwdhelloworldctutorial/Screenshot%202026-01-19%20142254.png)
![Visual Studio – Screenshot 2026-01-19 142303](fwdhelloworldctutorial/Screenshot%202026-01-19%20142303.png)
![Visual Studio – Screenshot 2026-01-19 142449](fwdhelloworldctutorial/Screenshot%202026-01-19%20142449.png)
![Visual Studio – Screenshot 2026-01-19 142756](fwdhelloworldctutorial/Screenshot%202026-01-19%20142756.png)
![Visual Studio – Screenshot 2026-01-19 142828](fwdhelloworldctutorial/Screenshot%202026-01-19%20142828.png)
![Visual Studio – Screenshot 2026-01-19 143037](fwdhelloworldctutorial/Screenshot%202026-01-19%20143037.png)
![Visual Studio – Screenshot 2026-01-19 163637](fwdhelloworldctutorial/Screenshot%202026-01-19%20163637.png)
![Visual Studio – Screenshot 2026-01-19 163705](fwdhelloworldctutorial/Screenshot%202026-01-19%20163705.png)
![Visual Studio – Screenshot 2026-01-19 165107](fwdhelloworldctutorial/Screenshot%202026-01-19%20165107.png)
![Visual Studio – Screenshot 2026-01-19 165118](fwdhelloworldctutorial/Screenshot%202026-01-19%20165118.png)
![Visual Studio – Screenshot 2026-01-19 165256](fwdhelloworldctutorial/Screenshot%202026-01-19%20165256.png)
![Visual Studio – Screenshot 2026-01-19 165341](fwdhelloworldctutorial/Screenshot%202026-01-19%20165341.png)
![Visual Studio – Screenshot 2026-01-22 214351](fwdhelloworldctutorial/Screenshot%202026-01-22%20214351.png)
![Visual Studio – Screenshot 2026-01-22 214407](fwdhelloworldctutorial/Screenshot%202026-01-22%20214407.png)
![Visual Studio – Screenshot 2026-01-22 214801](fwdhelloworldctutorial/Screenshot%202026-01-22%20214801.png)
![Visual Studio – Screenshot 2026-01-22 215050](fwdhelloworldctutorial/Screenshot%202026-01-22%20215050.png)
![Visual Studio – Screenshot 2026-01-22 215059](fwdhelloworldctutorial/Screenshot%202026-01-22%20215059.png)
![Visual Studio – Screenshot 2026-01-22 215135](fwdhelloworldctutorial/Screenshot%202026-01-22%20215135.png)
