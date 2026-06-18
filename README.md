# Final Exam Practical - ITDI204 Cloud Computing

## Student information

**Student name:** *Tim Roger*

**GitHub repository URL:** * https://github.com/SN-ICE-002/Final_exam_Tim.git *

**Render application URL:** * https://final-exam-tim.onrender.com *

---

## Application information

**Application name:** *Final Exam - TIM ROGER*

**Render project name:** *Final Exam - TIM ROGER*

**Branch used for production deployment:** **main**

**Staging branch name:** **staging**

---

## Deployment configuration

**Build command:** **npm install**

**Start command:** **npm start**

**Environment variable MSG:** **Final Exam**

**Environment variable ENV:** **Production**

---

## API endpoints to test

### Presentation endpoint

**URL:** * https://final-exam-tim.onrender.com/presentation *

**Expected result:** *Final Exam - Production*

### Correction endpoint

**URL:** * https://final-exam-tim.onrender.com/correction *

**Error after first call:** *Correction endpoint is working*

**Expected result after correction:** *Correction endpoint is working*

---

## Error detection

Briefly explain what you corrected and how you moved the correction from staging to production.

**Explanation:**  
*I have corrected the error in the correction endpoint by changing the res.sen to res.send.*
*I have moved the correction from staging to production by pushing the changes to the main branch and merge the staging to the main branch.*
*I have also updated the README.md file to include the correct URLs and expected results.*
