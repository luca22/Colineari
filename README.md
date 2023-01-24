# Colineari

Creare i file geometria.h e geometria.c che consentano di utilizzare la seguente struttura:


struct punto {
    double x, y;
};


e la funzione:


extern int colineari(struct punto p1, struct punto p2, struct punto p3);


La funzione ritorna 1 se p1, p2 e p3 giacciono sulla stessa retta, altrimenti 0.
