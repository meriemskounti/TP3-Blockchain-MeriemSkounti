# TP3 Blockchain — Analyse d'une transaction Bitcoin (TestNet4)

**Auteure :** Meriem Skounti — Master FinTech  
**Statut :** Projet individuel  

## 1. Question traitée
Comment fonctionne techniquement une transaction Bitcoin sur le réseau TestNet4 (entrées, sorties, modèle UTXO, frais de transaction et confirmations) lors d'un transfert entre deux portefeuilles ?

## 2. Démarche suivie
1. **Configuration des portefeuilles :** Création de deux portefeuilles distincts (Wallet A et Wallet B) sur **Wasabi Wallet** connecté au réseau de test **Bitcoin TestNet4**.
2. **Alimentation via Faucet :** Réception de fonds de test sur le Wallet A.
3. **Exécution du transfert :** Envoi de fonds du Wallet A vers le Wallet B.
4. **Vérification et analyse :** Inspection des identifiants de transaction (TXID) sur l'explorateur **Mempool.space** afin d'analyser les entrées (inputs), les sorties (outputs et adresse de rendu), les frais de minage et le nombre de confirmations.

## 3. Résultat principal (Livrable)
Le rapport complet contenant les captures d'écran de Wasabi Wallet, les liens de preuve Mempool.space et l'analyse détaillée du modèle UTXO est disponible dans ce dépôt :
* 📄 **[Analyse_Transaction_TestNet4_TP3.pdf](./Analyse_Transaction_TestNet4_TP3.pdf)**

## 4. Sources et outils utilisés
* **Logiciel de portefeuille :** Wasabi Wallet (réseau Bitcoin TestNet4)
* **Explorateur blockchain :** [Mempool.space (TestNet4)](https://mempool.space/testnet4)
* **Assistance IA :** Utilisation d'un assistant IA (Gemini) pour la structuration du rapport analytique, la reformulation technique du modèle UTXO et la mise en forme du fichier `README.md`. L'ensemble des transactions et captures d'écran a été réalisé et vérifié personnellement.