🎯 AI Resume Analyzer (Frontend UI)

A modern and responsive frontend interface for the AI Resume Analyzer, allowing users to upload resumes, analyze them, and check ATS compatibility with job descriptions.

🚀 Features...........
📁 Upload resume files (PDF, DOC, DOCX)
🔍 Analyze resume with AI-generated insights
⭐ Display resume quality score (1–10)
💡 Show personalized improvement suggestions
🎯 Perform ATS compatibility check
📊 Visualize matched & missing keywords
⚡ Real-time loading and error handling

🛠️ Tech Stack..........
Frontend: HTML, CSS, JavaScript
Styling: Custom CSS (Gradient UI, Cards, Animations)
API Integration: Fetch API
Backend اتصال: Spring Boot REST APIs

📂 Project Structure..........
frontend/
│── index.html
│── styles.css (optional)
│── script.js (optional)
🖥️ UI Screens
📄 Resume Analysis
Upload resume file
View:
Quality Score
Key Skills
Improvement Suggestions
🎯 ATS Checker
Upload resume + enter job description
View:
ATS Score (%)
Matched Keywords ✅
Missing Keywords ❌
Summary
⚙️ How to Run.........
Clone the repository
git clone https://github.com/your-username/ai-resume-analyzer-ui.git
Open project folder
Run index.html in browser

👉 Make sure backend is running at:

http://localhost:8080
🔗 API Integration

The frontend connects to backend APIs:

POST /api/resume/analyze
POST /api/resume/ats-check

Uses FormData + Fetch API for sending files and receiving JSON responses.........

💡 Key Highlights
🎨 Clean and modern UI with gradient design
📊 Interactive score visualization (circular progress UI)
⚡ Responsive and user-friendly experience
🔄 Dynamic content rendering using JavaScript
🚀 Future Improvements
🌐 Deploy UI on Netlify / Vercel
🔐 Add authentication system
📱 Improve mobile responsiveness
📊 Add charts for better visualization
👨‍💻 Author

Abhiraj Kumar

📧 Email: mr10abhiraj@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/abhiraj17
⭐ Support

If you like this project, give it a ⭐ on GitHub!
