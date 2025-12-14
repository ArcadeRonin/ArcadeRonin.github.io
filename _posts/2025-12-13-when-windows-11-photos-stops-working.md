---
title: "When Windows 11 Photos Stops Working: A Practical Alternative"
categories: [it, desktop-support]
---

### The Problem

### <span class="handwritten-pencil zine-highlight">The Problem</span>

### <span class="handwritten-felt zine-underline">The Problem</span>

### <span class="handwritten-felt zine-highlight zine-underline">The Problem</span>

### <span class="handwritten-felt zine-underline-wavy">The Problem</span>



Windows 11’s built-in apps are convenient until they aren’t. An app that has recently begun to cause us trouble at work is Photos. In some cases, Photos can become corrupted or partially broken, and frustratingly, the usual fixes don’t always work. Repairing the app, resetting it, uninstalling, or even reinstalling it from the Microsoft Store may fail to resolve the issue.

When this happens, our designers and customer service reps are left without a reliable way to open image files, which quickly becomes a customer experience nightmare and a productivity problem.


### Why This Is a Bigger Issue Than It Looks

For many businesses, image viewing isn’t optional. Our company frequently receives photos from customers, and a large portion of those images are in **HEIC** format. HEIC (High Efficiency Image Container) is the standard photo format used by iPhones, so this isn’t an edge case for us. It’s everyday business as usual.

On Windows, viewing HEIC files typically requires installing the HEVC/HEIC codec from the Microsoft Store. Microsoft charges a small fee for this because the underlying HEVC compression technology is covered by patent licensing. Individually, the cost is minor. At scale, the cost still doesn’t break the bank, but there is more to consider.

When you factor in:

- 60+ store locations  
- Multiple employees per store  
- The need for desktop support to manually install and pay for the codec on each device  

…it becomes clear that this approach doesn’t scale well.


### A Free, Open-Source Solution: nomacs

This is where **nomacs** comes in.

nomacs is a free, open-source image viewer for Windows 11 that:

- Works independently of the Windows Photos app  
- Supports common image formats out of the box  
- Supports **HEIC** files, including those taken on iPhones  
- Requires no Microsoft Store purchases or per-device licensing  

Because nomacs includes HEIC support via open-source libraries, it avoids the codec paywall entirely while still *just working* for end users.

You can find the project here: https://nomacs.org


### One Fix, Two Problems Solved

In environments where the Windows Photos app is broken:

- Replacing it with **nomacs** immediately restores image viewing  
- **HEIC** support is included, eliminating the need for paid codecs  

In other words, fixing the Photos problem with a reliable alternative also solves the HEIC problem at the same time.


### The Takeaway

Windows 11 default apps aren’t always as reliable as they should be, and when Photos breaks, it can be surprisingly hard to fix. For organizations that regularly handle iPhone photos, relying on paid codecs across dozens of locations is inefficient and, depending on scale, can be costly.

**nomacs** is a practical, free, and scalable solution. Sometimes, the simplest fix is replacing the broken piece entirely.

