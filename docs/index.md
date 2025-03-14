# PANA – Polski Asystent w Niderlandzkiej Akademii

*(For the English version, please scroll down.)*

PANA to chatbot stworzony z myślą o polskich studentach w Holandii. Jego celem jest pomoc nowoprzybyłym studentom w nawigacji przez proces rekrutacji, adaptacji do nowego środowiska akademickiego oraz codziennych wyzwań życia w Holandii.

## 🎯 Cel projektu
- Ułatwienie dostępu do sprawdzonych informacji o studiach, mieszkaniach, pracy i formalnościach w NL.
- Zbudowanie bazy wiedzy opartej na rzeczywistych pytaniach i doświadczeniach polskich studentów.
- Integracja z chatbotem opartym na modelu Bielik od SpeakLeash, który zostanie fine-tunowany na podstawie zgromadzonych danych.

## 🏗 Jak to działa?
1. **Zbieranie danych**  
   - Studenci wypełniają formularz, zgłaszając pytania i odpowiedzi na najczęstsze problemy.
   - Odpowiedzi w języku angielskim są tłumaczone na polski.
   - Dane są przetwarzane i organizowane według kategorii (rekrutacja, mieszkanie, formalności itd.).

2. **Fine-tuning modelu**  
   - Model Bielik jest dostosowywany na podstawie zebranych pytań i odpowiedzi.
   - Do tego celu wybrano model **Bielik-7B-Instruct-v0.1-GPTQ**, który zapewnia dobrą jakość odpowiedzi i jest zoptymalizowany pod kątem wydajnego działania na GPU.
   - Model ten jest odpowiedni do użycia na Kaggle, gdzie działa efektywnie na dostępnych tam kartach graficznych (T4/P100).
   - Testujemy skuteczność odpowiedzi oraz wprowadzamy poprawki.

3. **Uruchomienie chatbota**  
   - Chatbot będzie dostępny jako aplikacja webowa i/lub integracja z Telegramem/Discordem.

## 🚀 Jak mogę pomóc?
- Wypełnij formularz z pytaniami i odpowiedziami! (🔗 [Link do formularza](#))
- Zgłoś się jako tester do wczesnej wersji chatbota.
- Dołącz do zespołu i pomóż rozwijać projekt!

## 🛠 Technologie
- Model Bielik od [SpeakLeash](https://speakleash.org/)
- **Wybrany model:** Bielik-7B-Instruct-v0.1-GPTQ (optymalizacja dla Kaggle GPU)
- Python / Transformers / Fine-tuning NLP
- Google Forms / Sheets do zbierania danych

## 📜 Licencja
Projekt jest dostępny na licencji **MIT**, co oznacza, że możesz go dowolnie używać, modyfikować i udostępniać, pod warunkiem dołączenia informacji o oryginalnym autorze.  

Należy jednak pamiętać, że chatbot korzysta z modelu **Bielik**, który działa na licencji **Apache 2.0**. Oznacza to, że wszelkie użycie tego modelu wymaga przestrzegania tej licencji. Szczegóły: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

# PANA – Polish Assistant in the Dutch Academy

PANA is a chatbot designed for Polish students in the Netherlands. Its goal is to help new students navigate the recruitment process, adapt to the academic environment, and manage daily life challenges in the Netherlands.

## 🎯 Project Goals
- Provide verified information about studies, housing, jobs, and formalities in NL.
- Build a knowledge base based on real questions and experiences of Polish students.
- Integrate a chatbot based on the Bielik model from SpeakLeash, fine-tuned with collected data.

## 🏗 How It Works?
1. **Data Collection**  
   - Students submit questions and answers via a form.
   - English answers are translated into Polish.
   - Data is processed and categorized (recruitment, housing, formalities, etc.).

2. **Fine-tuning the Model**  
   - The Bielik model is trained on collected questions and answers.
   - The chosen model is **Bielik-7B-Instruct-v0.1-GPTQ**, which provides high-quality responses and is optimized for efficient GPU usage.
   - This model is well-suited for Kaggle, where it runs efficiently on available GPUs (T4/P100).
   - Responses are tested and improved.

3. **Launching the Chatbot**  
   - The chatbot will be available as a web application and/or Telegram/Discord integration.

## 🚀 How Can You Help?
- Fill in the form with questions and answers! (🔗 [Form Link](#))
- Sign up as a tester for the early chatbot version.
- Join the team and help develop the project!

## 🛠 Technologies
- Bielik Model from [SpeakLeash](https://speakleash.org/)
- **Selected model:** Bielik-7B-Instruct-v0.1-GPTQ (optimized for Kaggle GPU)
- Python / Transformers / Fine-tuning NLP
- Google Forms / Sheets for data collection

## 📜 License
This project is released under the **MIT License**, which allows free use, modification, and distribution, as long as attribution to the original author is provided.  

However, please note that the chatbot utilizes the **Bielik** model, which operates under the **Apache 2.0 License**. This means that any use of this model requires compliance with its licensing terms. Details: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).


