# Magnet Tasks - DECO3500 Prototype

A dynamic, fruit-based task management application designed to help users organize and complete their tasks through an intuitive, visual interface.

## Overview

Magnet Tasks is an interactive web application that transforms task management into an engaging experience using fruits as visual indicators. Users assign tasks to fruits (pineapple, orange, grapes), set priorities, and track completion with real-time alarms and activity logs.

## Main Features

### Fruit-Based Task Management
- Assign tasks to specific fruits with due dates and times
- Visual representation with fruit emojis and sizes correlated to priority levels
- Track active tasks with real-time status updates
- Complete tasks by returning fruits to the basket

### Priority System
- **High Priority**: Large fruit size (🍍 Pineapple - preset)
- **Medium Priority**: Medium fruit size (🍊 Orange - preset)
- **Low Priority**: Small fruit size (🍇 Grapes - preset)
- Visual size differences make priorities instantly recognizable

### Admin Mode
- Access additional features and extra fruits (Apple, Banana, Strawberry)
- Add extra fruits to the main screen for expanded task capacity
- Manage and control all tasks
- Silence all alarms with one click
- View detailed activity statistics and logs

### Real-Time Alarms
- Audio notifications when tasks become overdue
- Visual shaking and coloring for overdue tasks
- Automatic alarm stopping when tasks are completed
- Admin control for silencing all alarms

### Activity Tracking
- Complete log of all actions and task completions
- Real-time updates across all browser tabs
- Detailed statistics for active, overdue, and completed tasks
- Activity log visible in both normal and admin modes

## How to Use

### Main Screen
1. **Pick a fruit** from the basket (Pineapple, Orange, or Grapes)
2. **Click the fruit** to assign a task
3. **Fill in the form**:
   - Enter your name
   - Task description
   - Due date and time (or choose "due in" minutes)
4. **Save** to activate the task
5. **Complete tasks** by returning fruits to the basket

### Admin Mode
1. Click the **"Admin"** button in the header
2. Click **"Enter Admin Mode"** (no password required in this version)
3. Access additional features:
   - Add extra fruits (Apple, Banana, Strawberry) to the main screen
   - View activity statistics
   - Manage all tasks
   - Silence alarms
4. Extra fruits have a **golden border** and can be returned to admin by double-clicking

### Task Features
- **Search**: Filter tasks by keyword
- **Filter by Priority**: View tasks by High, Medium, Low, or No priority
- **Alarms**: Overdue tasks automatically trigger audio alarms
- **Activity Log**: See all actions in real-time
- **Monitor Window**: Open a separate monitor window for tracking fruits not returned

## Visual Indicators

- **Fruit Size**: Correlates with priority (large = high, small = low)
- **Golden Border**: Admin-added fruits can be returned
- **🔙 Icon**: Return to admin (double-click admin fruits)
- **OUT Badge**: Fruit is currently assigned to an active task
- **Priority Pills**: Color-coded (Red=High, Yellow=Medium, Green=Low)
- **Shaking Effect**: Overdue tasks shake continuously

## Admin Mode Features

### Extra Tasks Section
- 🍎 Apple (High priority preset)
- 🍌 Banana (Medium priority preset)
- 🍓 Strawberry (Low priority preset)
- Click to add any available fruit to the main screen
- Once added, assign tasks normally
- Double-click on the main screen to return to admin

### Activity Overview
- View statistics: Active Tasks, Overdue, Completed Today, Total Fruits
- Toggle detailed activity log
- Refresh stats in real-time

### Task Management
- Bulk complete all overdue tasks
- Extend all active tasks by 1 hour
- Force return fruits from admin panel
- Silent all alarms globally

## Alarm System

- **Audio Alerts**: Plays when tasks become due
- **Auto-Stop**: Alarms stop when tasks are completed or fruits are returned
- **Admin Control**: Silence all alarms from admin panel
- **Return Control**: Returning admin fruits stops their alarms
- **iOS Support**: Enhanced audio volume for mobile devices

## Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-featured experience with all visual effects
- **Tablet**: Adaptive layout with optimized touch interactions
- **Mobile**: Compact design with mobile-specific adjustments

## Technical Features

- **Local Storage**: All tasks and fruits persist across sessions
- **Cross-Tab Communication**: Real-time updates across browser tabs
- **Web Audio API**: Custom alarm sounds with iOS compatibility
- **Date/Time Handling**: Local timezone-aware scheduling
- **Dynamic Layout**: Basket adjusts automatically based on fruit count

## Quick Start Guide

### For Teachers - 5 Simple Steps

1. **Download the project:**
   - Go to: https://github.com/sahajdeep31/DECO3500-balanced-Bites
   - Click the green **"Code"** button
   - Click **"Download ZIP"**

2. **Extract the ZIP file:**
   - Double-click the ZIP file to extract it
   - You'll see a folder named `DECO3500-balanced-Bites`

3. **Open Terminal in that folder:**
   - **Mac**: Right-click the folder → "Open Terminal Here" or drag folder into Terminal
   - **Windows**: Open Command Prompt in the folder (Shift + Right-click → "Open PowerShell window here")

4. **Start the server:**
   ```bash
   python3 -m http.server 8000
   ```
   
   *On Windows, use:*
   ```bash
   python -m http.server 8000
   ```

5. **Open in browser:**
   - Go to: http://localhost:8000
   - The application will load!

**That's it!** Now you can start exploring the Magnet Tasks application.



