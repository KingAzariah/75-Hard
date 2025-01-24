# 75 Hard Challenge Tracker

## Overview
The 75 Hard Challenge Tracker is a simple web application designed to help users track their daily progress for the 75 Hard Challenge. It ensures that users stay consistent with all the challenge rules and provides feedback on completion.

## Features
- Tracks the following daily tasks:
  - Followed a nutrition plan
  - Completed two 45-minute workouts
  - Drank a gallon of water
  - Read 10 pages of a nonfiction book
  - Took a progress picture
- Displays a success or failure message based on the completion of all tasks.
- Redirects to separate pages (`success.html` and `failure.html`) for positive or negative feedback.
- Clean and responsive design with a red, black, grey, and white color scheme.

## File Structure
- `index.html`: The main tracker page where users can input their progress.
- `success.html`: Displays a congratulatory message for completing the challenge.
- `failure.html`: Displays a message to try again when tasks are not completed.
- `README.md`: Documentation for the project.

## How to Use
1. Open `index.html` in a web browser.
2. Check off the tasks as you complete them for the day.
3. Click the **Submit** button.
   - If all tasks are completed, you will be redirected to `success.html`.
   - If any tasks are incomplete, you will be redirected to `failure.html`.
4. Use the navigation link on the success or failure page to return to the tracker.

## Customization
### Colors
The app uses a dark theme with red, black, grey, and white colors. You can modify the styles in the `<style>` section of each HTML file to match your preferences.

### Success and Failure Pages
The `success.html` and `failure.html` pages contain customizable messages. You can edit the content to personalize the experience.

## Requirements
- A modern web browser.
- No additional dependencies or frameworks are needed.

## Future Enhancements
- Add persistence using local storage to save daily progress.
- Include a progress history to track multiple days.
- Integrate a timer for workouts.
- Add mobile-friendly enhancements.

## License
This project is open-source and available for modification and distribution.

