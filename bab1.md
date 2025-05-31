# BAB I: PENDAHULUAN

## 1.1 Latar Belakang

Dalam era Industri 4.0 yang berkembang pesat, dunia menghadapi tantangan besar dalam mencapai pembangunan berkelanjutan. Sustainable Development Goals (SDGs) yang ditetapkan oleh Perserikatan Bangsa-Bangsa menekankan pentingnya inovasi dan pembangunan infrastruktur yang berkelanjutan, khususnya dalam SDG 9: Industry, Innovation, and Infrastructure. Target utama SDG 9 mencakup pembangunan infrastruktur yang tangguh, promosi industrialisasi inklusif dan berkelanjutan, serta mendorong inovasi teknologi yang dapat memberikan dampak positif bagi masyarakat.

Namun, terdapat kesenjangan signifikan antara kebutuhan inovasi berkelanjutan dengan platform yang memfasilitasi kolaborasi antara innovators dan investors dalam ekosistem yang terintegrasi. Banyak inovator, terutama startup teknologi, peneliti kesehatan, dan mahasiswa, memiliki ide-ide revolusioner untuk mengatasi masalah industrial dan kesehatan, namun kesulitan mengakses jaringan investor yang tepat dan platform yang dapat mendemonstrasikan potensi teknologi mereka secara efektif.

Di sisi lain, investor yang fokus pada impact investing dan teknologi berkelanjutan seringkali menghadapi kendala dalam menemukan proyek-proyek inovasi yang sesuai dengan kriteria investasi mereka. Proses due diligence dan evaluasi proyek menjadi kompleks karena minimnya platform yang dapat menyajikan informasi komprehensif tentang inovasi, termasuk demonstrasi teknologi secara real-time yang dapat memberikan gambaran jelas tentang potensi implementasi.

Artificial Intelligence (AI) dan machine learning telah menunjukkan potensi besar dalam berbagai sektor, terutama dalam health monitoring dan predictive analytics. Implementasi AI dalam platform digital dapat memberikan nilai tambah yang signifikan, tidak hanya sebagai alat demonstrasi teknologi, tetapi juga sebagai proof of concept untuk aplikasi AI dalam konteks industrial dan kesehatan. Hal ini menjadi semakin penting mengingat kebutuhan akan workplace safety yang meningkat di era pasca-pandemi.

Berdasarkan analisis terhadap platform-platform existing seperti AngelList, Kickstarter, dan berbagai corporate innovation platforms, ditemukan bahwa masih terdapat gap dalam hal integrasi teknologi AI yang dapat didemonstrasikan secara interaktif, focus khusus pada sustainable development dan green technology, serta user experience yang optimal untuk kedua user groups dengan technical proficiency yang berbeda.

Mengingat kompleksitas interaksi antara innovators dan investors, serta kebutuhan untuk mendemonstrasikan teknologi AI secara efektif, diperlukan pendekatan Human-Computer Interaction (HCI) yang komprehensif dalam pengembangan platform. Prinsip-prinsip user-centered design, usability engineering, dan interaction design menjadi krusial untuk memastikan platform dapat memfasilitasi kedua user groups dengan efektif sambil mempertahankan accessibility untuk berbagai tingkat technical proficiency.

Platform Verdant dikembangkan sebagai respons terhadap kebutuhan tersebut, menggabungkan konsep sustainable industrial development dengan AI-powered health monitoring demonstration dalam satu ekosistem digital yang terintegrasi. Platform ini dirancang untuk menjembatani gap antara inovasi teknologi dan investasi berkelanjutan, sambil memberikan pengalaman pengguna yang optimal melalui penerapan prinsip-prinsip HCI modern.

## 1.2 Rumusan Masalah

Bagaimana merancang dan mengembangkan platform digital yang dapat memfasilitasi kolaborasi efektif antara innovators dan investors dalam ekosistem sustainable development, sambil mengintegrasikan AI-powered health monitoring demonstration yang dapat memberikan user experience yang optimal untuk kedua user groups?

Masalah utama yang ingin diselesaikan dari perspektif innovators mencakup keterbatasan akses terhadap investor yang fokus pada sustainable technology, kesulitan dalam mendemonstrasikan potensi teknologi AI kepada non-technical investors, serta minimnya platform untuk comprehensive project documentation yang dapat membangun kredibilitas dan trust dengan investors.

Dari perspektif investors, tantangan utama meliputi kesulitan menemukan high-quality sustainable technology projects, kompleksitas dalam proses due diligence terutama untuk AI-based solutions, serta minimnya tools untuk risk assessment dan impact measurement yang dapat membantu dalam pengambilan keputusan investasi.

Target users penelitian ini adalah innovators yang terdiri dari startup founders, healthcare professionals, dan university students, serta investors yang mencakup impact investors, VC partners, dan angel investors. Platform ini juga mempertimbangkan secondary users seperti government agencies, research institutions, dan industry players yang dapat mendapat manfaat dari ekosistem sustainable development yang terintegrasi.

