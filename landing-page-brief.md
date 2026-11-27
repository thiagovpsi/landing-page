# Bilingual Clinical Psychology Landing Page — Project Brief

**Project type:** Static bilingual website for GitHub Pages  
**Primary languages:** English (`en`) and Brazilian Portuguese (`pt-BR`)  
**Primary audience:** Autistic adults who are looking for clinical psychology services  
**Secondary audiences:** Adolescents and their families, parents or caregivers, and psychology or health professionals who are interested in professional guidance or supervision  
**Writing approach:** Clear English inspired by ASD-STE100 principles  
**Status:** Content draft. All bracketed fields must be completed and checked before publication.

---

## 1. Project purpose

Create a calm, clear, accessible, and trustworthy landing page for a clinical psychology service. The page must explain the professional's work, show the services that are available, answer common practical questions, and make it easy to start a contact conversation.

The website must support two languages:

- English (`en`)
- Brazilian Portuguese (`pt-BR`)

The project brief and technical instructions in this file are written in English. The website must provide complete English and Brazilian Portuguese versions of all user-facing text. Do not mix both languages in the same paragraph. Use a clear language switch.

The page must not act as a diagnostic tool, a clinical intake form, or an emergency service.

## 2. Known professional and service information

The information below comes from the service description supplied for this project. It is not a substitute for professional credential checks.

### Main area of work

- Clinical psychology services.
- A focus on psychotherapy for adults with Autism Spectrum Disorder (ASD). In Brazilian Portuguese, use **Transtorno do Espectro Autista (TEA)**.

### Other services reported

- Psychotherapy for people with ASD.
- Adult appointments.
- Adolescent appointments.
- Therapeutic accompaniment.
- Parental guidance for family members.
- Supervision or professional guidance.

### Current contact and service journey

- People find the service through referrals, Instagram, Google Search or Google Maps, and WhatsApp.
- WhatsApp Business is the main contact channel.
- The professional currently explains the service, professional background, session duration, frequency, available times, payment methods, and first-session process by message.
- Appointments are arranged manually through WhatsApp.
- The schedule is currently kept in a paper diary.
- The reported volume is approximately 1–5 new enquiries per month.
- The main audience is adults with an ASD diagnosis.

### Information that is not yet confirmed

Do not invent any of the following details. Use the placeholders in this brief until the professional supplies and verifies them:

- Full professional name: `[FULL PROFESSIONAL NAME]`
- Professional title and active registration: `[PSYCHOLOGIST — CRP/UF AND REGISTRATION NUMBER]`
- Verified education and qualifications: `[VERIFIED QUALIFICATIONS]`
- Additional professional training: `[VERIFIED TRAINING]`
- City and state: `[CITY, STATE, BRAZIL]`
- In-person address, if it is appropriate to publish: `[PUBLIC PRACTICE ADDRESS OR OMIT]`
- Service modality: `[ONLINE / IN-PERSON / BOTH — CONFIRM]`
- Session duration: `[SESSION DURATION]`
- Typical frequency: `[FREQUENCY, IF THE PROFESSIONAL CHOOSES TO PUBLISH IT]`
- Fees and payment methods: `[PRIVATE CONTACT INFORMATION — DO NOT USE FEES AS PUBLIC ADVERTISING]`
- WhatsApp contact: `[INTERNATIONAL WHATSAPP NUMBER]`
- Professional email: `[CONTACT EMAIL]`
- Instagram profile: `[INSTAGRAM URL]`
- Google Business Profile: `[GOOGLE BUSINESS PROFILE URL, IF AVAILABLE]`
- Working hours for enquiries: `[ENQUIRY RESPONSE HOURS]`

Do not claim that the professional is a specialist in ASD unless the professional confirms that the title is accurate and may be used under the applicable professional rules. A safer draft phrase is **“clinical psychology services with a focus on autistic adults.”**

---

## 3. Recommended page structure

Use one main page with these sections:

1. Header and language switch.
2. Hero section.
3. About the professional.
4. Services.
5. How to make first contact.
6. Practical information.
7. Frequently asked questions.
8. Contact section.
9. Footer with professional identification and privacy information.

Keep the navigation short. Use descriptive link labels. Do not use pop-ups, auto-playing media, flashing effects, or urgent sales language.

## 4. Bilingual website requirements

### Language behavior

