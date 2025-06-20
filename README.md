# Peapodcalculator
A calculator
A professional business lender matching calculator for Peapod Finance, partnered with Flexibility Capital.
🌐 Live Site
URL: https://peapodfinance.github.io/Peapodcalculator/
Access Code: peapod2025
📋 What It Does
The Peapod Calculator helps businesses find suitable lenders based on their financial profile. Users input their business information and receive:

✅ Qualified lenders they can apply to immediately
❌ Non-qualified lenders with specific improvement guidance
💡 Actionable recommendations to qualify for more lenders
📊 Detailed explanations of requirements and gaps

🏗️ Features
🔐 Secure Access

Password-protected login system
Professional Peapod branding with company mascot
Clean, modern interface

🧮 Smart Matching

23+ lenders in database
6 key criteria evaluation (credit score, revenue, deposits, NSFs, balance, business age)
Industry restrictions checking
Real-time qualification assessment

📈 Business Intelligence

Improvement suggestions with specific targets
Gap analysis showing exactly what's needed
Priority recommendations (high/medium/low impact)
Match rate statistics

🎯 Built For

Internal team use (25+ users)
Client consultations and assessments
Business development activities
Lender relationship management

🛠️ Technical Details

Frontend: HTML5, CSS3, JavaScript (Vanilla)
Styling: Modern glassmorphism design, responsive layout
Hosting: GitHub Pages
No backend required - runs entirely in browser
Mobile-friendly responsive design

📁 File Structure
├── index.html          # Login page
├── calculator.html     # Main calculator tool
├── mascot.png         # Company mascot image
└── README.md          # This file
🔄 How to Update
Weekly Lender Updates

Edit calculator.html
Update the lenders array with new criteria or lenders
Commit changes to GitHub
Changes deploy automatically (1-2 minutes)

Adding New Lenders
javascript{
  name: "New Lender Name",
  criteria: {
    personalCredit: 600,
    monthlyRevenue: 10000,
    deposits: 3,
    nsfs: 3,
    avgBalance: 1000,
    monthsBusiness: 12
  },
  restrictedIndustries: ["Industry1", "Industry2"]
}
Updating Access Password
Change the CORRECT_PASSWORD variable in index.html:
javascriptconst CORRECT_PASSWORD = "your-new-password";
👥 User Guide
For Users

Visit the site URL
Enter access code: peapod2025
Fill in business information form
Review qualified and non-qualified lenders
Follow improvement recommendations

For Administrators

Update lenders: Edit calculator.html
Change password: Edit index.html
Monitor usage: Check GitHub Pages analytics
Backup data: Download/export lender configurations

🎨 Customization
Branding

Logo: Replace mascot.png with new image
Colors: Update CSS variables in the <style> sections
Company name: Update text throughout HTML files

Content

Lender criteria: Modify the lenders array
Industry list: Auto-generated from lender restrictions
Improvement tips: Customizable in the JavaScript functions

📊 Analytics
The tool provides insights on:

Match rates for user inputs
Most/least accessible lenders
Common improvement areas
Industry restriction patterns

🔒 Security Notes

Password protection on frontend (not encryption)
No sensitive data stored or transmitted
No user tracking or data collection
GitHub Pages HTTPS encryption in transit

🚀 Future Enhancements
Potential additions for future versions:

Admin panel for easier lender management
Contact information storage for lenders
Export functionality for results
User accounts and saved searches
API integration with lender systems

📞 Support
For technical issues or feature requests:

Primary Contact: Peapod Finance Team
Platform: GitHub Issues (for development)
Updates: Deployed automatically via GitHub Pages

📄 License
Internal business tool for Peapod Finance use.

Built with ❤️ for the Peapod Finance team
