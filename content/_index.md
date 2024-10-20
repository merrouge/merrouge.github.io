---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: hero
    content:
      title: Construire les briques de votre bien-être
      text: 🧱 EN TOUTE SÉCURITÉ ET A LONG TERME 🧱
      primary_action:
        text: Transformer votre santé
        url: https://ufeelgreat.com/fra/fr/c/marc.nguyen/
        icon: rocket-launch
      secondary_action:
        text: Apprendre la science
        url: https://www.unicityscience.org/clinical-validation-studies/?lang=fr
      announcement:
        text: "Lire mon blog"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: community-1.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            de personnes savent 
            cette solution
        - statistic: "10k+"
          description: |
            produits utilisés
            par jour
        - statistic: "3k+"
          description: |
            Objectif de ma  
            communauté
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Prowellness
      text: Pour une santé métabolique optimale 🧱
            {{< youtube wv650EXkFcY >}}
      items:
        - name: Pratique & Facile
          icon: bolt
          description: Faciles à intégrer dans votre vie quotidienne, avec schéma d'alimentation **4/4/12** ou jeune intermittent **16/8**.
        - name: De véritables solutions pour la santé
          icon: sparkles
          description: Produits de haute qualité avec des procédures de fabrication brevetées! Entreprise historique depuis 120 ans.
        - name: Soutenu par la science
          icon: star
          description: Innovation à la bases des études cliniques, certifications fiables, brevets internationaux, pdr.net.
        - name: Make Life Better
          icon: rectangle-group
          description: C'est notre slogan ancré dans la mentalité! *J'essaie à sauver votre vie !*
        - name: Groupe d'entraide
          icon: magnifying-glass
          description: "Participer et être suivi pour mieux adapter à ta santé: détox, booster le métabolisme, renforcement musculaire, rajeunissement ..."
        - name: Style de vie sain à long terme
          icon: code-bracket
          description: Connaissances à jour pour éviter les maladies cardiovasculaires, AVC, inverser le diabète de type 2, pré-diabète, perte de graisses ...
    design:
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Rebooster ta santé avec Feel Great
          text: Facile comme compter 1, 2, 3!
          feature_icon: check
          features:
            - "**Balance**: Complément de fibres végétales breveté"
            - "**Unimaté**: Composé à base de feuilles de yerba mate, riche en acide chlorogénique"
            - Effets cliniquement prouvés 
            - Réduction de la glycémie de 20% (1 sachet) et 28% (2 sachets)
            - Aide au jeûne intermittent
            - Contrôle de la glycémie
            - Réduction des pics d'insuline
            - Effet satiétant
            - Amélioration du contrôle du cholestérol
            - Amélioration de la signalisation de la leptine
            - Propriétés anti-diabétiques
            - Effets anti-inflammatoires
            - Soutien à la perte de poids
            - Réduction naturelle de la pression artérielle
            - Environ 5€ par jour
            - Garantie satisfaction de 90 jours
            - Option d'abonnement mensuel avec réduction et livraison gratuite
          # Upload image to `assets/media/` and reference the filename here
          image: fg-comment ca marche.png
          button:
            text: Commander
            url: https://ufeelgreat.com/fra/fr/c/marc.nguyen
        - title: Notre Communauté prenant soin de ta santé
          text: Joins notre communauté sur Facebook - poses des questions pour adapter à ta santé
          feature_icon: bolt
          features:
            - "Mettre jour les connaissances récentes"
            - "Adapter ton alimentation: Quoi? Combien? Quand?"
            - "Apprendre et partager les retours d'expériences"
            - "Échanger les suivis pour mieux adapter à ta santé"
          # Upload image to `assets/media/` and reference the filename here
          image: community-4.jpg
          button:
            text: Joins à la communauté
            url: https://facebook.com/groups/lhq1fr/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: news
    content:
      title: ''
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        folders: 
          - blog
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      columns: 3
      # Choose a layout view
      view: article-grid
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  # === Vidéo ===
  - block: features
    id: features
    content:
      title: Construire votre carrière sans risque, zero capital
      text: pour 3 🗝️ santé, temps et finance
            {{< youtube xusCcQTOKEA >}}
      # items:
      #   - name: Sincérité
      #     icon: bolt
      #     description: ""
      #   - name: Intégrité
      #     icon: sparkles
      #     description: ""
      #   - name: Bienveillance
      #     icon: star
      #     description: ""
    design:
      spacing:
        padding: [0, 0, 0, 0]
  # === Slogan ===
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Marc Nguyen"
          role: "Leader en santé et mindset"
          # Upload image to `assets/media/` and reference the filename here
          image: "photo-hh-7-5.jpg"
          text: "Unissons-nous pour offrir au monde une santé meilleure, libérer les potentiels cachés et insuffler un sens profond à chaque vie! Sincérité, Intégrité et Bienveillance!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Prêt à donner à ta vie une chance
      text: Ta santé et ton mindset!
      button:
        text: Construire ensemble
        url: https://ufeelgreat.com/fra/fr/c/marc.nguyen
    design:
      card: 
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

