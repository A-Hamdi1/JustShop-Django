# JustShop - Plateforme E-commerce Django

JustShop est une application web e-commerce moderne développée avec Django, offrant une interface utilisateur intuitive et des fonctionnalités complètes de gestion de boutique en ligne.

## 🌟 Fonctionnalités

- **Gestion des Produits**
  - Catégorisation des produits (Alimentaire, Linge de Maison, Électronique, Design-Création)
  - Types de produits (Emballé, Frais, Conserve)
  - Gestion des images de produits
  - Système de prix et descriptions détaillées

- **Gestion des Fournisseurs**
  - Informations complètes (nom, adresse, email, téléphone)
  - Interface d'administration des fournisseurs

- **Système de Panier**
  - Ajout/Suppression de produits
  - Gestion des quantités
  - Calcul automatique des totaux
  - Session utilisateur persistante

- **API REST**
  - Endpoints pour les produits
  - Endpoints pour les fournisseurs
  - Endpoints pour les catégories

- **Interface Utilisateur**
  - Design responsive
  - Navigation intuitive
  - Formulaire de contact
  - Filtrage par catégories

## 🛠️ Technologies Utilisées

- **Backend**
  - Django 4.x
  - Django REST Framework
  - SQLite (Base de données)

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript
  - Bootstrap

## 📋 Prérequis

- Python 3.8+
- pip (gestionnaire de paquets Python)
- virtualenv (recommandé)

## 🚀 Installation

1. Cloner le repository
```bash
git clone https://github.com/votre-username/JustShop-Django.git
cd JustShop-Django
```

2. Créer et activer l'environnement virtuel
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Installer les dépendances
```bash
pip install -r requirements.txt
```

4. Effectuer les migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Créer un superutilisateur
```bash
python manage.py createsuperuser
```

6. Lancer le serveur
```bash
python manage.py runserver
```

## 📁 Structure du Projet

```
JustShop-Django/
├── shop/                    # Application principale
│   ├── models.py           # Modèles de données
│   ├── views.py            # Logique de l'application
│   ├── urls.py             # Configuration des URLs
│   ├── forms.py            # Formulaires
│   ├── serializers.py      # Sérialiseurs API
│   └── templates/          # Templates HTML
├── justshop/               # Configuration du projet
│   ├── settings.py         # Paramètres Django
│   ├── urls.py             # URLs principales
│   └── wsgi.py            # Configuration WSGI
├── media/                  # Fichiers médias
├── manage.py              # Script de gestion Django
└── db.sqlite3             # Base de données
```

## 🔒 Sécurité

- Protection CSRF
- Authentification utilisateur
- Validation des formulaires
- Gestion sécurisée des sessions

## 📝 API Endpoints

- `/api/produits/` - Liste et création de produits
- `/api/fournisseurs/` - Liste et création de fournisseurs
- `/api/categories/` - Liste des catégories

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👥 Auteurs

- Votre Nom - Développeur Principal

## 📞 Contact

Pour toute question ou suggestion, n'hésitez pas à nous contacter via :
- Email : hamdi.akram.dev@gmail.com
- Issues GitHub : [Créer une issue](https://github.com/A-Hamdi1/JustShop-Django/issues) 
