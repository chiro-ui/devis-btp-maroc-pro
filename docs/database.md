# Base de données

## Base de données

PostgreSQL (Supabase)

## Tables principales

### Utilisateurs

- profiles

### Entreprises

- companies

### Clients

- clients

### Projets

- projects

### Bordereau des Prix

- bpu_categories
- bpu_items

### Ressources

- materials
- labor
- equipment

### Devis

- estimates
- estimate_items

### Métré

- measurements

### Documents

- attachments

### Paramètres

- settings

## Relations

Un utilisateur possède plusieurs projets.

Un projet possède plusieurs devis.

Un devis possède plusieurs lignes.

Chaque ligne est liée à un article du BPU.
