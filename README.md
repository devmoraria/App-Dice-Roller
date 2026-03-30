🎲 Dice Roller: 
Bem-vindo ao Dice Roller, a aplicação que prova que, se a vida te der limões, podes ignorá-los e lançar dados virtuais. 
Este projeto foi criado para explorar o Jetpack Compose e entender o Android.

🚀 O que esta app faz?
Gera números aleatórios: De 1 a 6.

Interface Reativa: O ecrã atualiza-se magicamente o mutableStateOf.

Design Minimalista: Focamos no que importa: o dado e o botão de "desespero" (Roll).

🛠️ Tecnologias Usadas
Kotlin: A linguagem que nos faz felizes.

Jetpack Compose: Porque desenhar interfaces com XML é coisa do século passado.

Material 3: Para deixar tudo com aquele aspeto moderno e limpo.

🧠 O que aprendi (The Nerd)
O coração do app é o conceito de State Recomposition. Usei o remember { mutableStateOf(1) } para garantir que o Android não se esqueça de qual foi o último número sorteado. Se não fosse isso, o dado seria apenas uma imagem estática e triste.
