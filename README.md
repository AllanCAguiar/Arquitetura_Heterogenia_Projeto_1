# Arquiteturas Heterog�neas - Turma 23/01
# Programacao em Parallel  - Turma 23/01

## PROJECTO : IMPACT & PAVIC LAB 2023
##      IMPACTLAB LAB 2023
##      PAVIC LAB LAB 2023
###            PROJECTO: GUI - IMAGE PROCESSING

Projeto Tarefas:
- Tarefa 1 - Criar grupos de 3 a 5
- Tarefa 2 - instala��o Visual Studio
- Tarefa 3 - Criar reposit�rio Github(individual)
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

Quando falamos sobre o desempenho entre diferentes bibliotecas ou classes de processamento de imagem, isso geralmente depende de como essas bibliotecas manipulam os dados da imagem e as opera��es que realizamos nelas. Vamos detalhar a compara��o de desempenho entre `stbi` (uma biblioteca C popular para carregar imagens) e a classe `Bitmap` em C++/CLI com base em v�rios crit�rios:

### 1. Gerenciamento de Mem�ria

#### stbi
- **Efici�ncia de Mem�ria**: Tipicamente mais eficiente em termos de mem�ria, pois � uma biblioteca C e permite um controle mais refinado sobre o uso da mem�ria.
- **Gerenciamento Manual**: Requer gerenciamento manual da mem�ria, o que pode ser mais perform�tico, mas tamb�m mais propenso a erros (como vazamentos de mem�ria) se n�o for manuseado com cuidado.

#### Classe Bitmap
- **Coleta de Lixo**: Como parte do framework .NET, utiliza a coleta de lixo para o gerenciamento de mem�ria, o que pode adicionar sobrecarga em compara��o com o gerenciamento manual de mem�ria.
- **Facilidade de Uso**: Mais f�cil de usar e menos propenso a erros de gerenciamento de mem�ria em compara��o com o gerenciamento manual de mem�ria.

### 2. Velocidade das Opera��es

#### stbi
- **Velocidade Nativa**: Como uma biblioteca C, geralmente pode oferecer desempenho mais r�pido para opera��es de imagem porque opera mais pr�ximo do hardware.
- **Otimiza��es**: Pode ser combinada com outras bibliotecas C ou montagem inline para otimiza��es, potencialmente oferecendo um desempenho muito alto.

#### Classe Bitmap
- **C�digo Gerenciado**: Como uma classe gerenciada no framework .NET, pode ter alguma sobrecarga adicional em compara��o com o c�digo C nativo, o que pode potencialmente torn�-la mais lenta.
- **Facilidade de Implementa��o**: Oferece implementa��o mais f�cil e r�pida para v�rias opera��es, o que pode acelerar o tempo de desenvolvimento.

### 3. Flexibilidade e Funcionalidades

#### stbi
- **Flexibilidade**: Permite maior flexibilidade e personaliza��o para opera��es de imagem.
- **Integra��o com Outras Bibliotecas C**: Pode ser facilmente integrado com outras bibliotecas C para recursos adicionais e otimiza��es.

#### Classe Bitmap
- **Conjunto Rico de Funcionalidades**: Oferece um conjunto rico de funcionalidades para o processamento de imagens como parte do framework .NET, facilitando a implementa��o de opera��es complexas sem a necessidade de integrar bibliotecas adicionais.
- **Integra��o com .NET**: Pode ser facilmente integrado com outras classes e funcionalidades no framework .NET para construir aplica��es abrangentes.

### 4. Comunidade e Suporte

#### stbi
- **Comunidade**: Tem uma grande comunidade e tem sido usado em muitos projetos, o que pode ser uma fonte de suporte e exemplos.
- **Documenta��o**: Bem documentado, com muitos recursos dispon�veis para aprendizagem e resolu��o de problemas.

#### Classe Bitmap
- **Comunidade**: Tamb�m tem uma grande comunidade como parte da comunidade de desenvolvedores .NET, que pode ser uma fonte de suporte e exemplos.
- **Documenta��o**: Bem documentado como parte do framework .NET, com muitos recursos dispon�veis para aprendizagem e resolu��o de problemas.

### Conclus�o

A melhor escolha entre `stbi` e a classe `Bitmap` dependeria das suas necessidades espec�ficas, da complexidade do seu projeto e da sua familiaridade com a programa��o em C ou .NET. Se voc� est� procurando por desempenho bruto e est� confort�vel com a programa��o em C, `stbi` pode ser a melhor escolha. Se voc� est� procurando por uma implementa��o mais f�cil e integra��o com outras funcionalidades .NET, a classe `Bitmap` pode ser a melhor escolha.

 Tamb�m pode ser interessante realizar alguns benchmarks com sua carga de trabalho espec�fica para ver qual oferece um melhor desempenho.

