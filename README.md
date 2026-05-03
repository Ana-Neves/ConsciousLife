## Conscious Life

## 📋 About the project
This project was developed in Module 5 of the [Programmers of Tomorrow](https://programadoresdoamanha.org/) program, by Squad 1, composed of Alexsandro Filho, Ana Carolina Neves, Brenda Machado, Elzo Íthallo, Hewel Vieira, Jamyle Elen, Joicy Kelly, and Rodrigo Átila. The project applies the knowledge acquired in Module 4 on REST APIs, with the goal of providing an educational and accessible platform that promotes health and knowledge about sexually transmitted infections (STIs).

This repository contains the front-end of the Conscious Life website, responsible for managing intuitive and dynamic screens, where the user can register, log in, and will have graphs, cards, and a dynamic map. The project's back-end, developed in parallel, can be accessed in the following repository: [Conscious Life - Back-end](https://github.com/brenddamachado/VidaConsciente_Back).

## 🚫 Problem Statement
Sexually transmitted infections continue to be a public health challenge, largely due to a lack of knowledge and awareness among the population. Many people do not have easy access to reliable information about prevention and care, which contributes not only to the spread of these diseases but also to the propagation of false information and myths about the subject. This misinformation can lead to risky behaviors, delay diagnoses, and hinder proper treatment.

- **What are STDs/STIs?**
STDs (Sexually Transmitted Diseases) or STIs (Sexually Transmitted Infections) are diseases or infections that are mainly transmitted through unprotected sexual contact, whether vaginal, anal, or oral. They can be caused by bacteria, viruses, fungi, or parasites. The term "STI" is more recent and is being used more frequently, as it highlights that a person can be infected and transmit the disease even without showing apparent symptoms.

Among the most common STDs/STIs are: HIV/AIDS, syphilis, gonorrhea, chlamydia, genital herpes, HPV, and trichomoniasis. Prevention of these diseases is mainly done through the use of condoms and education about safe sex practices.

## 💡 Solution
Conscious Life proposes an educational and accessible solution, centralizing information about STDs/STIs in a practical and clear way. The website offers data on symptoms, treatments, prevention, types and cases of STDs/STIs, among other information that can help in raising awareness and promoting health.

## 🚀 Technologies Used
- **React**: Used to build the user interface, ensuring a dynamic and responsive experience.

- **Express.js**: Back-end framework used to build the REST API.

- **Node.js**: Runtime environment for the back-end, allowing the creation of an efficient API.

- **Leaflet**: Interactive map library used to display the testing locations of STDs.

- **Chart.js**: Used to create charts that display the evolution of STD cases over time.

- **Axios**: HTTP request library used for communication between the front-end and the back-end.

- **Styled Components**: For styling components with CSS-in-JS, allowing for a customizable and modern interface.

## 🚫 Deployment Problem
Unfortunately, it was not possible to deploy the application in this version. Therefore, to run the project locally, it is necessary to download and run **both the front-end and back-end repositories**.

### ▶ How to run the project (front-end and back-end)

To clone and run this project, follow the steps below:

1. **Clone the repositories (front and back-end)**:

- Front-end:

``bash
git clone https://github.com/brenddamachado/VidaConsciente

``

- Back-end:

``bash
git clone https://github.com/brenddamachado/VidaConsciente_Back

``

2. **Install the dependencies**:

- Access the project folders and install the dependencies on both the front-end and the back-end:

``bash
cd VidaConsciente
npm install

``

``bash
cd ../VidaConsciente_Back
npm install

``

3. **Run the front-end**:

- After installing the dependencies, run the command below to run the Front-end:

``bash
npm run dev

``

4. **Run the back-end**:

- In another terminal tab, access the back-end folder and run the server:

``bash
npm run dev

``

5. **Open your browser**:

- Access the project running at `http://localhost:3000` to view the front-end.

## 📅 Conclusion
The Vida Consciente project was developed with the goal of offering an educational and accessible platform, promoting awareness and self-care regarding sexually transmitted infections (STIs). Through the CRUD functionalities implemented in the four main APIs, users can manage personal information, access data on STIs, locate testing and treatment centers, and view registered cases. This project has a p
