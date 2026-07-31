========================================
  S.U.N.  —  your own AI, on your own PC
========================================

A window for talking to an AI that runs 100% on YOUR computer.
Nothing you say leaves your machine. It even remembers your past chats,
shows your computer's stats live, and has a glowing reactor that reacts
while the AI thinks. You can recolor and resize everything.


--------------------------------
WHAT YOU NEED (one time, all free)
--------------------------------
1. A Windows, Mac, or Linux computer.

2. PYTHON.
   Go to python.org, click the big Download button, run it.
   IMPORTANT: on the first install screen, CHECK the box that says
   "Add Python to PATH". (If you miss it, just install again and check it.)

3. OLLAMA — the free program that actually runs the AI.
   Go to ollama.com, click Download, install it.


-----------------
HOW TO START S.U.N.
-----------------
1. Put the file "sun_setup.py" anywhere. Your Documents folder is perfect.

2. Open a terminal:
   - Windows: press the Windows key, type  powershell  , press Enter.
   - Mac: open the app called  Terminal .
   - Linux: open your terminal.

3. Type this line and press Enter
   (if you didn't use Documents, change the path to where you put the file):

   Windows:     py "$env:USERPROFILE\Documents\sun_setup.py"
   Mac/Linux:   python3 ~/Documents/sun_setup.py

4. The FIRST time, it sets things up and downloads a small AI model.
   This takes a few minutes. Just wait — it only happens once.

5. Your web browser opens with S.U.N. Start typing. That's it!


---------------------
OPENING IT AGAIN LATER
---------------------
Run the same line from step 3. Everything starts back up.


--------------
MAKING IT YOURS
--------------
Click the gear (the little cog, top-right corner).
A panel slides out — change colors, reactor size, chat size, and more.
It remembers your choices automatically.


-----------
GOOD TO KNOW
-----------
- Runs on your computer ONLY. It does NOT send your chats anywhere.
  No account. No sign-up. No tracking. No internet needed once set up.

- Works with ANY model you have in Ollama. Have your own favorite?
  Pick it from the dropdown at the top. If you have none, S.U.N. offers
  to grab a small starter one for you.

- The GPU meter needs an NVIDIA graphics card. On other cards that ONE
  meter shows a dash — everything else works fine.

- Your chats are saved in a file called  sun_memory.db  next to the setup
  file. Want S.U.N. to forget everything? Just delete that file.


-------
STUCK?
-------
- App says "ollama offline"?
  Find the Ollama icon near your clock (bottom-right, maybe under the ^
  arrow). Right-click it, choose Quit. Then run the start line again.

- "python is not recognized"?
  Python wasn't added to PATH. Reinstall Python from python.org and
  CHECK the "Add Python to PATH" box on the first screen.

- Reactor is there but the AI won't answer?
  Make sure you have a model (dropdown at top isn't empty). If it is,
  run in a terminal:  ollama pull llama3.1:8b


Free to use and share. Made with love.

Like it? Tip jar:  https://ko-fi.com/1900prismx
