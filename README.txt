Zohaib Logistics - 3D logistics website (single file)

HOW TO OPEN
- Double-click index.html. It needs an internet connection the first time
  (it loads Three.js from cdnjs.cloudflare.com).

HOW TO EDIT YOUR DETAILS
- Open index.html in a text editor and search for:  var CFG
- Fill the empty fields (address, hours, ntn, clients, reviews, schedule,
  cases, jobs, brochure). Empty fields stay hidden on the site.
- formUrl / trackUrl / gaId / clarityId are for Google Sheet forms, tracking,
  Google Analytics and Microsoft Clarity. They work after deployment.

HOW TO DEPLOY (Vercel)
1. Create a GitHub repository (for example: zohaib-logistics).
2. Upload index.html to it.
3. On vercel.com choose "Add New Project", import that repository, and press Deploy.
