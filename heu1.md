# Heuristic Evaluation - Verdant Platform

**Kelompok 13 - Kelas LB83**

---

## **1. Visibility of system status**

_The system should always keep users informed about what is going on, through appropriate feedback within reasonable time._

**Is the heuristic violated? How?**
Yes. Ketika AI Health Monitoring Demo loading TensorFlow.js models, tidak ada loading indicator atau progress feedback untuk user. Users tidak tahu apakah system sedang loading atau stuck. Pada form submission (Innovation/Investment forms) juga tidak ada clear feedback saat form sedang di-submit.

**Severity:** Major (3)

---

## **2. Match between system and the real world**

_The system should speak the users' language, with words, phrases and concepts familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order._

**Is the heuristic violated? How?**
Yes. Platform menggunakan technical jargon seperti "TensorFlow.js", "BlazeFace", "SDG 9" yang mungkin tidak familiar untuk semua users. Investment terminology seperti "impact metrics", "due diligence" juga dapat membingungkan novice investors.

**Severity:** Minor (2)

---

## **3. User control and freedom**

_Users often choose system functions by mistake and will need a clearly marked 'emergency exit' to leave the unwanted state without having to go through an extended dialogue. Support undo and redo._

**Is the heuristic violated? How?**
Yes. Long forms (Innovation/Investment) tidak memiliki draft saving capability, sehingga users lose progress jika accidentally navigate away atau browser crashes. AI Demo juga tidak memiliki reset/restart option jika demo not working properly. Tidak ada clear back/previous step options pada multi-step processes.

**Severity:** Major (3)

---

## **4. Consistency and standards**

_Users should not have to wonder whether different words, situations or actions mean the same thing. Follow platform conventions._

**Is the heuristic violated? How?**
Yes. Terdapat inconsistency dalam button styling across pages (colors, sizes, hover states). Form field styles, labels, dan validation patterns juga berbeda-beda antara Contact, Innovation, dan Investment forms. Users perlu relearn interaction patterns di setiap halaman.

**Severity:** Minor (2)

---

## **5. Error prevention**

_Even better than good error messages is a careful design which prevents a problem from occurring in the first place._

**Is the heuristic violated? How?**
Yes. Tidak ada proper handling jika user denies camera permission untuk AI Demo, feature menjadi unusable tanpa clear guidance. Form validation hanya occurs on submit tanpa real-time validation. Not all required fields clearly marked, menyebabkan users submit incomplete forms.

**Severity:** Major (3)

---

## **6. Recognition rather than recall**

_Make objects, actions and options visible. The user should not have to remember information from one part of the dialogue to another. Instructions for use of the system should be visible or easily retrievable whenever appropriate._

**Is the heuristic violated? How?**
Yes. Dalam multi-step forms, users must remember information dari previous steps. Investment criteria juga harus diingat users ketika browsing projects, making it difficult to compare projects against user's criteria. Cognitive load tinggi untuk complex workflows.

**Severity:** Minor (2)

---

## **7. Flexibility and efficiency of use**

_Accelerators – unseen by the novice user – may often speed up the interaction for the expert user, such that the system can cater to both inexperienced and experienced users. Allow users to tailor frequent actions._

**Is the heuristic violated? How?**
Yes. Tidak ada keyboard shortcuts untuk power users. No personalization options untuk different user types. All users see same interface regardless of experience level, tidak ada customization untuk frequent actions atau adaptive interface.

**Severity:** Minor (2)

---

## **8. Aesthetic and minimalist design**

_Dialogues should not contain information which is irrelevant or rarely needed. Every extra unit of information in a dialogue competes with the relevant units of information and diminishes their relative visibility._

**Is the heuristic violated? How?**
Yes. Homepage contains too much information yang competing for attention, users mungkin overwhelmed dan tidak tahu where to start. AI Demo menampilkan too many technical details simultaneously, making interface feel cluttered untuk non-technical users.

**Severity:** Minor (2)

---

## **9. Help users recognise, diagnose and recover from errors**

_Error messages should be expressed in plain language (no codes), precisely indicate the problem and constructively suggest a solution._

**Is the heuristic violated? How?**
Yes. Error messages tidak specific atau actionable. Jika AI demo fails, tidak ada clear error message atau recovery options. Users tidak tahu how to fix problems karena generic error messages tanpa clear steps untuk resolution.

**Severity:** Major (3)

---

## **10. Help and documentation**

_Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on the user's task, list concrete steps to be carried out and not be too large._

**Is the heuristic violated? How?**
Yes. No comprehensive help atau documentation system tersedia. Complex features like AI demo tidak memiliki contextual help. Users cannot get help when stuck dengan complex processes. Tidak ada FAQs, tutorials, atau step-by-step guides.

**Severity:** Minor (2)

---

## **Summary**

- **Major Violations (3):** 4 issues
- **Minor Violations (2):** 6 issues
- **Total Issues:** 10 violations identified
- **Most Critical:** Visibility of system status, User control and freedom, Error prevention, Error recovery
