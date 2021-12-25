-Début du projet 22/12
-1er soucis rencontré (22/12): séparer les caractères: lettres, nombres et ponctuations 
(résolu le 22/12): utilisation des string.ascii_letters string.digits string.punctuation (trouvé dans la bibliothèque d'utilisation du module string)

-2e soucis rencontré (23/12): permettre à l'utilisateur de choisir les types de caractères qu'il veut dans son mdp ainsi que la longeur de celui ci
(résolu le 23/12):utilisation d'inputs et de eval (eval nous permet d’exécuter des chaînes de caractères en tant que instruction Python) 

-3e soucis rencontré (24/12): création du mot de passe en lui même, ajouter les caractères pour former le mdp et le faire de manière aléatoire 
(résolu le 24/12): si l'utlisateur à choisi d'avoir un certain type de caractère dans son mot de passe le code prend l'ensemble des caractères de cette catégorie 
pour les ajouter en option au mot de passe, viens ensuite l'utilisation du module random avec random.choices (Renvoie une liste de taille k d'éléments choisis 
de manière aléatoire) sachant que k représente la longeur choisi par l'utilisateur au début du code. Le mot de passe est donc générer.

-4e soucis rencontré (24/12) empecher l'utilisateur de ne pas suivre les instructions donnés pour limiter les erreurs
(résolu le 24/12): utilisation de except pour empecher certaines manipulations et de try pour permettre la sortie du code (avec break)


sources utilisés: bibliothèques des modules string et random