Scope penelitian mencakup pengembangan web-based platform dengan responsive design, implementasi AI health monitoring demonstration menggunakan TensorFlow.js, serta evaluasi comprehensive menggunakan heuristic evaluation, user testing, dan quantitative assessment melalui SUS dan UEQ. Namun, penelitian ini memiliki limitations dalam hal AI demo yang menggunakan simulated data, sample size terbatas untuk user testing, dan focus yang terbatas pada SDG 9 dengan AI demonstration khusus untuk health monitoring use case.

## 1.3 Tujuan Penelitian

Tujuan umum penelitian ini adalah mengembangkan platform digital berkelanjutan yang mengintegrasikan prinsip-prinsip Human-Computer Interaction untuk memfasilitasi kolaborasi efektif antara innovators dan investors dalam ekosistem sustainable development, dengan mendemonstrasikan AI-powered health monitoring sebagai proof of concept teknologi.

Secara khusus, penelitian ini bertujuan untuk menganalisis kebutuhan dan karakteristik users dari kedua user groups melalui comprehensive user research dan task analysis, merancang user interface dan user experience yang optimal untuk platform dual-purpose menggunakan user-centered design methodology, serta mengimplementasikan AI demonstration module menggunakan TensorFlow.js untuk memberikan interactive technology showcase.

Penelitian ini juga bertujuan untuk mengevaluasi usability dan user experience platform menggunakan multiple evaluation methods, mengidentifikasi design principles dan best practices untuk platform yang melayani multiple user groups dengan technical proficiency yang berbeda, serta memberikan rekomendasi untuk pengembangan platform berkelanjutan berdasarkan user feedback dan evaluation results.

Manfaat akademis dari penelitian ini mencakup kontribusi terhadap HCI research dalam hal insights tentang designing for multiple user groups dengan different technical backgrounds, best practices untuk AI integration dalam user-facing platforms, serta methodology untuk evaluating platforms dengan complex user interactions. Penelitian ini juga memberikan educational value sebagai case study untuk sustainable technology platform development dan real-world application dari HCI principles.

Manfaat praktis untuk innovators meliputi platform untuk showcasing sustainable technology innovations, access to network of impact investors dan funding opportunities, serta tools untuk technology demonstration dan project management. Untuk investors, manfaat mencakup streamlined discovery process untuk sustainable technology projects, risk assessment tools dan impact measurement capabilities, serta access to emerging technologies dan market intelligence.

Dari perspektif sosial, penelitian ini berkontribusi pada acceleration of SDG 9 achievement melalui technology collaboration, promotion of sustainable industrial development, support untuk green technology innovation ecosystem, serta knowledge transfer dan capacity building untuk sustainable technology adoption.

## 1.4 Metodologi Penelitian

Penelitian ini menggunakan User-Centered Design (UCD) sebagai metodologi utama, yang menekankan pada pemahaman mendalam tentang users, needs, dan contexts dalam setiap tahap pengembangan platform. UCD approach dipilih karena kompleksitas requirements dari dual user groups yang memiliki goals dan technical backgrounds yang berbeda.

Tahapan UCD yang diterapkan meliputi understand context of use melalui user research dan persona development, specify requirements dengan functional dan non-functional requirements definition, design solutions dengan information architecture design dan prototyping, serta evaluate against requirements melalui heuristic evaluation dan user testing dengan standardized metrics.

Proses desain iteratif mengadaptasi Double Diamond Design Process yang mencakup discover phase dengan user research dan market analysis, define phase dengan problem definition dan user personas, develop phase dengan information architecture dan prototyping, serta deliver phase dengan implementation dan comprehensive testing.

Evaluasi dilakukan menggunakan multiple methods untuk triangulation. Heuristic evaluation menggunakan Nielsen's 10 Usability Heuristics dengan expert reviewers untuk identify usability issues early dalam design process. User testing dilakukan dengan 7 representative users covering core platform functionality dengan realistic scenarios. System Usability Scale (SUS) digunakan untuk reliable measure dari overall system usability yang memungkinkan benchmarking dengan industry standards. User Experience Questionnaire (UEQ) memberikan comprehensive assessment dari user experience quality dengan dimensional analysis yang complementing SUS results.

Research validation strategy mencakup method triangulation dengan multiple evaluation methods, data triangulation dengan quantitative dan qualitative data integration, serta evaluator triangulation dengan multiple perspectives dari different stakeholder groups. Reliability measures meliputi internal consistency checks, inter-rater reliability untuk heuristic evaluation, dan test-retest reliability untuk critical measurements.

Ethical considerations mencakup participant protection dengan informed consent dan confidentiality measures, serta research integrity dengan transparent reporting dan bias minimization. Metodologi yang komprehensif ini diharapkan dapat menghasilkan platform yang tidak hanya memenuhi kebutuhan users tetapi juga memberikan kontribusi signifikan terhadap body of knowledge dalam HCI, khususnya dalam designing platforms untuk sustainable technology collaboration.
