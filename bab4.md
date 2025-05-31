# BAB 4: EVALUASI USABILITY

## 4.1 Metodologi Evaluasi

### 4.1.1 Paper Prototyping

Paper prototyping menjadi tahap awal dalam proses evaluasi usability platform Verdant, dilakukan untuk memvalidasi konsep desain dan alur interaksi sebelum implementasi digital. Metodologi ini dipilih karena kemampuannya untuk mengidentifikasi masalah usability fundamental dengan biaya yang rendah dan fleksibilitas tinggi dalam melakukan iterasi desain.

Proses paper prototyping dimulai dengan pembuatan sketsa low-fidelity untuk semua halaman utama platform, termasuk Home, Projects, About, AI Demo, Innovate Now, Invest Now, dan Contact. Setiap halaman dirancang dengan fokus pada layout structure, navigation flow, dan key interactive elements tanpa detail visual yang dapat mengalihkan perhatian dari aspek fungsional.

Testing sessions dilakukan dengan 5 partisipan yang mewakili target users platform: 3 inovator dan 2 investor dengan berbagai latar belakang teknis. Setiap session berlangsung 45-60 menit dengan skenario tasks yang mencakup core user journeys seperti project submission untuk inovator dan project discovery untuk investor.

Hasil paper prototyping mengidentifikasi beberapa insight penting: navigation structure yang terlalu complex untuk first-time users, kebutuhan akan clearer call-to-action differentiation antara inovator dan investor paths, dan pentingnya progressive disclosure dalam AI Demo feature untuk mengakomodasi users dengan berbagai tingkat technical expertise.

Iterasi desain berdasarkan feedback paper prototyping menghasilkan simplified navigation structure, enhanced visual hierarchy untuk role-based CTAs, dan restructured information architecture yang lebih intuitive untuk kedua user types.

### 4.1.2 Heuristic Evaluation

Heuristic evaluation dilakukan menggunakan 10 prinsip usability Nielsen sebagai framework untuk systematic assessment terhadap interface design platform Verdant. Evaluasi ini dilakukan oleh 3 expert reviewers dengan background HCI dan web development untuk memastikan objectivity dan comprehensiveness dalam assessment.

Proses evaluasi menggunakan severity rating scale: Cosmetic (1) untuk minor issues yang tidak mempengaruhi usability, Minor (2) untuk issues yang dapat menyebabkan slight delays atau confusion, dan Major (3) untuk issues yang significantly impact user experience atau task completion.

**Hasil Heuristic Evaluation menunjukkan:**

**Heuristics NOT Violated (3 dari 10):**

- **Consistency and Standards**: Platform menerapkan consistent design patterns, color schemes, dan interaction behaviors across all pages
- **Aesthetic and Minimalist Design**: Clean visual design dengan appropriate white space dan focused content presentation
- **Help Users Recognize, Diagnose, and Recover from Errors**: Clear error messages dengan constructive guidance untuk error recovery

**Heuristics PARTIALLY Violated (4 dari 10):**

- **Visibility of System Status** (Minor - 2): Loading indicators tersedia namun bisa lebih informative untuk AI processing
- **User Control and Freedom** (Minor - 2): Back navigation available namun undo functionality terbatas dalam forms
- **Flexibility and Efficiency of Use** (Minor - 2): Interface accessible untuk novices namun lacks advanced shortcuts untuk expert users
- **Help and Documentation** (Minor - 2): Basic help tersedia namun comprehensive documentation bisa ditingkatkan

**Heuristics CLEARLY Violated (3 dari 10):**

- **Match Between System and Real World** (Major - 3): Beberapa technical terms dalam AI Demo kurang familiar untuk general users
- **Recognition Rather than Recall** (Major - 3): Users perlu mengingat navigation paths untuk complex tasks
- **Error Prevention** (Major - 3): Form validation bisa lebih proactive dalam preventing user errors

Total severity score: 17 dari possible maximum 30, menunjukkan overall good usability dengan specific areas untuk improvement.

### 4.1.3 User Testing

User testing dilakukan dengan comprehensive approach untuk memvalidasi real-world usability platform Verdant dengan actual target users. Testing methodology dirancang untuk capturing both quantitative metrics dan qualitative insights tentang user experience.

**Participant Recruitment:** 7 partisipan direkrut untuk representing target demographics platform, terdiri dari 4 inovator (tech startup founders, engineers, researchers) dan 3 investor (venture capitalists, angel investors, impact investors). Semua partisipan adalah laki-laki berusia 21-25 tahun dengan berbagai tingkat technical proficiency.

