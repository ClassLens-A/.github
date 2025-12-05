# 🔥 Turning a real classroom challenge into an AI-powered solution.

# 📸 ClassLens

ClassLens is a multi-platform attendance automation system built to replace manual roll calls with an AI-powered mechanism using just one group photograph.  
By combining Computer Vision, Face Recognition, Vector Similarity Search, and a seamless UI across mobile and web, ClassLens enables faster, error-free, and more transparent attendance workflows.
```
![ClassLens](docs/classlens.jpeg)
```
---

## 🧠 Problem We Address  
Traditional attendance marking is:

❌ Time-consuming  
❌ Error-prone  
❌ Inefficient for large classrooms  

ClassLens eliminates this friction by automatically detecting student faces from a classroom image, matching them with stored embeddings, and producing verified attendance in seconds.

---

## 📂 Project Modules & Repositories

### 📱 Mobile App – Teachers & Students  
🧩 Flutter application for photo capture, attendance insights, profile, PRN-based login, OTP onboarding.

👉 [ClassLens_App](https://github.com/ClassLens-A/ClassLens_App)

---

### 🧠 Backend – AI Pipeline & Core Logic  
⚙ Django backend powering the pipeline from:

- Face detection  
- Embedding extraction  
- Similarity evaluation  
- Attendance marking  
- Verification image generation  
- Background processing (Celery)

👉 [ClassLens(Backend)](https://github.com/ClassLens-A/ClassLens)

---

### 🖥 Admin Dashboard – Academic Management  
🛠 Next.js dashboard enabling admins to:

- Upload bulk data via Excel/CSV  
- Manage teachers, students, subjects, batches  
- Monitor attendance records  
- View AI-generated reports  

👉 [ClassLens-Frontend](https://github.com/ClassLens-A/ClassLens-Frontend)

---

## 🎯 User Roles (What Each User Can Do)

### 👨‍🎓 Student
- Registers once using PRN & Face ID  
- Views personalised attendance  
- Maintains transparency in daily records  

### 👩‍🏫 Teacher
- Captures one classroom image  
- Receives attendance automatically  
- Reviews/checks mismatches  
- Submits final attendance instantly  

### 🏫 Admin
- Manages academic entities  
- Verifies registrations  
- Controls entire attendance database  

---

## 📰 Featured in Newspaper  
Our work was published in the **30th November edition** recognizing ClassLens as an innovative solution for educational institutions.

> “Bringing automation into everyday student management through AI.”

```
![Newspaper Feature](docs/newspaper.png)
```

---

## 📸 UI Preview (Placeholders)

```
![Teacher App – Main Screen](docs/teacher-app.png)
![Student App – Dashboard](docs/student-dashboard.png)
![Admin Dashboard – Bulk Upload View](docs/admin-dashboard.png)
```

You can upload screenshots later.

---

## 🧭 Current Status  

✔ Successfully tested deployment on intra-institutional network  
✔ End-to-end pipeline functioning  
✔ Teacher verification screens active  
✔ User onboarding with OTP implemented  
✔ Mobile and Web modules integrated  

🔄 Further improving face recognition confidence & matching quality  
🔄 Optimizing image processing speed across varied conditions  

🚀 Planned next steps:  
✨ Deploying on secured external cloud environment  
✨ Public demonstration release with real-user testing  
✨ Enhanced reporting, analytics and data insights

---

## 🧑‍💻 Team

| Team Member |
|-------------|
| Member 1 |
| Member 2 |
| Member 3 |

---

## 🤝 Contact & Collaboration  
For project queries, collaboration, academic showcase, or research expansion—  
👉 Feel free to reach out or open an issue in any repo.