- Provide a visible language switch labelled `EN` and `PT-BR`.
- Set English as the initial display language unless the developer chooses to detect the browser language. If browser language detection is used, provide a visible way to change the language.
- Translate every visible interface item, including navigation, buttons, form labels, validation messages, metadata, FAQ headings, and footer text.
- Update the document language attribute when the user changes language: `lang="en"` or `lang="pt-BR"`.
- Keep the language choice during the current browser session. Local browser storage may be used for this preference only.
- Do not translate the professional's official name, CRP registration, or proper names.
- Do not use automatic machine translation as the only translation review. Have both language versions checked for meaning and professional accuracy.

### Suggested implementation

For a small GitHub Pages project, use a static site. Keep both language dictionaries in one JavaScript file or in two clearly named content files. A language switch can update the text without a server or database.

Suggested project structure:

```text
/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── translations.js
│   └── images/
│       └── professional-photo.webp
├── README.md
└── landing-page-brief.md
```

Do not add a patient database, clinical records, or diagnostic questionnaire to this static website.

---

## 5. Landing page copy — English

The text below is a draft. The professional must review it and confirm that it describes the actual service.

### 5.1 Header

- Home
- About
- Services
- How it works
- Contact
- Language switch: `EN | PT-BR`

### 5.2 Hero section

**Headline**  
Clinical psychology with a focus on autistic adults.

**Supporting text**  
Psychological care for adults and adolescents, with clear information about the process and space for each person's needs and goals.

**Primary call to action**  
Contact the professional

**Secondary call to action**  
Learn about the services

**Short note**  
The first contact is an opportunity to ask practical questions and learn how the service works. It is not a clinical assessment.

### 5.3 About the professional

**Section title**  
About the professional

**Draft text**  
I provide clinical psychology services, with a focus on psychotherapy for autistic adults. I also offer services for adolescents, parental guidance, therapeutic accompaniment, and professional guidance or supervision, according to the scope of my training and practice.

My aim is to explain the service in a clear way. You can ask about the format, session length, frequency, availability, and payment before you decide whether to schedule a first appointment.

**Professional identification block — required fields**  
`[FULL PROFESSIONAL NAME]`  
`Psychologist — CRP [REGIONAL COUNCIL / REGISTRATION NUMBER]`  
`[VERIFIED QUALIFICATIONS AND TRAINING]`

Do not publish this section until all credentials and descriptions have been checked.

### 5.4 Services

**Section title**  
Services

**Service 1 — Psychotherapy for autistic adults**  
Psychotherapy for adults on the autism spectrum. The work is discussed with each person and takes account of their needs, context, and goals.

**Service 2 — Psychology services for adolescents**  
Psychological care for adolescents. Contact and consent procedures must follow the applicable professional and legal requirements.

**Service 3 — Therapeutic accompaniment**  
Therapeutic accompaniment, where this service is part of the professional's verified scope of practice. Add a clear description of the format, setting, and limits of the service before publication.

**Service 4 — Parental guidance**  
Guidance for parents and family members. The purpose, participants, and boundaries of this service must be explained before scheduling.

**Service 5 — Professional guidance or supervision**  
Professional guidance or supervision for other professionals, where supported by the professional's qualifications and experience. Add the target audience and format before publication.

### 5.5 How first contact works

**Section title**  
How to make first contact

1. **Send a message.** Use WhatsApp or email to ask about the service.
2. **Receive practical information.** The professional can explain the service, format, session length, availability, and fees.
3. **Decide whether to schedule.** You can review the information and decide whether you want to book a first appointment.
4. **Confirm the appointment.** If you choose to proceed, the professional will agree on a date and time with you.

**Note**  
You do not need to send a diagnosis, medical report, or private clinical history in the first message.

### 5.6 Practical information

Use a simple list or cards. Publish only confirmed information.

- **Format:** `[ONLINE / IN-PERSON / BOTH — CONFIRM]`
- **Location:** `[CITY, STATE, BRAZIL]` or `[PUBLIC ADDRESS, IF APPROPRIATE]`
- **Session length:** `[SESSION DURATION]`
- **Frequency:** `[CONFIRMED INFORMATION OR OMIT]`
- **Availability:** Confirmed directly with the professional.
- **Fees and payment:** Shared directly with the person before the service starts. Do not use price or discounts as public advertising.

### 5.7 Frequently asked questions

**Do I need to send my diagnosis before I make contact?**  
No. You can first ask practical questions about the service. Do not send sensitive documents in the first message.

**Can I ask about fees before I schedule?**  
Yes. The professional will explain the fee and payment conditions before the service starts.

**Can I ask about online or in-person appointments?**  
Yes. Contact the professional to confirm which formats are available.

**How long is a session?**  
The professional will confirm the session length before scheduling.