**Testing Protocol:** Setiap testing session berlangsung 60-90 menit dengan structured approach yang mencakup:

- Pre-test interview untuk understanding background dan expectations
- Task-based testing dengan think-aloud protocol
- Post-test questionnaire (SUS dan UEQ)
- Semi-structured interview untuk gathering qualitative feedback

**Task Scenarios:** Testing scenarios dirancang untuk covering core user journeys:

- **Untuk Inovator:** Platform exploration, project submission process, AI Demo usage, investor connection
- **Untuk Investor:** Project discovery, filtering dan search, project evaluation, contact initiation

**Data Collection:** Multiple data points dikumpulkan including task completion rates, time-on-task, error frequencies, satisfaction ratings, dan detailed qualitative feedback tentang pain points dan positive experiences.

Testing environment diatur untuk simulating realistic usage conditions dengan participants menggunakan their preferred devices dan browsers untuk ensuring ecological validity dari results.

## 4.2 Hasil System Usability Scale (SUS)

### 4.2.1 Profil Responden (7 pengguna)

Evaluasi SUS dilakukan dengan 7 responden yang carefully selected untuk representing target user base platform Verdant. Demographic profile menunjukkan homogeneous group dalam terms of age dan gender, namun diverse dalam technical background dan professional experience.

**Demographic Characteristics:**

- **Gender:** 100% laki-laki (7/7 responden)
- **Age Range:** 21-25 tahun (mean: 23 tahun)
- **Geographic Distribution:** Urban areas dengan akses reliable internet
- **Education Level:** Minimal sarjana dengan majority memiliki technical atau business background

**Professional Background Distribution:**

- **User 1:** Tech Startup Founder - High technical proficiency, familiar dengan innovation platforms
- **User 2:** Mechanical Engineer - Medium technical proficiency, focus pada industrial applications
- **User 3:** Environmental Researcher - Medium technical proficiency, sustainability expertise
- **User 4:** Tech Startup Investor - High technical proficiency, extensive platform usage experience
- **User 5:** Software Engineer - Very high technical proficiency, critical eye untuk technical implementation
- **User 6:** Data Scientist - Very high technical proficiency, AI/ML expertise relevant untuk AI Demo
- **User 7:** Business Analyst - High analytical skills, focus pada user experience dan business processes

Diversity dalam professional backgrounds memastikan comprehensive perspective terhadap platform usability dari berbagai user contexts dan use cases yang relevant dengan platform objectives.

### 4.2.2 Analisis Skor SUS (Rata-rata: 86/100)

Hasil SUS evaluation menunjukkan performance yang excellent dengan overall average score 86/100, menempatkan platform Verdant dalam kategori "Grade B - Excellent" berdasarkan SUS scoring interpretation standards.

**Individual SUS Scores:**

- User 1 (Tech Startup Founder): 82.5/100
- User 2 (Mechanical Engineer): 82.5/100
- User 3 (Environmental Researcher): 85/100
- User 4 (Tech Startup Investor): 95/100
- User 5 (Software Engineer): 80/100
- User 6 (Data Scientist): 90/100
- User 7 (Business Analyst): 85/100

**Statistical Analysis:**

- **Mean Score:** 86.0/100
- **Median Score:** 85.0/100
- **Standard Deviation:** 5.2
- **Range:** 15 points (80-95)
- **Confidence Interval (95%):** 82.1 - 89.9

**Score Distribution Analysis:**

- **Excellent Level (90+):** 2 users (28.6%) - Users 4 dan 6
- **Good Level (80-89):** 5 users (71.4%) - Users 1, 2, 3, 5, dan 7
- **Below Good (<80):** 0 users (0%)

Consistency dalam high scores across different user types menunjukkan bahwa platform successfully meets usability expectations untuk diverse user backgrounds dan technical proficiency levels.

### 4.2.3 Interpretasi Hasil

Interpretasi hasil SUS menggunakan established benchmarks dan industry standards untuk contextualizing platform performance dalam broader usability landscape.

**Grade Classification:** Score 86/100 menempatkan platform dalam "Grade B" category, yang menunjukkan excellent usability performance. Berdasarkan SUS interpretation guidelines, scores above 80 dianggap "Good" dan scores above 85 approaching "Excellent" territory.

**Percentile Ranking:** Score 86 menempatkan platform approximately dalam 85th percentile dari SUS database, meaning platform performs better than 85% dari systems yang telah dievaluasi menggunakan SUS methodology.

