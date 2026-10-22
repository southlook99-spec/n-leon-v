# N LEON — Chauffeur Privé Tesla Model Y · Cergy & Île-de-France

Site web officiel et plateforme de réservation pour **N LEON**, chauffeur privé VTC basé à Saint-Ouen-l'Aumône.

---

## Hébergement OVHcloud (Option retenue)

Votre nom de domaine `www.cergychauffeurprivé.fr` et votre hébergement web sont gérés directement chez **OVHcloud**.

### 1. Configuration de la Zone DNS chez OVHcloud

Dans votre espace client OVHcloud (**Web Cloud** → **Noms de domaine** → `cergychauffeurprivé.fr` → **Zone DNS**) :

- **Champ A (domaine racine `@`)** :
  - Sous-domaine : *(laisser vide)*
  - Type : `A`
  - Cible : **`51.91.236.255`**
- **Champ A (sous-domaine `www`)** :
  - Sous-domaine : `www`
  - Type : `A`
  - Cible : **`51.91.236.255`**
- **Champ TXT de validation OVH** :
  - Sous-domaine : `ovhcontrol`
  - Type : `TXT`
  - Valeur : **`xY6E1MFCdK60IA4nqqKa0g`**

*(Supprimez l'ancienne adresse IP de parking `213.186.33.5` si elle était encore présente).*

### 2. Déploiement des fichiers dans le dossier `www` d'OVH

1. Connectez-vous à votre espace FTP OVHcloud (ou via l'explorateur de fichiers Web Cloud OVH).
2. Ouvrez le dossier **`www`**.
3. Déposez-y le fichier `index.html` (issu de `public/ovh-index.html`).
4. Créez un sous-dossier `images` et déposez-y vos photos :
   - `images/tesla-model-y-black.jpg`
   - `images/tesla-model-y-interior.jpg`
   - `images/paris-airport-transfer.jpg`

### 3. Activation du Certificat SSL (HTTPS) chez OVH

Dans votre espace OVHcloud (**Web Cloud** → **Hébergement** → onglet **Multisite**) :
- Cliquez sur les trois petits points à droite de votre domaine → **Générer un certificat SSL**.
- En quelques minutes, votre site sera sécurisé en `https://www.cergychauffeurprivé.fr`.

---

## Caractéristiques du Véhicule

- **Modèle** : Tesla Model Y Noire Premium
- **Jantes** : 19 pouces noires
- **Intérieur** : Cuir noir intégral & toit panoramique
- **Vitrage** : Vitres arrière surteintées pour l'intimité des passagers
- **Capacité** : 1 à 4 passagers confort

---

## Tarifs & Conditions

- **Course / Transfert** : Forfait de départ 10 € + 2,00 €/km
- **Mise à disposition** : Devis personnalisé selon programme et durée
- **Annulation** : Sans frais jusqu’à 1 heure avant la prise en charge
- **Contact** : 06 34 50 70 01 · `nleonfm@gmail.com`
- **SIRET** : 812 053 320 00030