**How often do appointments take place?**  
The frequency depends on the service and the professional's assessment. The professional will explain the options during the appropriate conversation.

**Does the website provide diagnosis or emergency care?**  
No. This website provides general information about the service. It does not provide diagnosis, treatment, or emergency support.

### 5.8 Contact section

**Heading**  
Would you like to know more?

**Text**  
Contact the professional to ask about the service, available formats, fees, and appointment times. You can decide whether to schedule after you receive this information.

**Primary button**  
Contact via WhatsApp

**Secondary link**  
Send an email

**WhatsApp pre-filled message**  
Hello. I would like to receive information about the psychology services and appointment options.

### 5.9 Footer

`[FULL PROFESSIONAL NAME]`  
`Psychologist — CRP [REGIONAL COUNCIL / REGISTRATION NUMBER]`  
`[CITY, STATE, BRAZIL]`  
`[PROFESSIONAL EMAIL]`  
`Privacy notice`  
`This website provides general information. It does not replace an individual professional consultation.`

---

## 6. Landing page copy — Brazilian Portuguese

The Portuguese version must express the same meaning as the English version. Do not translate word by word if a natural and accurate Brazilian Portuguese sentence is better.

### 6.1 Header

- Início
- Sobre
- Serviços
- Como funciona
- Contato
- Language switch: `EN | PT-BR`

### 6.2 Hero section

**Headline**  
Psicologia clínica com foco em adultos no espectro autista.

**Supporting text**  
Atendimento psicológico para adultos e adolescentes, com informações claras sobre o processo e espaço para as necessidades e os objetivos de cada pessoa.

**Primary call to action**  
Entre em contato

**Secondary call to action**  
Conheça os serviços

**Short note**  
O primeiro contato permite esclarecer dúvidas práticas e conhecer o funcionamento do serviço. Não é uma avaliação clínica.

### 6.3 About the professional

**Section title**  
Sobre o profissional

**Draft text**  
Ofereço serviços de psicologia clínica, com foco em psicoterapia para adultos no espectro autista. Também realizo atendimentos de adolescentes, orientação parental, acompanhamento terapêutico e orientação ou supervisão profissional, de acordo com minha formação e área de atuação.

Meu objetivo é explicar o serviço de forma clara. Você pode perguntar sobre modalidade, duração das sessões, frequência, disponibilidade e valores antes de decidir pelo agendamento de uma primeira consulta.

**Professional identification block — required fields**  
`[NOME COMPLETO DO(A) PROFISSIONAL]`  
`Psicólogo(a) — CRP [REGIONAL / NÚMERO DE REGISTRO]`  
`[FORMAÇÃO E QUALIFICAÇÕES VERIFICADAS]`

Do not publish this section until all credentials and descriptions have been checked.

### 6.4 Services

**Section title**  
Serviços

**Service 1 — Psychotherapy for autistic adults**  
Psicoterapia para adultos no espectro autista. O trabalho é conversado com cada pessoa e considera suas necessidades, seu contexto e seus objetivos.

**Service 2 — Psychology services for adolescents**  
Atendimento psicológico para adolescentes. Os procedimentos de contato e consentimento devem seguir as exigências profissionais e legais aplicáveis.

**Service 3 — Therapeutic accompaniment**  
Acompanhamento terapêutico, quando fizer parte do escopo de atuação confirmado do(a) profissional. Antes da publicação, incluir uma descrição clara do formato, contexto e limites do serviço.

**Service 4 — Parental guidance**  
Orientação para pais e familiares. A finalidade, os participantes e os limites do serviço devem ser explicados antes do agendamento.

**Service 5 — Professional guidance or supervision**  
Orientação ou supervisão profissional para outros profissionais, quando compatível com a formação e a experiência do(a) profissional. Antes da publicação, informar o público e o formato.

### 6.5 How first contact works

**Section title**  
Como funciona o primeiro contato

1. **Envie uma mensagem.** Use o WhatsApp ou o e-mail para perguntar sobre o serviço.
2. **Receba as informações práticas.** O(a) profissional poderá explicar o serviço, a modalidade, a duração da sessão, a disponibilidade e os valores.
3. **Decida se deseja agendar.** Você pode analisar as informações e decidir se deseja marcar uma primeira consulta.
4. **Confirme o agendamento.** Caso decida prosseguir, o(a) profissional combinará com você a data e o horário.

**Note**  
Você não precisa enviar diagnóstico, laudo ou histórico clínico particular na primeira mensagem.

### 6.6 Practical information