**Industry Comparison:** Dalam context web applications dan platforms, score 86 significantly exceeds industry average (sekitar 68) dan menunjukkan competitive advantage dalam user experience quality.

**User Satisfaction Indicators:** High SUS scores correlate dengan strong user satisfaction dan likelihood untuk continued usage. Score consistency across different user types menunjukkan robust design yang accommodates diverse user needs dan preferences.

**Areas of Strength:** Analysis menunjukkan particular strength dalam ease of use, learnability, dan overall user confidence dalam menggunakan platform. Users consistently reported feeling comfortable dan efficient dalam completing tasks.

**Implications untuk Platform Development:** Excellent SUS results validate design decisions dan implementation quality, sambil providing confidence untuk scaling platform dan adding advanced features tanpa compromising core usability.

## 4.3 Hasil User Experience Questionnaire (UEQ)

### 4.3.1 Analisis 6 Dimensi UX

User Experience Questionnaire (UEQ) evaluation memberikan comprehensive assessment terhadap multiple dimensions dari user experience platform Verdant. UEQ methodology mengukur 6 distinct dimensions yang collectively provide holistic view terhadap overall user experience quality.

**Attractiveness (Mean: +1.32)**
Dimensi Attractiveness mengukur overall impression dan appeal dari platform. Score +1.32 menunjukkan bahwa users find platform visually appealing dan engaging. Feedback qualitative menunjukkan appreciation terhadap clean design, consistent color scheme, dan professional appearance yang builds trust untuk investment platform context.

**Perspicuity (Mean: +1.07)**  
Perspicuity mengukur ease of getting familiar dengan platform dan clarity dalam understanding how to use it. Score +1.07 menunjukkan good performance dalam making platform intuitive dan easy to learn. Users reported clear navigation structure dan logical information architecture yang memudahkan first-time usage.

**Efficiency (Mean: +1.25)**
Efficiency dimension mengukur whether users dapat complete tasks quickly dan efficiently tanpa unnecessary effort. Score +1.25 menunjukkan strong performance dalam task completion efficiency. Users appreciated streamlined workflows dan minimal steps required untuk core tasks seperti project browsing dan information access.

**Dependability (Mean: +0.93)**
Dependability mengukur user confidence dalam platform reliability dan predictability. Score +0.93 menunjukkan good performance namun dengan room untuk improvement. Users expressed confidence dalam platform stability namun noted occasional concerns tentang data persistence dan system reliability untuk critical tasks.

**Stimulation (Mean: +1.54)**
Stimulation dimension mengukur excitement dan motivation yang dirasakan users saat menggunakan platform. Score +1.54 merupakan highest score among all dimensions, menunjukkan bahwa platform successfully creates engaging dan motivating experience. AI Demo feature particularly contributed untuk high stimulation scores.

**Novelty (Mean: +1.25)**
Novelty mengukur innovation dan creativity dalam design approach. Score +1.25 menunjukkan good performance dalam providing fresh dan innovative user experience. Integration dari AI technology dan focus pada sustainability themes contributed untuk positive novelty perception.

### 4.3.2 Benchmarking dengan Standar UEQ

Benchmarking analysis menggunakan UEQ benchmark dataset yang terdiri dari 1,455 studies untuk contextualizing platform performance dalam broader UX landscape.

**Benchmark Comparison Results:**

**Above Average Performance (4 dimensions):**

- **Stimulation (+1.54):** Significantly above benchmark mean, indicating exceptional engagement
- **Attractiveness (+1.32):** Above average, showing strong visual appeal dan overall impression
- **Novelty (+1.25):** Above average, demonstrating successful innovation dalam design approach
- **Efficiency (+1.25):** Above average, indicating good task completion performance

**Average Performance (2 dimensions):**

- **Perspicuity (+1.07):** Within average range, showing acceptable clarity dan ease of learning
- **Dependability (+0.93):** Lower end of average range, indicating area untuk focused improvement

**Overall UEQ Performance:** Platform Verdant demonstrates strong UX performance across all measured dimensions, dengan particular strengths dalam engagement (Stimulation) dan visual design (Attractiveness). No dimensions fall below average, indicating consistent quality across different aspects dari user experience.

**Industry Context:** Performance levels place platform dalam competitive position within web application landscape, dengan scores comparable atau superior to established platforms dalam similar domains.

### 4.3.3 Perbandingan dengan SUS

Cross-validation analysis antara SUS dan UEQ results menunjukkan consistent findings dan mutual reinforcement dari usability dan user experience assessments.

