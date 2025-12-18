# placement-governance-automation
End-to-end automation that manages student re-entry into a placement program by  coordinating mentor grading, feedback loops, and interview eligibility.

# Placement Re-entry & Mentor Grading Automation (ARF–RPG)

> A production-grade workflow that governs student re-entry into a placement program
> by automating mentor grading, feedback loops, and interview eligibility.

---

## 🔍 Problem This Solves

Placement teams struggle with:
- Manual re-entry requests
- Chasing mentors for grading
- Tracking feedback iterations
- Ensuring only eligible students move to interviews

This results in:
- Delays
- Missed follow-ups
- Inconsistent grading standards
- High ops overhead

This system replaces all of that with **clear gates, ownership, and automation**.

---

## 🧠 What This Workflow Does

### 1️⃣ Student Re-entry Request
- Student fills out an **ARF (Application for Re-entry Form)**
- Submits required **RPG (Real Project GitHub) links**

---

### 2️⃣ Automated Mentor Assignment
- RPG links are routed to **assigned mentors**
- Mentors receive grading tasks via **Slack**
- Clear instructions and grading criteria included

---

### 3️⃣ Mentor Grading Loop (Slack-driven)
- Mentors submit structured feedback
- System tracks grading status automatically
- Partial / failed submissions trigger follow-ups

---

### 4️⃣ Student Feedback Automation
- Students receive **email feedback** after each review cycle
- Feedback is versioned and logged
- Students can resubmit improvements if required

---

### 5️⃣ Placement Eligibility Gate
- Once grading is cleared:
  - Student status is updated
  - Re-entry is logged
  - Student is **automatically moved to the Interview stage**

No manual checks. No spreadsheet chasing.

---

## 🏗️ System Architecture

**Inputs**
- ARF submission form
- RPG GitHub links

**Processing**
- n8n workflow orchestration
- Mentor assignment logic
- Slack-based grading workflows
- Feedback version control
- Status-based gating rules

**Outputs**
- Email feedback to students
- Slack notifications to mentors & ops
- Placement pipeline status update

---

## 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Forms-673AB7?style=for-the-badge&logo=google-forms&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white"/>
</p>

---

## 📊 Key Outcomes

- Eliminated manual mentor follow-ups
- Reduced re-entry processing time from days to hours
- Clear audit trail for every student decision
- Scaled re-entry without increasing ops headcount

---

## 🎯 Why This Matters

This is not a demo workflow.

It’s a **governance system**:
- Clear ownership
- Defined gates
- Automated escalation
- Zero ambiguity in placement eligibility

Exactly how high-scale programs should run.

---

## 🔒 Notes

- Sensitive identifiers removed
- Workflow JSON included for reference
- Built and used in a real production environment

---

## 👤 Built By

**Jatin Saini**  
Operations · Automation · Program Systems  
🔗 [LinkedIn](https://www.linkedin.com/in/jatinsaini09/)
