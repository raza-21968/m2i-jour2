# m2i-jour2

\\ Pseudo-code affichant la moyenne de valeurs lues
DÉBUT
    \\ Lire le nombre de valeurs à traiter
    RÉPÉTER
        REQUÊTE "Combien de valeurs à traiter?", Nb
    JUSQU'À Nb >= 0

    \\ Y a-t-il un traitement à faire?
    SI Nb > 0 ALORS
        \\ Lire les valeurs et en calculer la somme
        Somme = 0
        POUR I = 1 JUSQU'À Nb FAIRE
            REQUÊTE "Entrez une valeur? ", Valeur
            Somme = Somme + Valeur
        FINPOUR

        \\ Afficher la moyenne des valeurs lues
        ÉCRIRE "Moyenne =", Somme / Nb
    SINON
        ÉCRIRE "Aucune valeur à traiter"
    FINSI
FIN