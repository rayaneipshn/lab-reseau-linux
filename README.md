## ⚙️ Configuration réseau

Interface réseau :
- eth0

Adresse IP :
- 10.0.2.15 (réseau NAT VirtualBox)

---

## 🔍 Tests réalisés

### Test de connectivité internet
Commande :
ping 8.8.8.8

Résultat :
- communication fonctionnelle
- temps moyen ~15 ms

---

### Test DNS
Commande :
ping google.com

Résultat :
- résolution DNS fonctionnelle
- communication avec serveur distant

## 🧠 Analyse

- La machine utilise un réseau NAT fourni par VirtualBox
- L’adresse IP (10.0.2.15) est attribuée automatiquement
- L’accès internet est fonctionnel sans configuration manuelle
- Le DNS permet de traduire les noms de domaine en adresses IP
