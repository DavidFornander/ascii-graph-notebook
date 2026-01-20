# README.md (Yes, this is ai)

```text
      __  __  __     __  _   _  ____  _____  _____  ____    ____    ____    __  __ 
     |  \/  | \ \   / / | \ | |/ __ \|_   _|| ____||  _ \  / __ \  / __ \  |  |/  |
     | \  / |  \ \_/ /  |  \| | |  | | | |  | |__  | |_) || |  | || |  | | |  ' / 
     | |\/| |   \   /   | . ` | |  | | | |  |  __| |  _ < | |  | || |  | | |    \ 
     | |  | |    | |    | |\  | |__| | | |  | |___ | |_) || |__| || |__| | | . . \
     |_|  |_|    |_|    |_| \_|\____/  |_|  |_____||____/  \____/  \____/  |_|\__|

                   [ TERMINAL OF THOUGHT ] [ RENDERER: ACTIVE ]

```

## 1. Welcome to the Lab

Welcome to my personal knowledge base. You won't find bloated JPEGs or heavy diagrams here. 

This notebook operates on a simple principle: **If you can understand it, you can render it in plain text.** 

- 1+1=2. Point proven. 

---

## 2. The "Pipe to ASCII" Philosophy

I use a custom workflow (*Literally just gemini 3 and good old unix*) to pipe any data into the utility. Then gemini renders it through the power of ascii. 

Here Gemini has prepared a little showcase of what it can do:

### Exhibit A: The Knowledge Graph (Zettelkasten)

*Visualizing how I connect atomic notes.*

```text
    [INPUT] -> ascii "Show me how notes connect"

          +------------------+
          |   (Root Note)    |
          +--------+---------+
                   |
         __________v__________
        /                     \
       |   THE NETWORK LAYER   |
        \_________+___________/
                  |
        +---------+---------+
        |                   |
  +-----v-----+       +-----v-----+
  | Concept A |<----->| Concept B |
  +-----------+       +-----------+

```

### Exhibit B: Mechanical Systems

*Explaining the physical world without a single pixel.*

```text
    [INPUT] -> ascii "How does a turbocharger work?"

       Exhaust Gas
          |
          v
      +-------+       (Shaft)       +-------+
      |TURBINE|=====================|COMPRSR|
      +---+---+      High Speed     +---+---+
          |                             ^
       Exhaust Out                 Cold Air In
                                        |
                                   Compressed Air
                                   to Engine ->

```

### Exhibit C: Logic & State

*Debugging decision trees.*

```text
[INPUT] -> ``` cat login-logic-flow.txt | ascii```
  
    [START] --> User Enters Creds
                     |
                     v
             < Is Valid? > ----NO----> [Throw Error 401]
                     |
                    YES
                     |
                     v
             [Generate Token] --> [Redirect to Dashboard]

```

---

## 3. Navigation

The notebook is organized by directory, but visualized as a tree:

```text
    .
    ├── 00_Meta/            # The Brain (Indexes)
    ├── 10_Journal/         # Daily Logs
    ├── 20_Concepts/        # The ASCII Art Gallery
    │   ├── Physics/
    │   └── Code/
    └── 99_Archive/         # Deprecated Thoughts

```

---

> *"The computer screen is not a window, it is a canvas of characters."*