# Scenario Analysis: Investigating E-commerce Downtime (DDoS)
# Analyse de Scénario : Investigation d'une Interruption E-commerce (DDoS)

---

## 🇬🇧 English Version: Technical Case Study

### **Scenario Overview**
A company’s main e-commerce website suddenly went offline. Customers were unable to access services, leading to potential brand damage and financial loss. As a security analyst, I analyzed the logs to identify the root cause.

### **Log Investigation Process**
1. **Firewall & IDS/IPS Logs:** Analyzed to identify unusual traffic spikes from specific IP addresses or geographic regions that were being blocked or flagged.
2. **Application Logs:** Examined database query timeouts and functional crashes to see if the backend was overwhelmed.
3. **Server Logs:** Identified **HTTP 503 (Service Unavailable)** errors. By correlating these with the firewall spikes, I confirmed the incident was a **Distributed Denial of Service (DDoS) attack**.

### **SIEM Strategy for Mitigation**
* **Correlation:** Used SIEM to bridge the "Firewall Request" data with "Server Error" data to see the attack pattern in real-time.
* **Automated Alerting:** Configured alerts for "Failed Login Thresholds" and "Abnormal Traffic Spikes" to enable proactive defense.
* **Visualization:** Created dashboards to inform stakeholders about the attack's scale and origin.

---

## 🇫🇷 Version Française : Étude de Cas Technique

### **Aperçu du Scénario**
Le site e-commerce principal d'une entreprise est soudainement tombé en panne. Les clients ne pouvaient plus accéder aux services, entraînant une perte de confiance et des pertes financières. En tant qu'analyste, j'ai examiné les logs pour identifier la cause racine.

### **Processus d'Investigation des Logs**
1. **Logs Pare-feu et IDS/IPS :** Analyse des pics de trafic inhabituels provenant d'adresses IP ou de régions géographiques spécifiques.
2. **Logs d'Application :** Examen des délais d'attente des requêtes de base de données (timeouts) et des plantages fonctionnels.
3. **Logs Serveur :** Identification des erreurs **HTTP 503 (Service Unavailable)**. En corrélant ces données avec les pics du pare-feu, j'ai confirmé qu'il s'agissait d'une **attaque DDoS**.

### **Stratégie SIEM pour la Mitigation**
* **Corrélation :** Utilisation du SIEM pour lier les données des requêtes pare-feu aux erreurs serveur afin de visualiser le schéma d'attaque.
* **Alertes Automatisées :** Configuration d'alertes pour les "Seuils d'échec de connexion" et les "Pics de trafic anormaux" pour une défense proactive.
* **Visualisation :** Création de tableaux de bord pour informer les parties prenantes de l'ampleur et de l'origine de l'attaque.

---
