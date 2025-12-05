CSGO Stats Viewer (2020)

A small standalone Windows application I built around 2020 to view and analyze personal CSGO match statistics by web-scraping the player data from Valve’s official profile pages.

Although CSGO has now been retired and replaced by CS2, this tool was designed specifically for CSGO-era HTML pages and may not work for CS2 data.
Use with caution.

📌 Overview

This tool allows you to load your CSGO match data from a saved HTML file and instantly view useful statistics such as:

Kill/Death ratio (K/D)

Average headshot percentage

Win/Loss percentage

Map-wise performance

Custom map selection filters

The application processes the HTML file offline and displays the computed stats in a clean, simple interface.

🔧 How It Works

Open your CSGO match history on the Valve website.

(Optional but recommended) Install the FloatCS browser extension to display all your match history on the page.

Save the entire match history page as an HTML file.

Open the CSGO Stats Viewer .exe file.

Load your saved HTML file into the application.

Explore your computed stats and map-based insights.

🛠️ Technologies Used

BeautifulSoup – for HTML parsing / web-scraping

Pandas + NumPy – for data cleaning and statistical calculations

Python – backend code

.exe – generated so users can run the program without Python installed

📦 Availability

The core Python source files are private, but the final application is public, standalone, and free to use.

⚠️ Important Note

This tool was built specifically for CSGO match data and the structure of the older Valve profile pages.
Because CS2 uses a different data format, this application may not function properly on CS2 match pages.

Use at your own discretion.
