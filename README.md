# Nowou

![In-app screenshot](https://flowscious.com/assets/email-assets/ver-2/images/productivity-app/in-app/timeline-1.jpg "Wide screenshot of the web app.")

    Developer's note:
    
    This project is currently deployed, but the code is closed-source. If I ever choose to make this a public project, I will publish everything here in this repository.

> ⚠️ **NOTE**  
> This web app is a work in progress! The Flowscious platform consists of a single person working on many projects.

## Introduction

Click **[here](https://flowscious.com/nowou)** to explore the deployed web app 🔥

> ✔️ Logging in is not required and it's completely free.

This is a fully interactive web app that allows you to build timelines, create to-do lists, animate text, and much more. All created 'blocks' can be placed, scaled, and locked onto a beautifully textured canvas. All assets are either photographed or hand-drawn/illustrated.

## Text Editor

Blocks share global systems such as calendar, text editor, to-do lists, note-taking, and more. Most of these are self-explanatory but here's a quick overview of the text editor.

> ✔️ **Tip**  
> In moments of confusion, look for the assistant icon (sitting creature) and he'll explain what to do!

The text editor (top bar) allows you to write, animate. and alter text. It activates automatically whenever you interact with a text area. Here are a few guidelines.

- Adjust the settings by dragging the sliders or using the available tools.
    - To continue writing, you’ll need to reselect the text.
- Press tab to create a new text item
    - For example, you can emphasize the first letter by making it a separate altered item.

## Blocks

### 🕔 Timelines

The most feature-rich block is the timeline. This block converts time into **percentages** by using a start and end date. It's also mounted with globally recognized features such as to-do lists, note-taking, animated text, and more. These elements exist inside each block.

> ✔️ **TIP**  
> You can easily check if an element contains data by viewing the small green progress bar. This bar serves as an indicator, showing when the limits are reached.

#### Default Timeline

When visiting the app for the first time, a default daily timeline is created automatically. This is a special block that cannot be deleted.

Examples:

- 00:00 = **0%**
- 12:00 = **50%**
- 23:59:59 = **100%**

#### ➕ Add a Timeline

1. Create a timeline
2.  Click on the settings icon to open the calendar.
    - Choose a start and an end date.
3. Click on 'More settings'
    - Here you can customize the timeline as you see fit.
4. Add time ranges (just click on the timerange area or the '+' button)
    - These can be dragged around and each timerange is also mounted with the globally recognized elements. 
    - For example, you can split up a deadline into multiple segments.
5. Add alerts
    - Just click on the main progressbar to insert an alert at that location. 

### 🤯 Brainstorms

This is a powerful tool and **space-saver!** Just like an infinite image carousel looping in the background, you can use this similarly. 

Here's some examples of what you can add to a brainstorm

- Affirmations
- Favorite words
- Words you want to learn (perhaps other languages)
- Quotes

#### ➕ Add a Brainstorm

1. Simply create a brainstorm and start adding items. 
    - Each item is its own small environment where you can animate your text however you like. 
2. Drag and drop your items to alter the order in which they will appear.
3. Choose how many seconds they should be visible before the next item will show.
4. Close the block and drag it wherever you want on the canvas. 
    - You can also adjust its size and scale if you want.

### 🖊️ Text Blocks

There are two text blocks to choose from one transparent, and another one with a more cinematic feel. These are more simplistic, you can use them if you just want to add text to the canvas. 

## Performance

### Optimized Rendering

One of the most powerful performance features in **Nowou** is the built-in rendering optimization. As you may have noticed, each timeline requires a lot of re-renders when updating all the particles. To avoid unnecessary rendering, only the timelines visible on the screen are subjected to re-rendering. You can see this system in action when scrolling on the canvas. As you scroll, timelines will proactively wake up and fall to sleep as they enter and exit the view. This is a fully dynamic system, ensuring that only the components in view are using precious resources.

## ⛔️ Known Issues

- When creating an account, your previously created 'guest project' (if any) won't be transferred over to your account. It may appear as all your work is gone, but it's not! Just log out and your guest project will be loaded!
- There are one or two bugs when using the Brainstorm block and text editor. Please save often!
- There's no undo button, which can be frustrating sometimes.
- The text editor can be tough to work with and it's often challenging to select, erase, and focus.
- The app is not very pleasant to work with on mobile. 
- Blocks can be hard to organize when on top of each other.
- The default timeline gets stuck at 100% and a browser refresh is needed to reset.

## ✔️ What's Coming?

Aside from fixing the current issues, there's an ocean of updates on the way. I will not list everything here but here's a few short-term bullet points. Some of these are already done but not quite ready to be published yet. 

- General
    - Mobile and desktop app
    - Email and other types of notifications
    - Followers, public projects, etc.
    - More data indicators to see if data exist inside blocks.
    - More feature-rich todo's 
    - 'Boxes' than allows you to loosely detach elements and items from blocks, to easily put content aside temporarily.
- Projects
    - Create multiple projects
    - Import projects
- Canvas
    - Zoom and scale entire projects
- Timelines
    - Reset control (weekly, monthly, etc)
    - Higher resolution (zoom into timelines)
    - More 'timerange control'.  
- Blocks
    - Copy, paste, select, and group blocks
    - Images
    - Curves
    - Shapes
    - Drawings
    - Etc.