**Correlation Analysis:**

- SUS score 86/100 correlates well dengan UEQ overall positive scores
- Both methodologies indicate above-average performance dengan room untuk specific improvements
- Consistency dalam results increases confidence dalam evaluation validity

**Complementary Insights:**

- **SUS Focus:** Task-oriented usability dan efficiency - confirmed by UEQ Efficiency scores
- **UEQ Breadth:** Emotional dan experiential aspects - adds depth dengan Stimulation dan Attractiveness insights
- **Combined Perspective:** Comprehensive view covering both functional usability dan experiential quality

**Validation of Design Decisions:**

- High scores dalam both evaluations validate user-centered design approach
- Consistency across different user types confirms robust design yang accommodates diverse needs
- Strong performance metrics support platform readiness untuk broader deployment

**Areas untuk Improvement Alignment:**

- Both methodologies suggest focus pada system reliability (UEQ Dependability, SUS consistency items)
- Learning curve optimization opportunities identified dalam both assessments
- Error prevention dan recovery mechanisms highlighted dalam both evaluations

## 4.4 Temuan dan Rekomendasi Perbaikan

### 4.4.1 Critical Success Factors

Evaluasi comprehensive mengidentifikasi several critical success factors yang contribute terhadap excellent usability performance platform Verdant.

**Design Consistency:** Consistent application dari design system across all pages dan components creates predictable user experience yang reduces cognitive load dan increases user confidence. Color scheme, typography, dan interaction patterns yang coherent membantu users develop mental model yang accurate tentang platform functionality.

**Clear Information Architecture:** Logical organization dari content dan features memungkinkan users untuk easily find information dan complete tasks. Navigation structure yang intuitive dengan appropriate categorization supports both browsing dan goal-directed usage patterns.

**Responsive Design Implementation:** Mobile-first approach dengan careful attention terhadap touch interactions dan screen size adaptations ensures optimal experience across devices. Testing menunjukkan consistent usability performance dari desktop hingga mobile devices.

**AI Integration Approach:** Progressive disclosure dalam AI Demo feature successfully accommodates users dengan varying technical expertise levels. Complex AI functionality presented dalam accessible manner tanpa overwhelming non-technical users.

### 4.4.2 Areas untuk Improvement

Meskipun overall performance excellent, evaluasi mengidentifikasi specific areas yang dapat ditingkatkan untuk further enhancing user experience.

**System Feedback Enhancement:** Users expressed desire untuk more detailed feedback during AI processing dan form submissions. Implementation dari progress indicators dengan estimated completion times dan clearer status messages dapat improve user confidence dan reduce uncertainty.

**Error Prevention Mechanisms:** Proactive validation dan input guidance dapat reduce user errors dan frustration. Implementation dari real-time validation dengan helpful suggestions dan format examples dapat significantly improve form completion success rates.

**Advanced User Features:** Power users expressed interest dalam shortcuts dan advanced features untuk increased efficiency. Implementation dari keyboard shortcuts, bulk operations, dan customizable interfaces dapat accommodate expert user needs tanpa compromising simplicity untuk novice users.

**Documentation dan Help System:** While basic help tersedia, comprehensive documentation dan contextual help dapat reduce learning curve dan support independent problem-solving. Interactive tutorials dan guided tours dapat particularly benefit first-time users.

### 4.4.3 Prioritized Recommendations

Berdasarkan impact assessment dan implementation feasibility, recommendations diprioritaskan untuk maximum improvement dengan available resources.

**High Priority (Immediate Implementation):**

1. **Enhanced Loading Indicators:** Implement detailed progress feedback untuk AI processing dan data loading
2. **Improved Error Messages:** Develop constructive error messages dengan specific guidance untuk resolution
3. **Form Validation Enhancement:** Add real-time validation dengan helpful formatting examples

**Medium Priority (Next Development Cycle):**

1. **Contextual Help System:** Implement tooltips dan contextual guidance untuk complex features
2. **Keyboard Navigation:** Add comprehensive keyboard shortcuts untuk improved accessibility
3. **Advanced Search Features:** Enhance filtering dan search capabilities untuk power users

**Low Priority (Future Enhancements):**

1. **Personalization Features:** Implement user preferences dan customizable interfaces
2. **Advanced Analytics:** Add detailed usage analytics dan performance metrics
3. **Offline Capabilities:** Explore progressive web app features untuk offline functionality

Implementation dari these recommendations akan further strengthen platform usability dan user satisfaction, building upon already excellent foundation established through current design dan development efforts.
