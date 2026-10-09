# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Abdulrhman Suliman AlQasimi] |
| **Student ID** | [444050388] |
| **University Email** | [444050388@std.psau.edu.sa] |
| **GitHub Username** | [Abdulrahman-Qasimi] |
| **Repository Link** | [https://github.com/Abdulrahman-Qasimi/OS-Assignment1-444050388-Abdulrahman-AlQasimi] |
 
---

## 🎥 Video Link

**Video Link**: [(https://drive.google.com/file/d/1UTmhfXG_43Y74t2zj1QtHFchYrw8CooN/view?usp=sharing)]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [04/10/2026 05:44]
**What I did**: made Github account and forked repository and made 3 commits today about (ID as a seed, priority).

**Details**:
Created the account using university email, then used Fork to the main assignment,
made the first feature priority as an int and using random as value and made a getter,
and print the number based priority for each task, 

**Challenges**:
Seeing the visual codes of colors and Hashmap trying to find where i should add the context Switch Count increases, 

**Solution**:
I got somewhat familiar with it the colors and tried to add and change of my own code in Visual Studio,


**Time spent**:
~20 Minutes 
---

### Entry 2 - [04/10/2026 | 7PM]
**What I did**:
worked on the 2nd feature which is a context switch counter 

**Details**:
I have made the context switch and declared context switch counter inside the Scheduler Simulation  and set the stating value as 0,
and i add value to context switch counter inside while loop in the main ad lastly add system.out.println to make sure that context switch count works 

**Challenges**:
to find the right place to add to the context switch counter

**Solution**:
For Context switch count I followed the code trying to find where could be a reasonable place and found it better under while loop when adding in queue. 

**Time spent**:
~15
---

### Entry 3 - [07/10/2026 9PM]
**What I did**: 
I wrote about Waiting time function,
so we now are able to know how much the task has been in the ready queue and the total turn around time. 

**Details**:
First I searched for how to add a table to easily view the time spent in each part to know the burst, waiting, and the turnaround in milli Seconds,
then I put update Waiting time in  2 places one in the Run() and the other in RunToCompletion(),
I add New Getters functions like get waiting time and get turnaround time and mark ready and update waiting time.

**Challenges**:
Understanding where to add update waiting time.

**Solution**:
first time it runs and if it returns to ready queue then run to completion are the places to get the time right.

**Time spent**:
~30
---


### Entry 4 - [Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

### Entry 5 - [Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [1.5 hours]

**Most challenging part**: implementing waiting Time.

**Most interesting learning**: the use of thread start and join.

**What I would do differently next time**: I would read more carefully then code. 

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[From this assignment I now learned how multithreading works,
I saw how to use runnable and create new thread to make the program run on and we used thread.start() . 
The use of thread.join() that is because the main thread has to wait until the current process finishes its quantum before moving to another one, this made  me visualize the idea of multithreading and made it easy to repeat and understand,
and I used priority field, context switch counter, now I know how threads take turns using the cpu in Round robin.
.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[For me the most challenging part in the whole assignment was add or rather implementing the waiting time tracking,
Yes I had to use System.currentTimeMillis() I had to make sure that was updated in the correct times only which to trial and error, at the beginning I add the methods outside the Process class not focusing on where the class ends,
which caused me a lot of time trying to find the problem in my code when it was the getters that are out of the class, it has been a long time since I last used arryList and i wrote it wrong 2 times, but at last everything now works.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[To be honest i found the Readme helped in big details the challenges I faced were based on my coding and me not being focused enough, But from the start of using Visual studio and understanding the code that was already there i tried to see what can i understand before adding the required features,
i used system.out.println to see the priority is working as intended.
but there was something out of my understanding which is the date on the commit i thought it meant each commit for the same day different times but from where i see it it was my mistake of not understanding before committing.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[I have made a project about a community service app that helps many places like a mosque that needs Bakhur water or even Quran or a park for kids to play needs maintaining of the swings and cleaning, Multithreading can help
to load many donation and volunteers without freezing and ease of use for both the volunteer and the one in need,
one thread can handle the list of needs while another thread updates the user location to show nearby request.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[in the code already there there is a class named Process and for my understanding it is there for simulating a real process but in real run of the code Java thread is used here, 
we used thread(Process) because threads are cheap and lighter and they share the same memory space unlike making different processes, and make multithread makes communication between them are easy because they run on the same process, and thread has three functions to control them we have start() and join(), sleep() .]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[in Round robin scheduling, when a process dose not finish  in it is time quantum, it is put bac into the ready queue to wait fore it is next turn, in my program using my ID the outputs came out with p11 (and p10, p7, p4) was added to ready queue 3 times which means it was re queued 2 time before it was finished. 
In term of fairness these process has large burst time and getting them in and out of is fair because it stops these long processes from keeping the CPU to them self  and gives the other process a chance to run.]

Example from my output:
```
[(https://img.sanishtech.com/u/b1b90a4888b4156e66b2fed3be1eecc9.png)]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?] 
A: P1 is created inside of add processToQueue() the line Thread Thread = new thread(process);
2. **Runnable**: [When does P1 become Runnable?]
A: P1 becomes runnable when we call currentThread.start() in the scheduler loop after start
3. **Running**: [When is P1 Running?]
A: p1 is running when it is call the Run() method 
4. **Waiting**: [When and why would a thread be Waiting?]
A:  p1 can use thread.sleep() to make it wait or even the use of currentThread.join() 
5. **Terminated**: [When is P1 Terminated?]
A: p1 is terminated when it finishes it work or after runToCompletion() ends


## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Community service app]

**Description**:
[In this community service app different communities needs water clothes free cleaning services, 
the idea can be transferred into processes,  time quantum can be the short time the app spends loading or updating one request before moving to the next, A context switch happens when the app stops workig on one needs and starts showing or updating another.]

**Why Round-Robin works well here**:
[round robin works here very nicely, it keeps the app responsive so the user does not feel the screen freezing while many requests are loading it also gives ever community need of fair chance to be shown and updated]

### Example 2: [mobile operating system ]

**Description**:
[on a smartphone many apps run at the same time like WhatsApp, Youtube, maps, the mobile operating system gives ech app a short time slice on the CPU then switches to the next app in our simulation each process is like one running app the time quantum is the short time the phone gives to each app and the context switch is when the phone moves from one app to another.]

**Why Round-Robin works well here**:
[It keeps the phone responsive so the user still opens apps and receive notifications quickly it also fair because no single app can freeze the whole phone by using the CPU all the time.]

## Summary

**Key concepts I understood through these questions:**
1.The difference between a simulated Process and a real Java Thread, and how we create the thread with new Thread(process).
2.How Round-Robin works with the ready queue and why processes are re-queued for fairness.
3.The thread lifecycle New to Runnable to Running to Waiting to Terminated and the role of start(), join(), and sleep().

**Concepts I need to study more:**
1.More advanced thread synchronization (like wait/notify or locks) beyond basic start and join.
2.How the operating system schedules threads when many programs are open.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