- **Modalidade:** `[ONLINE / PRESENCIAL / AMBAS — CONFIRMAR]`
- **Localização:** `[CIDADE, ESTADO, BRASIL]` ou `[ENDEREÇO PÚBLICO, SE APROPRIADO]`
- **Duração da sessão:** `[DURAÇÃO]`
- **Frequência:** `[INFORMAÇÃO CONFIRMADA OU OMITIR]`
- **Disponibilidade:** Confirmada diretamente com o(a) profissional.
- **Valores e pagamento:** Informados diretamente à pessoa antes do início do serviço. Não usar preço ou desconto como publicidade.

### 6.7 Frequently asked questions

**Preciso enviar meu diagnóstico antes de entrar em contato?**  
Não. Primeiro, você pode perguntar sobre o funcionamento do serviço. Não envie documentos sensíveis na primeira mensagem.

**Posso perguntar os valores antes de agendar?**  
Sim. O(a) profissional informará o valor e as condições de pagamento antes do início do serviço.

**Posso perguntar sobre atendimento online ou presencial?**  
Sim. Entre em contato para confirmar quais modalidades estão disponíveis.

**Qual é a duração da sessão?**  
O(a) profissional informará a duração antes do agendamento.

**Com que frequência acontecem os atendimentos?**  
A frequência depende do serviço e da avaliação profissional. As possibilidades serão explicadas na conversa adequada.

**O site oferece diagnóstico ou atendimento de emergência?**  
Não. Este site apresenta informações gerais sobre o serviço. Ele não oferece diagnóstico, tratamento ou suporte de emergência.

### 6.8 Contact section

**Heading**  
Gostaria de saber mais?

**Text**  
Entre em contato para perguntar sobre o serviço, as modalidades disponíveis, os valores e os horários. Você poderá decidir se deseja agendar depois de receber essas informações.

**Primary button**  
Falar pelo WhatsApp

**Secondary link**  
Enviar e-mail

**WhatsApp pre-filled message**  
Olá. Gostaria de receber informações sobre os serviços de psicologia e as opções de atendimento.

### 6.9 Footer

`[NOME COMPLETO DO(A) PROFISSIONAL]`  
`Psicólogo(a) — CRP [REGIONAL / NÚMERO DE REGISTRO]`  
`[CIDADE, ESTADO, BRASIL]`  
`[E-MAIL PROFISSIONAL]`  
`Aviso de privacidade`  
`Este site apresenta informações gerais. Ele não substitui uma consulta profissional individual.`

---

## 7. Accessibility and sensory-aware design

Design for clear and predictable use. Do not assume that one design works for every autistic person. Avoid sensory-heavy effects and give visitors control over the page.

### Visual design

- Use a calm, consistent visual system.
- Use readable font sizes and clear spacing.
- Use strong text/background contrast.
- Do not use color alone to show meaning.
- Avoid flashing, pulsing, parallax, rapid movement, and decorative animation.
- Do not autoplay video or audio.
- Respect the `prefers-reduced-motion` system setting.
- Keep page sections in a predictable order.
- Keep navigation short and consistent.

### Interaction design

- Use clear labels for buttons and links.
- Make keyboard focus visible.
- Ensure all controls work with a keyboard.
- Give buttons and form fields clear names.
- Use large, easy-to-select controls on mobile.
- Do not use time limits for reading or contact actions.
- Do not open unexpected pop-ups.
- Keep the language switch easy to find.

### Content design

- Use short paragraphs.
- Use one main idea in each paragraph.
- Explain professional terms when needed.
- Use literal, direct headings.
- Avoid idioms, pressure, exaggerated claims, and vague promises.
- Explain what happens after a visitor clicks a contact button.

Target WCAG 2.2 AA as an implementation goal. Do not claim WCAG conformance until the published page has been tested.

---

## 8. ASD-STE100 writing approach

The user requested ASD-STE100. The correct name is **ASD-STE100 Simplified Technical English**. Issue 9 is dated 15 January 2025.

ASD-STE100 is a controlled language standard for technical documentation. It is not a website marketing standard. This project can adopt selected clarity principles, but must not claim that this landing page is certified or fully compliant with ASD-STE100.

Apply these principles to the English copy:

- Use short sentences.
- Put one main idea in each sentence.
- Prefer active voice.
- Use familiar words where possible.
- Use the same term for the same concept.
- Avoid idioms and ambiguous phrases.
- Explain a necessary technical term.
- Use clear headings and direct instructions.
- Avoid unnecessary adjectives and promotional language.

The official ASD-STE100 specification includes writing rules and a controlled dictionary. Use the official source if strict compliance is required. Do not copy the standard's protected content into this project.

