# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS


COMPANY:CODTECH IT SOLUTIONS

NAME:EBIN ROSHAN.B

INTERN ID:CT04DH317

DOMAIN:FULL STACK WEB DEVELOPMENT

DURATION:4 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

DESCRIPTION:

**Project Introduction and Overview**

In today’s fast-paced digital world, tracking how we spend our time online is more important than ever. Many of us spend hours on the internet—sometimes productively, sometimes not. This project is built to solve that problem. The **Productivity Tracker** is a small browser extension popup that gives users a quick glance at how much time they’ve spent online and how much of that time was productive or unproductive.

This HTML page is designed as the main popup interface that appears when a user clicks the browser extension icon. The goal is to provide **a quick, clean, and visually appealing summary** of the user’s web activity for the day. It allows users to easily track their productive habits, see which websites are taking up the most time, and reset their daily stats if needed.

With soft gradients, readable fonts, and interactive buttons, this simple yet elegant interface helps users stay mindful of their time, stay organized, and form better digital habits—all without needing to open a separate website or dashboard.

**Layout and Visual Design**

The design uses a **modern and minimalistic layout** with a beautiful gradient background, making it pleasing to look at during frequent usage. The color palette ranges from violet to deep blue, creating a calming effect that’s both professional and user-friendly. It uses a system-default font stack to maintain compatibility and speed, ensuring it works well across all systems.

The interface is broken down into clear sections:

1. **Header** – Contains the title “📊 Productivity Tracker” in a friendly font with a slight glass blur effect.
2. **Stats Section** – Displays the key statistics:

   * Total time spent online
   * Productive time (with green progress bar)
   * Unproductive time (with orange progress bar)
   * A scrollable list of top websites
3. **Buttons Section** – At the bottom, two large buttons allow the user to:

   * Open the full dashboard
   * Reset the stats for the day

The use of **glassmorphism** (blur + transparency) gives it a high-tech look while still keeping things light and smooth.

**Functionality and Features**

This HTML file serves as the **visual interface**. Its dynamic behavior is powered by a JavaScript file (`popup.js`, which is referenced at the bottom). The main functionality includes:

* **Tracking Time**: Displays total time spent online today, as well as a breakdown of productive vs. unproductive time.
* **Progress Indicators**: Colored progress bars show how much of your day was spent on productive vs. unproductive sites.
* **Top Websites List**: Dynamically displays which websites took up the most time today.
* **Reset Button**: Allows the user to clear the day’s data and start fresh.
* **Dashboard Button**: Likely takes the user to a more detailed view (in the main extension dashboard).

Each stat block is wrapped in a soft, rounded box with light blur effects. These individual cards make the interface modular and easy to expand in future versions.

**CSS Styling Breakdown**

The page uses a **clean and modern CSS design**. Key styles include:

* **Body Styling**:

  * Fixed width of 350px (ideal for browser extensions)
  * Vertical space with `min-height: 400px`
  * Gradient background for aesthetic appeal

* **Stat Blocks**:

  * White semi-transparent backgrounds (`rgba(255,255,255,0.1)`)
  * Rounded corners and padding
  * Blurred background for a glassy feel (`backdrop-filter: blur(10px)`)

* **Typography**:

  * Fonts are system-based (`Segoe UI`, `Roboto`) for speed and compatibility
  * Smaller text for labels and larger, bold text for time values

* **Progress Bars**:

  * Slim (6px) bars with animated colored fills
  * Green for productive time, orange for unproductive
  * Transitions smoothly to represent change visually

* **Buttons**:

  * Rounded, full-width buttons
  * Color-coded (blue for main actions, white for secondary)
  * Hover effects to indicate interactivity

**Usability and Accessibility**

The interface is designed to be simple enough for **daily use without confusion**, even for users who are not tech-savvy. Some of the accessibility and usability highlights include:

* **Readable text sizes**: Enough contrast between text and background for clear readability.
* **Mobile-friendly**: While this is a browser extension popup, the layout adapts to smaller screen areas like sidebars or mobile-like views.
* **Clear visual feedback**: Buttons change appearance when hovered, giving a tactile feel.
* **Auto-scroll list**: If there are many websites visited, the “Top Websites” section can be scrolled, avoiding overflow issues.

This design could easily be scaled or enhanced with accessibility tags (like `aria-*`), voice support, or even dark/light themes.

**Use Case and Future Enhancements**

The Productivity Tracker popup can be used by **students, remote workers, digital freelancers**, and anyone who wants to develop healthy browsing habits. By simply checking this popup a few times a day, users become more aware of how they're spending their time.

Potential future improvements include:

* **Adding analytics charts**: Like pie charts for time breakdowns
* **User account sync**: Letting users save data across devices
* **Category filters**: Letting users set custom tags for different websites
* **Reminders/alerts**: Notify the user when too much time is spent on unproductive sites
* **Voice summaries**: For visually impaired users or multitaskers

Ultimately, this simple interface is a powerful tool when paired with a strong backend. It encourages better habits, promotes mindfulness, and adds a touch of joy to productivity tracking.


<img width="1919" height="1013" alt="Image" src="https://github.com/user-attachments/assets/86bdb75c-6437-4b32-b677-b7247fca6af4" />
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/2f46fe96-2cba-48fa-b2a0-132527b03b08" />
