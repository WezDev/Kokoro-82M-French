# Kokoro-82M-French
Guide d'utilisation de Kokoro 82M en Français 

📣 12 janvier Statut : intention d'améliorer le modèle de base https://hf.co/hexgrad/Kokoro-82M/discussions/36

❤️ Serveur Discord Kokoro : https://discord.gg/QuGxSWBfQy

🚨Vous avez des données synthétiques ? Vous voulez des packs de voix entraînés ? Voir https://hf.co/posts/hexgrad/418806998707773

Kokoro est un modèle TTS de pointe pour sa taille de 82 millions de paramètres (texte en entrée/audio en sortie).

Le 25 décembre 2024, les pondérations Kokoro v0.19 ont été publiées de manière permissive en pleine précision fp32 sous une licence Apache 2.0. Au 2 janvier 2025, 10 packs de voix uniques ont été publiés et une version .onnx de v0.19 est disponible.

Dans les semaines précédant sa sortie, Kokoro v0.19 était le modèle classé n°1🥇 dans l'arène TTS Spaces. Kokoro avait atteint un Elo plus élevé dans ce cadre d'arène à voix unique par rapport aux autres modèles, en utilisant moins de paramètres et moins de données :

Kokoro v0.19 : 82 millions de paramètres, Apache, formé sur < 100 heures d'audio
XTTS v2 : 467 millions, CPML, > 10 000 heures
Edge TTS : Microsoft, propriétaire
MetaVoice : 1,2 milliard, Apache, 100 000 heures
Parler Mini : 880 millions, Apache, 45 000 heures
Fish Speech : environ 500 millions, CC-BY-NC-SA, 1 million d'heures
La capacité de Kokoro à atteindre le sommet de cette échelle Elo suggère que la loi d'échelle (Elo vs calcul/données/paramètres) pour les modèles TTS traditionnels pourrait avoir une pente plus raide que prévu.

Vous pouvez trouver une démo hébergée sur https://hf.co/spaces/hexgrad/Kokoro-TTS.
