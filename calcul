def estimer_E (P, L, fleche, b, h) :
    """ Estime le module d'Young E d'une poutre en flexion simple
        P : charge appliquée (N)
        L : portée entre appuis (m)
        flèche : flèche maximale (m)
        b : largeur de la section rectangulaire (m)
        h : hauteur de la section rectangulaire (m)
        E : module d'Young estimé (Pa)
    """
    I = (b * h**3) / 3  # Moment d'inertie pour une section rectangulaire
    E = (P * L**3) / (48 * I * fleche)
    return E


def fleche_max (P, L, E, b, h) :
    """ Calcule la flèche maximale d'une poutre en flexion simple
        P : charge appliquée (N)
        L : portée entre appuis (m)
        E : module d'Young (Pa)
        b : largeur de la section rectangulaire (m)
        h : hauteur de la section rectangulaire (m)
        flèche : flèche maximale (m)
    """
    I = (b * h**3) / 3  # Moment d'inertie pour une section rectangulaire
    fleche = (P * L**3) / (48 * E * I)
    return fleche


