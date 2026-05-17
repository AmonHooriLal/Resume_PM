Amon H Lal - Interactive Web Resume

Welcome to the repository for my interactive web resume. I am a Fintech Product Manager specializing in Payments, AI Automation, and B2B SaaS.

This project is a fully responsive, single-page web portfolio built with HTML and Tailwind CSS. It features a modern, professional SaaS-inspired aesthetic, tailored specifically for product management roles.

🚀 Features

Modern UI: Clean, responsive design with dynamic hover states and stylized gradients.

Print-Optimized (Save Web PDF): Native CSS print styling allows users to save the webpage as a clean, properly formatted PDF without UI clutter (buttons, shadows, etc.).

Classic Resume Download: Direct link to download an ATS-friendly, classic LaTeX-generated PDF resume.

Integrated Case Studies: Direct links to detailed Notion product case studies.

📁 Repository Structure

To ensure all images and downloads work perfectly on GitHub Pages, the repository must maintain this exact file structure:

/
├── index.html                           # Main web resume code
├── profile_pic/
│   └── Amon_Profile_Pic.png             # Your profile picture
└── classicResume/
    └── Amon_Classic_Resume.pdf          # Your ATS-friendly PDF resume


Note: GitHub Pages is strictly case-sensitive. Ensure folder names and file names match the exact casing shown above.

🌐 How to Host on GitHub Pages

Upload the files maintaining the structure above to the main branch of this repository.

Go to your repository's Settings.

In the left sidebar, click on Pages.

Under "Build and deployment", set the Source to Deploy from a branch.

Select the main branch and / (root) folder, then click Save.

GitHub will take a minute or two to build the site. Your live URL will appear at the top of the Pages settings!

🤖 How to Update this Code using Google Gemini

If you need to add a new job, change a metric, or alter the theme in the future, you don't need to write the code manually. You can use the original Gemini AI chat to do it for you:

Access the Original Chat: Click this link to open the resume builder conversation: Amon's Gemini Resume Chat.
(Alternatively, you can open a new chat with Gemini at any time).

Upload the Latest Code: To ensure Gemini has the most up-to-date version of your site, copy the code from index.html and paste it into the chat prompt.

Give Clear Instructions: Tell Gemini exactly what you want to change. Examples:

"Add a new job under Work Experience: 

$$Company Name$$

, 

$$Role$$

, 

$$Dates$$

. Here are my 3 bullet points:..."

"Change the primary theme color from Indigo to a deep Forest Green."

"Update the metric under my JustDial experience from 25% to 40%."

Copy the Output: Gemini will generate the newly updated index.html file. Simply copy that code, replace the code in your GitHub repository, and commit the changes! Your live website will update automatically.
