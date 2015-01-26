****************
intégrer du code python
****************

J'écris un petit texte avec du **gras** et de l'*italique*
Voici une liste à puce hierarchisée:

   *  item1
   *  item 2
   *  item 3
      *  sous-item 1
      *  sous-item 2
      *  etc..
 
 
 
 intégrer fich ext
****************     
..  litteralinclude:: scripts/conversion.py
    :language: python
    :emphasise-lines: 3,5,6
      
      
intégrer du code python
****************

Voici la fonction qui calcule la factorielle de :math:'n' :
::
    def factorielle (n):
        if n==0:
            return 1
        return n * factorielle(n-1)
        
..  figure:: figures/dirt.jpg
    :width: 80%
