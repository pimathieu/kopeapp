# KopeApp

[Version Française](#Aperçu)

### Overview

KopeApp is an open-source app suite designed to revolutionize how cooperative institutions in Haiti operate. By leveraging the latest cloud and AI technologies, KopeApp empowers cooperatives to modernize their systems, streamline their processes, and offer an expanded range of services to their members. The platform focuses on financial inclusion, transparency, and operational efficiency, providing a unified solution that addresses the unique challenges faced by cooperatives in the region. Hosted on GitHub, KopeApp invites global collaboration to continually refine and adapt the suite to meet evolving needs.

The suite includes tools tailored to address critical cooperative functions such as managing funds, facilitating instant money transfers, organizing group savings, handling international remittances, and paying bills. With its modular architecture, KopeApp ensures flexibility and scalability, enabling cooperatives to implement only the services they need while maintaining room for growth. Built with robust security and real-time capabilities, KopeApp aims to strengthen the bond between cooperative members and their institutions while driving innovation and development in Haiti's cooperative sector.

### Features

#### 1. KopeKloud

- Modernizes cooperative data systems by migrating them to the cloud.
- Enhances data accessibility, security, and scalability.

#### 2. KopeKash

- Functions like Zelle, allowing instant money transfers within the same cooperative.
- Secure with PIN and biometric authentication.

#### 3. KopeSol

- Facilitates group savings programs ("Sòl") to promote mutual financial support among members.
- Tracks contributions and manages payout schedules.

#### 4. KopeTrans

- Manages international money transfers from countries like the US, Canada, France, and South America to local cooperative accounts.
- Ensures real-time tracking for both members and administrators.

#### 5. KopeBill

- Enables members to pay bills (e.g., internet, phone) directly from their cooperative accounts.

#### 6. KopeBank

- Acts as a financial institution to manage cooperative funds.
- Provides tools for cooperative-level financial planning and management.

#### 7. KopeKat

- A virtual card system that allows members to perform online transactions securely.
- Integrates seamlessly with cooperative accounts for ease of use.

#### 8. KopeKonek

- Connects with local financial institutions (e.g., Moncache by Digicel) via APIs.
- Enables seamless integration for additional services and interoperability.

---

### Architecture

- **Infra**: Hosted on AWS Cloud, ensuring scalability and security.
- **Compute**: Serverless architecture powered by AWS Lambda (Node.js/Python) for handling business logic.
- **Database**: DynamoDB for scalable and low-latency data management.
- **Storage**: S3 for secure and reliable storage of documents, member data, and other resources.
- **Frontend**: Built with Next.js for a fast and responsive user experience across web and mobile platforms.
- **AI Support**: Integrated with AWS Bedrock for advanced AI capabilities, including data insights and natural language processing.
- **Authentication**: Managed by Amazon Cognito, providing secure user sign-up, sign-in, and access control.
- **Monitoring and Logging**: AWS CloudWatch and X-Ray for real-time monitoring, debugging, and performance optimization.
- **API Gateway**: AWS API Gateway to manage API endpoints and ensure secure communication.
- **Message Queue**: Amazon SQS for decoupling services and handling asynchronous workflows.
- **Notifications**: Amazon SNS for sending real-time alerts and updates to members.

---

### License

This project is licensed under the [MIT License](./LICENSE.md). See the LICENSE file for details.

---

[English Version](#Overview) 

### Aperçu

KopeApp est une suite d’applications open source conçue pour révolutionner le fonctionnement des institutions coopératives en Haïti. En exploitant les dernières technologies de cloud et d’intelligence artificielle, KopeApp permet aux coopératives de moderniser leurs systèmes, de rationaliser leurs processus et d’offrir une gamme de services élargie à leurs membres. La plateforme se concentre sur l’inclusion financière, la transparence et l’efficacité opérationnelle, tout en proposant une solution unifiée pour répondre aux défis uniques auxquels les coopératives de la région sont confrontées. Hébergée sur GitHub, KopeApp invite à une collaboration mondiale pour affiner et adapter continuellement la suite aux besoins évolutifs.

La suite comprend des outils conçus pour répondre aux fonctions critiques des coopératives, telles que la gestion des fonds, les transferts d’argent instantanés, l’organisation d’épargnes collectives, la gestion des envois de fonds internationaux et le paiement des factures. Avec son architecture modulaire, KopeApp garantit flexibilité et scalabilité, permettant aux coopératives d’implémenter uniquement les services dont elles ont besoin tout en préservant une marge de croissance. Conçu avec une sécurité robuste et des capacités en temps réel, KopeApp vise à renforcer les liens entre les membres des coopératives et leurs institutions tout en favorisant l’innovation et le développement dans le secteur coopératif haïtien.

### Fonctionnalités

#### 1. KopeKloud

- Modernise les systèmes de données des coopératives en les migrés vers le cloud.
- Améliore l'accessibilité, la sécurité et la scalabilité des données.

#### 2. KopeKash

- Fonctionne comme Zelle, permettant des transferts d’argent instantanés au sein d’une même coopérative.
- Sécurisé avec un code PIN et une authentification biométrique.

#### 3. KopeSol

- Facilite les programmes d'épargne collective (« Sòl ») pour promouvoir l'entraide financière entre les membres.
- Suit les contributions et gère les paiements.

#### 4. KopeTrans

- Gère les transferts d'argent internationaux depuis des pays comme les États-Unis, le Canada, la France et l’Amérique du Sud vers les comptes locaux des coopératives.
- Offre un suivi en temps réel pour les membres et les administrateurs.

#### 5. KopeBill

- Permet aux membres de payer leurs factures (internet, téléphone) directement depuis leurs comptes coopératifs.

#### 6. KopeBank

- Agit comme une institution financière pour gérer les fonds des coopératives.
- Fournit des outils pour la planification financière au niveau coopératif.

#### 7. KopeKat

- Un système de carte virtuelle qui permet aux membres d'effectuer des transactions en ligne en toute sécurité.
- S'intègre facilement avec les comptes coopératifs pour plus de commodité.

#### 8. KopeKonek

- Connecte avec des institutions financières locales (par exemple, Moncache par Digicel) via des APIs.
- Permet une intégration fluide pour des services supplémentaires et l'interopérabilité.

---


### Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

