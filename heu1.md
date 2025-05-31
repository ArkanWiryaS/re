# Heuristic Evaluation - Verdant Platform

**Kelompok 13 - Kelas LB83**
**Evaluators:** Arkan Wirya Sentika, Muhammad Jundi Arfa Satriatama, Adhe Naufal Putra Purnomo

---

## **1. Visibility of system status**

_The system should always keep users informed about what is going on, through appropriate feedback within reasonable time._

**Is the heuristic violated? How?**
**Partially violated.** Platform menampilkan navigation state dengan baik melalui active menu highlighting dan page titles yang jelas. Namun, pada AI Health Monitoring Demo, tidak ada loading indicator saat TensorFlow.js models sedang loading, menyebabkan user tidak tahu status system. Form submissions juga memerlukan better feedback during processing.

**Severity:** Minor (2)

---

## **2. Match between system and the real world**

_The system should speak the users' language, with words, phrases and concepts familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order._

**Is the heuristic violated? How?**
**Not significantly violated.** Platform menggunakan bahasa yang appropriate untuk target audience (innovators dan investors). Terminology seperti "Innovation Project", "Investment Opportunity", "Health Monitoring" sudah familiar. Beberapa technical terms seperti "TensorFlow.js" dan "BlazeFace" muncul di AI demo, namun ini acceptable karena menunjukkan credibility teknologi yang digunakan.

**Severity:** Cosmetic (1)

---

## **3. User control and freedom**

_Users often choose system functions by mistake and will need a clearly marked 'emergency exit' to leave the unwanted state without having to go through an extended dialogue. Support undo and redo._

**Is the heuristic violated? How?**
**Yes, violated.** Forms yang panjang (Innovation submission, Investment forms) tidak memiliki draft saving atau progress preservation. Users bisa kehilangan data jika accidentally navigate away. AI Demo tidak memiliki clear reset/restart button jika detection not working properly. Navigation memerlukan browser back button untuk return to previous steps.

**Severity:** Major (3)

---

## **4. Consistency and standards**

_Users should not have to wonder whether different words, situations or actions mean the same thing. Follow platform conventions._

**Is the heuristic violated? How?**
**Not violated.** Platform menunjukkan good consistency dalam navigation layout, color scheme (green theme yang konsisten), typography, dan button styling across all pages. Form layouts mengikuti standard conventions dengan clear labels dan logical field ordering. Design language coherent dan professional.

**Severity:** Not applicable

---

## **5. Error prevention**

_Even better than good error messages is a careful design which prevents a problem from occurring in the first place._

**Is the heuristic violated? How?**
**Partially violated.** Platform menerapkan basic form validation dan required field indicators dengan baik. Namun, AI Demo tidak memiliki proper camera permission handling atau fallback options. Real-time validation bisa ditingkatkan untuk prevent submission errors. Overall, basic error prevention sudah implemented.

**Severity:** Minor (2)

---

## **6. Recognition rather than recall**

_Make objects, actions and options visible. The user should not have to remember information from one part of the dialogue to another. Instructions for use of the system should be visible or easily retrievable whenever appropriate._

**Is the heuristic violated? How?**
**Not violated.** Platform design mendukung recognition dengan clear navigation menu yang always visible, descriptive page headings, dan logical information architecture. Project information dan investment details ditampilkan dengan clear structure. Users tidak perlu mengingat information dari page lain karena context sudah cukup clear di setiap halaman.

**Severity:** Not applicable

---

## **7. Flexibility and efficiency of use**

_Accelerators – unseen by the novice user – may often speed up the interaction for the expert user, such that the system can cater to both inexperienced and experienced users. Allow users to tailor frequent actions._

**Is the heuristic violated? How?**
**Partially violated.** Platform sudah menyediakan multiple pathways untuk different user types (innovator vs investor), dengan dedicated sections dan forms. Namun, tidak ada personalization features atau shortcuts untuk experienced users. Interface sama untuk semua experience levels, tidak ada customization options.

**Severity:** Minor (2)

---

## **8. Aesthetic and minimalist design**

_Dialogues should not contain information which is irrelevant or rarely needed. Every extra unit of information in a dialogue competes with the relevant units of information and diminishes their relative visibility._

**Is the heuristic violated? How?**
**Not violated.** Platform menerapkan clean, minimalist design dengan good use of white space dan visual hierarchy. Information presented secara logical dan focused pada essential elements. Green color scheme professional dan tidak overwhelming. Layout tidak cluttered dan mendukung easy scanning of content.

**Severity:** Not applicable

---

## **9. Help users recognise, diagnose and recover from errors**

_Error messages should be expressed in plain language (no codes), precisely indicate the problem and constructively suggest a solution._

**Is the heuristic violated? How?**
**Yes, violated.** Ketika AI demo mengalami issues (camera access denied, model loading failed), error messages tidak specific atau actionable. Form validation errors basic tapi bisa lebih descriptive. Users perlu better guidance untuk troubleshooting dan recovery dari error states, especially untuk technical features seperti AI demo.

**Severity:** Major (3)

---

## **10. Help and documentation**

_Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on the user's task, list concrete steps to be carried out and not be too large._

**Is the heuristic violated? How?**
**Partially violated.** Platform sudah cukup intuitive untuk basic navigation dan form completion tanpa extensive documentation. Clear page descriptions dan contextual information adequate untuk most users. Namun, complex features seperti AI Health Demo bisa benefit dari contextual help atau quick tutorials untuk first-time users.

**Severity:** Minor (2)

---

## **Summary & Assessment**

### **Overall Usability Score:**

- **Not Violated:** 3 heuristics (Good design fundamentals)
- **Partially Violated:** 4 heuristics (Minor improvements needed)
- **Clearly Violated:** 3 heuristics (Requires attention)

### **Severity Breakdown:**

- **Major Issues (3):** 2 problems - Need immediate attention
- **Minor Issues (2):** 4 problems - Plan for next iteration
- **Cosmetic Issues (1):** 1 problem - Low priority

### **Platform Strengths:**

✅ **Consistent visual design** dan professional appearance  
✅ **Clear information architecture** dan logical navigation  
✅ **Appropriate language** untuk target audience  
✅ **Good recognition support** dengan descriptive elements  
✅ **Clean aesthetic** yang tidak overwhelming

### **Priority Improvements:**

🔴 **High Priority:**

- Implement form draft saving/progress preservation
- Enhance AI demo error handling dan recovery options

🟡 **Medium Priority:**

- Add loading indicators untuk AI model initialization
- Improve real-time form validation
- Add contextual help untuk complex features
- Consider personalization untuk different user experience levels

### **Overall Assessment:**

Platform Verdant menunjukkan **solid foundation** dalam usability design dengan strong visual consistency dan clear information structure. Core usability principles sudah well-implemented. Areas untuk improvement primarily focused pada **advanced interactions** dan **error handling** rather than fundamental design flaws. Platform ready untuk user testing dengan minor refinements.
