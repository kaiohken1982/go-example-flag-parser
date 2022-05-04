## Esempi GO

Contiene esempi con flag parser

-s indica quale separatore usare
-n se usato, indica di omettere il carattere newline

# Utilizzo

go run . -s / uno due // uno/due ( si newline )

go run . -s / -n uno due // uno/due ( no newline )

go run . -n uno due // uno due ( no newline )
