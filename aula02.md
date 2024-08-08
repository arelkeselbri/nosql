# NoSQL - Aula 02

## Playground
https://mongoplayground.net/

## Cheat sheet
https://www.mongodb.com/developer/products/mongodb/cheat-sheet/


## Base de exemplo:

[
        {
            "id": 1,
            "nome": "Curso de Programação",
            "modulos": [
                {
                    "id": 1,
                    "nome": "Introdução",
                    "aulas": [
                        {
                            "id": 1,
                            "nome": "Aula 1",
                            "materiais": [
                                {"id": 1, "nome": "Slides de Aula 1", "tipo": "PDF"}
                            ]
                        }
                    ]
                },
                {
                    "id": 2,
                    "nome": "Fundamentos de Java",
                    "aulas": [
                        {
                            "id": 2,
                            "nome": "Aula 2",
                            "materiais": [
                                {"id": 2, "nome": "Código de Exemplo", "tipo": "Código"}
                            ]
                        }
                    ]
                }
            ]
        },
        {
            "id": 2,
            "nome": "Curso de Design",
            "modulos": [
                {
                    "id": 3,
                    "nome": "Design Gráfico",
                    "aulas": [
                        {
                            "id": 3,
                            "nome": "Aula 3",
                            "materiais": [
                                {"id": 3, "nome": "Vídeo da Aula 3", "tipo": "Vídeo"}
                            ]
                        }
                    ]
                }
            ]
        }
    ]
