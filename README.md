# Project Euler in 05ab1e

## 1

    999Lʒ35SÖZ}O

    999L         - 1..999
        ʒ        - filter
         35S     - push 3,5
            Ö    - divisible?
             Z   - max (i.e. will be 1 if at least one true)
              }  - close filter
               O - sum

## 2

    4000000ÅFʒÈ}O

## 3

    600851475143ÒZ

## 4

    999LnʒDRQ}θ

    999L        - range 1 to 999
        n       - square
         ʒDRQ}  - filter when the Reverse is eQual
              θ - last element 
