# Arquiteturas Heterogêneas - Turma 23/01
# Programacao em Parallel  - Turma 23/01

## PROJECTO : IMPACT & PAVIC LAB 2023
##      IMPACTLAB LAB 2023
##      PAVIC LAB LAB 2023
###            PROJECTO: GUI - IMAGE PROCESSING

Projeto Tarefas:
- Tarefa 1 - Criar grupos de 3 a 5
- Tarefa 2 - instalação Visual Studio
- Tarefa 3 - Criar repositório Github(individual)
- Tarefa 4 - Criar um GUI
- Tarefa 5 - Processamento de Imagem
- Tarefa 6 - Criar 3 filtros 


LINKS: 
- https://www.youtube.com/watch?v=zv8DkkhBNR0
- https://www.rkaiser.de/c-winforms-tutorial/


IMPACT LAB PROJETO - TURMA 03
- GRUPO : 01: https://github.com/Odalisio-Neto/Impact-Lab-Comp-Het 
- GRUPO : 02: https://github.com/vitskrieg/ArquiteHeterogeneas_ImpactLab_EXERCICIOS.git
- GRUPO : 03: https://github.com/pedrolievra/FilterApply.git
- GRUPO : 04: https://github.com/EugenioAL/Imsof.git
- GRUPO : 05: http://github.com/MehlloLima/Sidoraldo


PAVIC PROJETO - TURMA 01
- GRUPO : 01: https://github.com/PauloCh-PAVIC/PP_Image_Recolor
- GRUPO : 02: https://github.com/mafaldasalomao/app_pp_cuda
- GRUPO : 03: https://github.com/Roberto-RB/Project
- GRUPO : 04: https://github.com/Cleps/PAVIC-modulo1
- GRUPO : 05: https://github.com/AvlisRede/PAVIC-LAB---MODULO-01---PROJETO---TURMA-01
- GRUPO : 06: https://github.com/moisesa1/imagem_projeto

IMPACT LAB PROJETO - TURMA 03 - Example 
https://github.com/AntonioRodriguezUFAM/ImpactLab_Project_02 


"Diferentes bibliotecas ou classes de processamento de imagem"

 -- Classe stbi
 -- Classe Bitmap

---

Quando falamos sobre o desempenho entre diferentes bibliotecas ou classes de processamento de imagem, isso geralmente depende de como essas bibliotecas manipulam os dados da imagem e as operações que realizamos nelas. Vamos detalhar a comparação de desempenho entre `stbi` (uma biblioteca C popular para carregar imagens) e a classe `Bitmap` em C++/CLI com base em vários critérios:

### 1. Gerenciamento de Memória

#### stbi
- **Eficiência de Memória**: Tipicamente mais eficiente em termos de memória, pois é uma biblioteca C e permite um controle mais refinado sobre o uso da memória.
- **Gerenciamento Manual**: Requer gerenciamento manual da memória, o que pode ser mais performático, mas também mais propenso a erros (como vazamentos de memória) se não for manuseado com cuidado.

#### Classe Bitmap
- **Coleta de Lixo**: Como parte do framework .NET, utiliza a coleta de lixo para o gerenciamento de memória, o que pode adicionar sobrecarga em comparação com o gerenciamento manual de memória.
- **Facilidade de Uso**: Mais fácil de usar e menos propenso a erros de gerenciamento de memória em comparação com o gerenciamento manual de memória.

### 2. Velocidade das Operações

#### stbi
- **Velocidade Nativa**: Como uma biblioteca C, geralmente pode oferecer desempenho mais rápido para operações de imagem porque opera mais próximo do hardware.
- **Otimizações**: Pode ser combinada com outras bibliotecas C ou montagem inline para otimizações, potencialmente oferecendo um desempenho muito alto.

#### Classe Bitmap
- **Código Gerenciado**: Como uma classe gerenciada no framework .NET, pode ter alguma sobrecarga adicional em comparação com o código C nativo, o que pode potencialmente torná-la mais lenta.
- **Facilidade de Implementação**: Oferece implementação mais fácil e rápida para várias operações, o que pode acelerar o tempo de desenvolvimento.

### 3. Flexibilidade e Funcionalidades

#### stbi
- **Flexibilidade**: Permite maior flexibilidade e personalização para operações de imagem.
- **Integração com Outras Bibliotecas C**: Pode ser facilmente integrado com outras bibliotecas C para recursos adicionais e otimizações.

#### Classe Bitmap
- **Conjunto Rico de Funcionalidades**: Oferece um conjunto rico de funcionalidades para o processamento de imagens como parte do framework .NET, facilitando a implementação de operações complexas sem a necessidade de integrar bibliotecas adicionais.
- **Integração com .NET**: Pode ser facilmente integrado com outras classes e funcionalidades no framework .NET para construir aplicações abrangentes.

### 4. Comunidade e Suporte

#### stbi
- **Comunidade**: Tem uma grande comunidade e tem sido usado em muitos projetos, o que pode ser uma fonte de suporte e exemplos.
- **Documentação**: Bem documentado, com muitos recursos disponíveis para aprendizagem e resolução de problemas.

#### Classe Bitmap
- **Comunidade**: Também tem uma grande comunidade como parte da comunidade de desenvolvedores .NET, que pode ser uma fonte de suporte e exemplos.
- **Documentação**: Bem documentado como parte do framework .NET, com muitos recursos disponíveis para aprendizagem e resolução de problemas.

### Conclusão

A melhor escolha entre `stbi` e a classe `Bitmap` dependeria das suas necessidades específicas, da complexidade do seu projeto e da sua familiaridade com a programação em C ou .NET. Se você está procurando por desempenho bruto e está confortável com a programação em C, `stbi` pode ser a melhor escolha. Se você está procurando por uma implementação mais fácil e integração com outras funcionalidades .NET, a classe `Bitmap` pode ser a melhor escolha.

 Também pode ser interessante realizar alguns benchmarks com sua carga de trabalho específica para ver qual oferece um melhor desempenho.

### Treinamento Pavic - Turma II 2023
![image info](Treinamento Pavic - Turma II 2023.jpeg)

Inline-style (hover to see title text):
![alt text](img/markdown_logo.png "Title Text")
Reference-style (hover to see title text):
![alt text1][logo]
[logo]: img/markdown_logo.png "Title Text"
