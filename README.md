TurisGraph — Planejador de Rotas Inteligentes

Entrega E3 - MVP

O TurisGraph é um sistema de otimização logística voltado ao setor de turismo,
desenvolvido para calcular rotas de menor custo entre destinos utilizando a Teoria dos
Grafos.

1. Descrição do Projeto
Este projeto simula o planejamento de itinerários, permitindo identificar o caminho
mais curto entre localidades específicas ou planejar roteiros completos com foco em
eficiência de custo e distância.

2. Estrutura do Projeto

TurisGraph/
├── data/
│ └── mapa.json # Dataset com cidades e conexões
├── src/
│ ├── main.py # Interface de linha de comando (CLI)
│ ├── core/ # Domínio: Lógica do Grafo
│ ├── algorithms/ # Algoritmos: Dijkstra
│ └── infra/ # Infraestrutura: Leitura de JSON
├── tests/ # Testes Unitários
├── requirements.txt # Dependências do projeto
└── README.md # Este arquivo

3. Como Executar o MVP
Pré-requisitos
Python 3.x instalado.
Bibliotecas listadas no requirements.txt instaladas.
•
•

Instalação

pip install -r requirements.txt

Execução
Para rodar o planejador de rotas, execute o seguinte comando a partir da raiz do
projeto:

python src/main.py

4. Algoritmos Implementados
Dijkstra: Utilizado para encontrar o caminho mínimo entre dois nós em um grafo
ponderado, garantindo a rota mais eficiente entre duas cidades escolhidas pelo
usuário.

5. Testes Unitários
O projeto conta com testes automatizados para validar a lógica do algoritmo principal,
cobrindo cenários como:
Caso Base (Entrada válida com resultado conhecido).
Grafo Vazio (Tratamento de erro para falta de dados).
Grafo Completo (Validação em conexões densas).

6. Autores
Gustavo Gomes Guimarães (RA: 29078784)
Júlia Moreno da Silva (RA: 39159108)
Thiago de Luca Fernandes (RA: 38767791)
