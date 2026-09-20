# Portfolio Universitaire — Ainis Haichour

> Lyceen . Maker . Passionne d'infra, d'automatisation et d'IA.

Bienvenue sur le depot de mon portfolio personnel. C'est une vitrine de mes projets — persos, scolaires, ou nes d'un week-end ou j'avais juste envie de bidouiller quelque chose. Pas de framework, pas de build tools : que du HTML/CSS/JS ecrit a la main, page par page.

**[Voir le site en ligne](https://gamer3001.github.io/Portfolio-universitaire/)**

---

## Apercu

Le site adopte une identite visuelle sombre et epuree : fond noir avec un leger degrade marine, un ciel etoile anime en canvas qui reagit au scroll, et une typographie qui melange le **Cormorant Garamond** (elegance, titres) et le **DM Sans** (clarte, texte courant). Chaque page projet respecte la meme structure — nav, fond anime, modal de contact — pour garder une coherence visuelle sur l'ensemble du site.

---

## Structure du site

```
Portfolio-universitaire/
├── index.html                          # Page d'accueil — hero + grille de projets
├── diaporamas.html                     # Galerie de diaporamas (visionneuse d'images)
├── Data/                                # Assets (images, photos des projets, etc.)
│
├── Intelligence Artificielle & Automation
│   ├── kara-ia.html                    # Kara — mon JARVIS personnel (IA locale, domotique)
│   ├── esp-32(Kara).html                # Assistant vocal DIY base sur ESP32
│   ├── frigate.html                    # Detection d'objets en temps reel
│   └── n8n.html                        # Orchestration et automatisation de workflows
│
├── Infrastructure & Virtualisation
│   ├── infrastructure-proxmox.html     # Cluster Proxmox — 3 serveurs, ~20 VM/LXC
│   └── truenas.html                    # TrueNAS Scale — stockage ZFS redondant
│
├── Services & Domotique
│   ├── home-assistant.html             # Centralisation domotique
│   ├── octoprint.html                  # Gestion d'impression 3D
│   └── pihole.html                     # Blocage pub/traceurs au niveau DNS
│
├── Projets Scolaires
│   ├── cybertruck.html                 # Voiturette autonome (evitement d'obstacles)
│   ├── cisco trafik.html               # Feu tricolore pilote sans code (Cisco Packet Tracer)
│   ├── deploiment-fog.html             # Deploiement FOG — clonage d'OS en salle de cours
│   ├── datacenter-epil.html            # Datacenter EPIL — projet de fin d'annee
│   ├── virtual-Arcade.html             # VM d'emulation avec interface arcade
│   └── TailsScale.html                 # VPN Zero Trust avec Tailscale
│
└── Projets DIY
    ├── Borne-arcade.html               # Borne d'arcade construite maison
    ├── Ambilight.html                  # Systeme de lumiere reactive pour la TV
    └── Wii-portable.html               # Wii transformee en console portable (en cours)
```

---

## Stack technique

- **HTML / CSS / JavaScript vanilla** — aucune dependance, aucun framework
- **Canvas API** pour le fond anime (etoiles, parallax au scroll)
- **Google Fonts** — Cormorant Garamond & DM Sans
- **GitHub Pages** pour l'hebergement
- Chaque page est **autonome** (un seul fichier `.html`), pour rester simple a dupliquer et a heberger n'importe ou

---

## Pourquoi ce format ?

Plutot qu'un site genere avec un framework, j'ai voulu que chaque page projet reste un fichier independant, simple a copier-coller comme base pour la suivante. C'est un choix assume : ca me permet d'iterer vite sur le design sans me soucier d'une chaine de build, et ca garde le depot lisible meme sans setup particulier — on clique sur un `.html`, ca s'ouvre, c'est tout.

---

## Me contacter

- Email : [haichour.ainis3@gmail.com](mailto:haichour.ainis3@gmail.com)
- LinkedIn : [ainis-haichour](https://linkedin.com/in/ainis-haichour)
- GitHub : [gamer3001](https://github.com/gamer3001)

---

<p align="center"><i>© 2026 Ainis Haichour — Fait avec beaucoup de cafe et un peu trop de serveurs.</i></p>
