## Resumo ‘Big Ball of Mud’
Artigo escrito por Brian Foote e Joseph Yoder, publicado em 26 de Agosto de 1997

O artigo "Big Ball of Mud" explora como o desenvolvimento de software pode levar a uma arquitetura insustentável, denominada "Big Ball of Mud". O ciclo de vida desse fenômeno passa por várias etapas: código descartável (Throwaway Code), crescimento incremental (Piecemeal Growth), manter o sistema funcionando (Keep it Working), esconder problemas (Sweeping it Under the Rug) e, eventualmente, a necessidade de uma reconstrução do projeto (Reconstruction).

Um sistema pode se tornar uma "Big Ball of Mud" por um grande desencadeamento de fatores. Um exemplo trazido pelo artigo, se dá quando o código projetado para resolver problemas rápidos e temporários, começa a ser modificado e expandido em grande escala e sem uma preocupação com sua arquitetura. Com o tempo, esse sistema cresce descontroladamente (Piecemeal Growth), e, para mantê-lo funcionando, programadores adotam uma mentalidade de "apenas manter funcionando", sem se preocuparem-se com a devida solução do problema, que muitas vezes é mais profundo e custoso do que pode parecer. Em relação a problemas que vão surgindo durante a evolução, usam soluções rápidas para escondê-los ao invés de enfrentá-los propriamente (Sweeping it Under the Rug), até que a única solução viável seja uma reconstrução total do sistema.

Muitos fatores contribuem para a formação dessa bagunça, como os seguintes casos citados no artigo: 

Falta de planejamento;
Complexidade;
Mudanças de requisitos;
Falta de experiência dos desenvolvedores;
Pressão de entrega e/ou prazos apertados;
Priorização das funcionalidades imediatas ao invés da arquitetura;
Custo e orçamento;

Embora o código do tipo "Big Ball of Mud" seja muitas vezes confuso e insustentável, é inegável sua grande presença no meio da tecnologia. Ela surge como uma solução viável para o desafio de entregar um sistema funcional em ambientes de desenvolvimento com pressões de prazo e recursos limitados, cenário muito recorrente em nosso meio.

O artigo conclui que, embora a "Big Ball of Mud" possa parecer uma anti-padrão, ela persiste devido a pressões econômicas e de mercado que priorizam entregas rápidas sobre a elegância arquitetural. No entanto, os autores acreditam que é possível aspirar a sistemas mais duráveis e sustentáveis. A chave para isso é reconhecer as pressões que levam à degradação arquitetural e, com isso, permitir o surgimento de artefatos mais duradouros, que possam ser refinados conforme o sistema amadurece.

