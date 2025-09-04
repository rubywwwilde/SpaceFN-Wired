# SpaceFN Karabiner Configuration - Accessibility-Focused Layout

## Why SpaceFN?

Have you heard of those fancy ergonomic keyboards that let you create multiple layers? They usually have special keys that activate different layers, so you can access tons of functions without moving your hands much, which supposedly minimizes muscle strain.

I had one of those too - a Dygma Raise. It's really good, but pricey as hell, and not exactly practical when you want to use it while traveling or lying in bed. That frustrated me, so I started researching how to add an extra layer to any keyboard through software. That's how I discovered SpaceFN.

I'm super grateful to [tshu-w](https://github.com/tshu-w) who created the original SpaceFN modification for Karabiner-Elements, an app for macOS that lets you do all sorts of keyboard magic.

## What I Changed and Why

tshu-w's SpaceFN layout was good, but it didn't quite solve my problem. I needed to minimize hand movement from the home row. I'm partially paralyzed - I can move my hands freely, but when you move them, you actually engage a lot of other muscles throughout your body. So efficiency isn't just about speed for me, it's mainly about reducing fatigue.

### The Core Layout Philosophy

The main idea behind my layout is simple:
- **Left hand = all modifiers** (A→Control, S→Shift, D→Option, F→Command, G→Hyper)  
- **Right hand = navigation** (H,J,K,L for arrows, Vim-style)

Why? Because most text editing operations use Shift, Option, Cmd, and Control combined with arrow keys. Having modifiers on the left and navigation on the right means you can do these combos naturally without awkward hand positions.

### What's Included in This Configuration

**Navigation & Editing:**
- Space+HJKL → Arrow keys (Vim-style navigation)
- Space+Backspace → Forward Delete
- Space+N → Enter (I prefer this one)
- Space+' → Enter (Alternative)

**Modifier Keys (Left Hand Home Row):**
- Space+A → Control
- Space+S → Shift  
- Space+D → Option
- Space+F → Command
- Space+G → Hyper (all modifiers at once)

**Function Keys:**
- Space+[1-9,0,-,=] → F1-F12

**Special Characters:**
- Space+E → Escape
- Space+M → Backtick (`)
- Space+, → Tilde (~)
- Space+B → Space (for when you need spaces while holding Space)

**Power User Shortcuts:**
- Space+W → Control+W (window/tab management in vim)
- Space+[1-0] → Cmd+Shift+Alt+[1-0] (customizable app shortcuts)

**CapsLock Multi-Function Key:**
- Tap CapsLock → Escape
- Hold CapsLock → Control  
- Shift+CapsLock → Regular CapsLock (for when you need to YELL)

The Control key on Mac is in a terrible position - you have to twist your pinky awkwardly to reach it. Shift, Option, and Cmd are pretty accessible, but Control? Nope. And Control is used constantly in terminal and Vim (Ctrl+U, Ctrl+D for page navigation, Ctrl+C to exit, etc.). Making CapsLock dual-function solves this beautifully.

### Additional

- Space+I/U/O → Homerow app shortcuts
  [Homerow](https://github.com/nchudleigh/homerow) is another fantastic app that helps a lot. It allows you to click on any clickable element on the page.

## Make It Your Own

You can tweak this however you want. Want WASD-style navigation instead of Vim? Want different modifier positions? Just edit the JSON. AI tools are surprisingly good at helping with these modifications - just tell them what you want to change.

The point is: you don't need expensive hardware to have an ergonomic, efficient keyboard setup. You just need Karabiner-Elements and some configuration.
