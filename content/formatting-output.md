---
author: ["Mark Beachill"]
title: "Reformatting chatbot output for Word"
date: "2025-03-23"
description: "Reformatting chatbot output for Word"
summary: "Reformatting chatbot output for Word"
tags: ["markdown", "syntax" ]
categories: ["prompts", "introduction"]
series: ["Prompts Guide"]
ShowToc: true
TocOpen: true
social:
  fediverse_creator: "@mark@mark.social"
---

----------

## How to Install the `ApplyFormatting` Macro in Microsoft Word

### 1. Open Microsoft Word

Start Microsoft Word and open a document (a blank one is fine).

### 2. Enable the Developer Tab (if it’s not already visible)

-   Go to the **File** menu and select **Options**.
    
-   In the **Word Options** window, select **Customize Ribbon**.
    
-   On the right side, check the box labeled **Developer**.
    
-   Click **OK** to close the options.
    

### 3. Open the VBA Editor

-   Go to the new **Developer** tab in the ribbon.
    
-   Click the **Visual Basic** button.
    

### 4. Add the Macro Code

-   In the VBA editor window, find your document or the "Normal" project in the panel on the left.
    
-   Right-click on **Modules** (or right-click the project name), then choose **Insert > Module**.
    
-   A new module will appear (like "Module1").
    
-   In the large editor pane on the right, paste in the code from the GitHub page.
    

You can get the macro code from:  
[https://github.com/markbeachill/reapply-normal/blob/main/reapply-normal-word-macro-chatgpt-formatting](https://github.com/markbeachill/reapply-normal/blob/main/reapply-normal-word-macro-chatgpt-formatting)

Paste everything from:

```vba
Sub ApplyFormatting()

```

down to the end of the macro.

### 5. Save the Macro

-   Press **Ctrl+S** to save.
    
-   Close the **VBA Editor** window.
    

----------

## How to Run the `ApplyFormatting` Macro in Microsoft Word

### Option 1: Use the Developer Tab

-   Go to the **Developer** tab.
    
-   Click the **Macros** button.
    
-   Select **ApplyFormatting** from the list.
    
-   Click **Run**.
    

### Option 2: Assign a Keyboard Shortcut (optional)

-   Go to **File > Options**.
    
-   Click **Customize Ribbon**, then click the **Customize** button next to "Keyboard shortcuts".
    
-   Under **Categories**, select **Macros**.
    
-   Select **ApplyFormatting** in the list on the right.
    
-   In the **Press new shortcut key** box, type a shortcut (like Ctrl+Alt+F), then click **Assign**.
    

----------

## Notes

-   If Word displays a security warning about macros, click **Enable Content** to allow the macro to run.
    
-   This macro applies consistent formatting based on the Normal style, helping to clean up formatting copied from other sources.
    

