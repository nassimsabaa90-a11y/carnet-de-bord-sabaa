# Préparation de la séance 2 – Nassim Sabaa

## 1. Résumé de la page Cloud en anglais (5 lignes)
*Source lue : AWS – What is Cloud Computing?*

1. Le cloud computing permet d'accéder à la demande via Internet à des ressources informatiques (serveurs, stockage, bases de données, réseaux) sans acheter de matériel physique.
2. Le modèle de facturation repose généralement sur le paiement à l'usage (*pay-as-you-go*), ce qui évite de gros investissements au départ.
3. Il offre une grande élasticité : il est possible d'augmenter ou de réduire la capacité en quelques minutes selon les besoins réels.
4. On distingue trois principaux modèles : l'IaaS (infrastructure), le PaaS (plateforme de développement) et le SaaS (logiciels prêts à l'emploi).
5. Les fournisseurs gèrent la maintenance matérielle et l'infrastructure mondiale, permettant aux équipes de se concentrer sur leurs projets.

---

## 2. Début de fiche de veille : Docker

- **Catégorie :** Conteneurisation / Environnement d'exécution
- **À quoi ça sert ?** Docker permet d'empaqueter une application (ou un site web) avec tout ce dont elle a besoin pour fonctionner dans un « conteneur » léger et portable.
- **Avantages pour le projet :**
  - Le site ou l'application fonctionne exactement de la même façon sur n'importe quel ordinateur (Windows, macOS, Linux).
  - Démarrage rapide et isolation propre sans polluer le système principal.
- **Limites / Points d'attention :**
  - Nécessite d'installer Docker Desktop (consomme de la RAM sur Windows) et d'apprendre les bases d'un `Dockerfile` / `docker-compose.yml`.
- **Sources utilisées :** `https://docs.docker.com/` et `https://github.com/docker/compose`
- **Prochaine étape (séance 2) :** Tester un premier conteneur simple (ex. serveur web Nginx) avec une page HTML.
