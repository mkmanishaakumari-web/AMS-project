# AMS-project
Build a web application with user authentication and a PDF report generation system. The  system must generate different types of reports from pre‑existing assessment data without  requiring code modifications for new assessment types
# Assessment Management System

## 🚀 Setup

### Backend
```powershell
cd backend
npm install
npm run dev
cd frontend
npm install
npm run dev

---

## 3. Documentation (Configuration System)
Explain how `config.json` works. Example:

- To **add a new assessment**:
  - Add a new top-level key (e.g., `"as_nutrition_01"`)
  - Define `title`, `sections`, and `fields`

- To **modify field mappings**:
  - Update the `"path"` in the field object (e.g., `"vitalsMap.vitals.heart_rate"`)

- To **update classifications**:
  - Add or edit ranges inside `"classifications"`

---

## 4. Data Setup
- `backend/src/data.ts` already has `session_001` and `session_002` with `assessment_id` values.  
- These match what the PDF requires → so you’re ✅ here.

---



## 5. Testing
- Use **session_001** → generates `as_hr_02` (Health & Fitness Report)  
- Use **session_002** → generates `as_card_01` (Cardiac Assessment Report)  
- Show how config differences reflect in generated PDF  

---

✅ Once I’ve done this, i’ll have everything needed:  
- GitHub repo  
- README with instructions + config documentation  
- Demo video  

---