---

## 9. Professional ethics, privacy, and safety requirements

This section is a publication checklist. It is not legal advice. The professional must review the final website against current CFP guidance, the applicable Regional Psychology Council guidance, and Brazilian law.

### Professional identification and advertising

Before publication:

- Show the professional's full name or permitted professional name.
- Show the professional title.
- Show the CRP regional identification and registration number.
- Publish only qualifications and titles that the professional holds.
- Describe only services and methods that are within the professional's authorized scope.
- Do not promise a specific result.
- Do not use sensational language.
- Do not compare the professional with other professionals.
- Do not use price, discounts, or promotions as public advertising.
- Do not publish patient stories, images, quotes, or testimonials as marketing content.

Fees must still be explained directly to a prospective client before the service starts. The public landing page should invite the visitor to ask for practical information without using price as an advertising claim.

### Privacy

- Do not ask visitors to submit a diagnosis, report, medication list, clinical history, or other health information through the landing page.
- Prefer a direct WhatsApp link with a neutral pre-filled message.
- If a contact form is added, collect only the minimum contact information needed. Explain the purpose, who receives it, and how long it is retained.
- Do not send health information to analytics, advertising pixels, or third-party marketing tools.
- Do not place patient names, phone numbers, appointment details, or clinical notes in public GitHub files, source code, issues, or commits.
- Keep the website separate from clinical records and the clinical schedule.
- Add a privacy notice before collecting any personal data.

### Emergency message

The website is not an emergency service. If the professional chooses to add emergency guidance, the wording and local contact information must be checked before publication. Do not invent emergency phone numbers or promise immediate response.

---

## 10. GitHub Pages publishing checklist

- [ ] Create a GitHub repository for the website.
- [ ] Add `index.html` at the repository root, or configure the correct publishing folder.
- [ ] Add the CSS, JavaScript, and image assets.
- [ ] Add both language versions.
- [ ] Test the `EN` and `PT-BR` language switch.
- [ ] Test the page on desktop and mobile.
- [ ] Test WhatsApp and email links.
- [ ] Test keyboard navigation and visible focus.
- [ ] Test contrast and text resizing.
- [ ] Check that the page has no placeholder text.
- [ ] Check all professional claims and registration details.
- [ ] Check privacy and cookie/analytics behavior.
- [ ] Enable GitHub Pages in repository settings.
- [ ] Open the published URL in a private browser window.
- [ ] Test both languages on the published website.

### Suggested metadata

English page title:  
`Clinical Psychology | Support for Autistic Adults`

Portuguese page title:  
`Psicologia Clínica | Atendimento a Adultos no Espectro Autista`

English description:  
`Clinical psychology services with a focus on autistic adults. Learn about the services, appointment formats, and how to make contact.`

Portuguese description:  
`Serviços de psicologia clínica com foco em adultos no espectro autista. Conheça os atendimentos, as modalidades e como entrar em contato.`

---

## 11. Items to confirm before the developer builds the final page

The developer must not guess these details. Ask the professional to confirm each item:

1. What full professional name must appear on the website?
2. What is the exact CRP regional identification and registration number?
3. Which qualifications and training can be published?
4. Which city and state should appear?
5. Is the service online, in person, or both?
6. What is the public practice address, if any?
7. What is the session duration?
8. Which services are currently available?
9. What exactly does therapeutic accompaniment include?
10. What is the scope and audience for professional supervision or guidance?
11. Which WhatsApp number and email should be published?
12. What are the professional's enquiry response hours?
13. Should English or Brazilian Portuguese be the default language?
14. Is there a professional photo and permission to publish it?

---

## 12. References

- ASD-STE100 official website: https://www.asd-ste100.org/
- ASD-STE100 Issue 9 and official downloads: https://www.asd-ste100.org/STE_downloads.html
- ASD-STE100 official FAQ: https://www.asd-ste100.org/STE_faq.html
- W3C Web Content Accessibility Guidelines (WCAG) 2.2: https://www.w3.org/TR/WCAG22/
- Authorized Brazilian Portuguese WCAG 2.2 translation: https://www.w3.org/Translations/WCAG22-pt-BR/
- Federal Council of Psychology — professional advertising guidance: https://transparencia.cfp.org.br/crp16/pergunta-frequente/publicidade-dos-servicos-psicologicos/
- Brazilian General Data Protection Law (LGPD), Law No. 13,709/2018: https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm

**Publication rule:** The page is a draft until the professional confirms all details, verifies professional advertising rules, checks both language versions, and approves the final content.
