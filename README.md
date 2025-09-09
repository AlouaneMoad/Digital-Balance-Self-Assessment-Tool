Digital Balance Self-Assessment Tool
<img width="1920" height="893" alt="image" src="https://github.com/user-attachments/assets/dbe69d8e-8c2d-4e00-b3c5-c5fa71d8512e" />

A bilingual (English/Chinese), single-file web application designed to help users assess their digital wellness through an interactive quiz. This tool translates academic research on the effects of social media and AI into a practical, user-centric experience with personalized feedback.


Key Features
Bilingual Interface: Fully translated into both English and Chinese, with the user's preference saved locally.

Interactive 12-Question Quiz: A step-by-step assessment covering Addiction, Attention Fragmentation, and Anxiety.

Dynamic Results Dashboard: Instantly calculates and displays an overall score and a detailed breakdown with animated progress bars.

Personalized & Dynamic Tips: Provides a rotating pool of actionable advice tailored to the user's specific risk levels.

Visual Progress Tracking: Integrates Chart.js to plot the user's assessment history on a line chart, visualizing their progress over time.

Full History Management: Users can view their past results, delete individual entries, or clear their entire history safely.

Data Export: Allows users to download a summary of their results as a PDF file.

Modern & Accessible UI: Features a fully responsive design with a theme-aware dark/light mode and ARIA labels for accessibility.

Tech Stack
Frontend: Vanilla JavaScript (ES6+), HTML5, CSS3

Styling: Tailwind CSS (via CDN)

Data Visualization: Chart.js (via CDN)

PDF Generation: html2canvas & jsPDF (via CDN)

Privacy First
This application is built with user privacy as a priority. All assessment data, including answers and results history, is stored exclusively in the browser's localStorage. No data is ever transmitted to any server.    
