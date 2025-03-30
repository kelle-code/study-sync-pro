# 📚 StudySync Pro – AI-Powered Daily Test Scheduler

This project is a no-code, generative AI app that builds personalized study schedules for any exam using [AWS PartyRock](https://partyrock.aws). Users input the exam subject, number of days to prepare, and daily study hours, and the app returns a custom daily study plan — plus a motivational message.

🔗 [Try the live app here](https://partyrock.aws/u/MoHines/a3v33aetb/Daily-Test-Scheduler)

---

## 🧠 BUILD Summary

### 🔹 B – Background
As someone who recently passed the AWS Cloud Practitioner exam, I wanted to create something helpful for other test-takers. *StudySync Pro* helps students manage their time and energy by building a realistic study schedule with AI.

---

### 🔹 U – Understanding
The app accepts 3 inputs:
- Exam Subject
- Study Duration (in days)
- Daily Study Hours

With this info, the AI generates:
- A detailed day-by-day study schedule
- A motivational message for encouragement

---

### 🔹 I – Implementation
- **Platform:** [AWS PartyRock](https://partyrock.aws)
- **Model:** Amazon Bedrock (text generation)
- **Tools Used:** No-code widgets
- **Widgets:**
  - Text Input x3
  - Text Generator x2 (schedule + motivation)

Prompt example:
You are a study coach. Create a study schedule for the {Exam Subject} exam over {Study Duration} days with {Daily Hours} hours per day. Include a mix of study sessions, review time, practice tests, and rest days.

---

### 🔹 L – Lessons Learned
- Prompt engineering is powerful — small tweaks made the AI output much more useful.
- PartyRock makes it easy to build with generative AI even without code.
- Designing an interface with user clarity in mind is just as important as logic.

---

### 🔹 D – Deliverables
- ✅ Live App: [https://partyrock.aws/u/MoHines/a3v33aetb/Daily-Test-Scheduler](https://partyrock.aws/u/MoHines/a3v33aetb/Daily-Test-Scheduler)
- 🕒 Time to build: ~4 hours
- 💡 Future ideas:
  - Add user login and saved schedules
  - Track study progress with DynamoDB + Amplify
  - Add downloadable PDF schedules

---

## 📸 Screenshots

*(Add screenshots of your app interface here — you can upload PNGs or JPGs and drag them into the repo or use Markdown image links)*

---

## 📬 Contact

Created by [@MoHines](https://www.linkedin.com/in/your-link-here/)  
Let’s connect and build something great!

