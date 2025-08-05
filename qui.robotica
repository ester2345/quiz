quiz = [
    {
        "pergunta": "1. Quem é considerado o 'pai da robótica' devido às suas três leis famosas?",
        "opcoes": [
            "a) Nikola Tesla",
            "b) Isaac Asimov",
            "c) Alan Turing",
            "d) Leonardo da Vinci"
        ],
        "resposta": "b",
        "explicacao": "Isaac Asimov foi um escritor de ficção científica que criou as famosas Três Leis da Robótica."
    },
    {
        "pergunta": "2. Qual foi o primeiro robô industrial utilizado comercialmente?",
        "opcoes": [
            "a) Unimate",
            "b) ASIMO",
            "c) Atlas",
            "d) Robby"
        ],
        "resposta": "a",
        "explicacao": "Unimate foi o primeiro robô industrial, usado em uma linha de montagem da General Motors em 1961."
    },
    {
        "pergunta": "3. De onde vem a palavra 'robô'?",
        "opcoes": [
            "a) Do grego antigo",
            "b) Do latim",
            "c) Do tcheco",
            "d) Do francês"
        ],
        "resposta": "c",
        "explicacao": "A palavra 'robô' vem do termo tcheco 'robota', que significa 'trabalho forçado' ou 'trabalho escravo'."
    },
    {
        "pergunta": "4. Qual destes robôs ficou famoso por explorar Marte?",
        "opcoes": [
            "a) Sophia",
            "b) Curiosity",
            "c) Pepper",
            "d) Wall-E"
        ],
        "resposta": "b",
        "explicacao": "Curiosity é um robô rover da NASA, famoso por explorar a superfície de Marte desde 2012."
    },
    {
        "pergunta": "5. Em que ano foi criado o termo 'robótica'?",
        "opcoes": [
            "a) 1921",
            "b) 1954",
            "c) 1942",
            "d) 1969"
        ],
        "resposta": "c",
        "explicacao": "O termo 'robótica' foi usado pela primeira vez por Isaac Asimov em 1942 em seu conto 'Runaround'."
    }
]

score = 0

for q in quiz:
    print(q["pergunta"])
    for opcao in q["opcoes"]:
        print(opcao)
    resposta_usuario = input("Digite a letra da resposta correta: ").lower()
    if resposta_usuario == q["resposta"]:
        print("Correto!")
        score += 1
    else:
        print("Incorreto!")
    print("Explicação:", q["explicacao"])
    print("-" * 40)

print(f"Você acertou {score} de {len(quiz)} perguntas.")