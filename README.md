# MISSÃO MARKDOWN 🚀
Escrito por: Isaac Iuri Alves de Oliveira - DEV-B

## Objetivo:
- Pesquisar sobre __sistemas operacionais__, com foco especial no __Windows__, e registre suas descobertas em um documento __README.md__ utilizando __Markdown__.
- Desenvolvendo habilidades de formatação e estruturação de documentos técnicos, enquanto aprofunda seus conhecimentos sobre sistemas operacionais.

## Pesquisa:

### O que é um Sistema Operacional:
Sistema Operacional é o ___software___, ele não se resume à interação do usuário ou ao estado gráfico que o usuário enxerga, ele é um programa que conversa com o ___hardware___ da máquina.

Ele funciona como uma interface entre a aplicação e a rotinas dos __dispositivos__ de entrada e saída (E/S), dentro dele existem dois modos: o modo __supervisor__ e o modo __usuário__.

No modo __supervisor__, o acesso ao controle da máquina (_hardware_) é completo, podendo executar qualquer coisa que a máquina possa fazer. No modo __usuário__, ele restringe o acesso apenas a funções já pré-programadas a fazer, como um navegador _web_ ou reprodutor de música, porém é um dos mais usados comumente.

![Modo Supervisor e Modo Usuário](https://www.alura.com.br/artigos/assets/sistemas-operacionais-conceito-estrutura/imagem3.png)

Tem como suas principais funções:

- Funcionar como ponte entre o _hardware_ e usuário;
- Gerenciar recursos em uma tarefa complexa (como a execução de diversos programas – “Gerenciador de Tarefas”);
- E prover serviços e facilidades para execução de programas.

O surgimento do sistema operacional, surgiu justamente para __intermediar__ o diálogo entre a máquina e o desenvolvedor de programas, sem a necessidade em se preocupar com cada componente interno da máquina.

### Evolução dos Sistemas Operacionais:

### Windows

#### Introdução

#### Principais Versões Windows:

##### MS-DOS (1981)

Antes dos sistemas operacionais modernos, computadores antigos funcionavam com sistemas muito rudimentares e primitivos. Junto com a criação do ___MS-DOS___ em __1981__, pela empresa _Microsoft_ de Bill Gates, houve uma grande adoção por este sistema operacional, ele permitia os usuários, por meio de uma linha de comando, interagissem com o computador __digitando comandos__.

Seu design simples, porém eficiente, além da sua grande funcionalidade, trouxe uma série de benefícios para a empresa da Microsoft, dentre elas:

- Colocando o sistema como modelo da indústria e tornando os computadores pessoais mais comuns;
- Ascensão da IBM (_International Business Machines Corporation_) como fabricantes de _PCs_;
- Permissão de um ampla gama de softwares a ser desenvolvida e executada.

##### Windows 3.1 e Windows 95

Outra grande novidade que mudou com a forma que interagimos com os computadores, foi na década de 1990, especificamente em __1992__, no lançamento do ___Windows 3.1___, um avanço significativo, comparando-se com o _MS-DOS_.

Nesse lançamento, foi introduzido a Interface Grádica do Usuário (_GUI_), que facilitava a interação com o sistema através de ícones, menus e janelas.

Após 3 anos do seu lançamento, _Microsoft_ lança Windows 95, trazendo uma interface mais sofisticada, suporte aprimorado e a introdução do ___Menu Iniciar___, o que se tornou um ícone dos sistemas operacionais Windows.

##### Windows XP

No lançamento do ___Windows XP___, lançado em __2001__, conseguiu ser um dos sistemas operacionais mais bem sucedidos da _Microsoft_, combinando estabilidade com uma interface amigável e se tornou extremamente popular e duradouro, sendo amplamente adotado.

##### Windows 7

Em __2009__, o ___Windows 7___ trouxe uma interface mais refinada, melhor desempenho e uma série de recursos novos, como o _Snap_ e a Biblioteca, que facilitavam a organização e o acesso aos arquivos.

##### Windows 8 e Windows 10 (2012 e 2015)

Em __2012__, no ___Windows 8___, se marca uma mudança radical em relação a interfacer _Modern UI_, voltada para dispositivos _TouchScreen_. Apesar de inovações como a ___Loja Windows___ e integração da ___Windows Store___. Usuários _Windows_ da época ficaram insatisfeitos com essa mudança.

E para corrigir essa bobeira, jogaram no mercado o ___Windows 10___ em 2015, o sistema trouxe de volta o _Menu Iniciar_ e integrou o melhor dos dois mundos: interface amigável e _touchscreen_. Além de um conceito de "_Windows_ como um Serviço", passando a ter __atualizações contínuas__, focando 100% na experiência do usuário.

##### Windows 11 (2021)

O ___Windows 11___, lançado em __2021__, representa a próxima fase na evolução dos sistemas operacionais da Microsoft. Com uma interface mais moderna, novas funcionalidades e melhorias na segurança, o _Windows 11_ busca oferecer uma experiência mais fluida e integrada. Ele introduziu uma nova barra de tarefas centralizada, widgets e melhorias no suporte a múltiplos monitores e virtualização.

#### Arquitetura Windows:

##### Modo Usuário (User Mode):

Essa parte é onde os programas comuns (aplicativos, navegadores, editores de texto) rodam. Aqui, os processos têm acesso restrito ao _hardware_ para evitar falhas graves no sistema.

##### Modo Kernel ou Modo Núcleo (Kernel Mode ou Core Mode):

O ___Kernel/Núcleo___ é o coração do sistema operacional e tem acesso total ao _hardware_. Ele gerencia processos, memória, _drivers_ e segurança.

##### Componentes Importantes:

- _NT Kernel_ (_Windows NT_) – A base do _Windows_ moderno, usada desde o _Windows 2000_, que traz mais segurança e estabilidade.
- _Registry_ (Registro do _Windows_) – Banco de dados onde o _Windows_ guarda configurações do sistema e de programas.
- Sistema de Arquivos _NTFS_ – O principal sistema de arquivos do _Windows_, conhecido por sua segurança e suporte a grandes volumes de dados.
- Gerenciador de Processos (_Task Manager_) – Ferramenta usada para monitorar e controlar os programas e serviços em execução.

#### Comandos Windows:

##### 10 comandos Windows:

1. `ipconfig` --> Mostra informações da rede, como _IP_, máscara de sub-rede e gateway padrão.
2. `ping` --> Testa a conectividade com um site ou outro dispositivo na rede.
3. `tasklist` --> Exibe todos os processos em execução no sistema.
4. `taskkill` --> Finaliza um processo em execução.
5. `shutdown` --> Desliga ou reinicia o computador.
6. `chkdsk` --> Verifica e corrige erros no disco rígido.
7. `sfc` --> Verifica e repara arquivos do sistema corrompidos.
8. `netstat` --> Mostra conexões ativas e portas abertas no computador.
9. `wmic` --> Exibe informações do sistema de forma avançada.
10. `regedit` --> Abre o Editor de Registro do _Windows_.


### Biblioteca README.md:

`usado para mostrar código`
```
nome = str('usado para mostrar blocos de código')
print(nome)
```

``` Tabela
| Nome  | Idade | Profissão  |
|-------|------|------------|
| Ana   | 25   | Engenheira |
| João  | 30   | Professor  |
```

``` Agenda
- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Outra tarefa pendente
```

>Citação 1
>>Citação 2

___

## Curiosidades:

## Fontes:
- [Tutorial README.md - Drive](https://drive.google.com/file/d/1M9UfWY8D3gFnGc_wqWd0dV5GLvIVlnKP/view?usp=classroom_web&authuser=0)
- [Sistemas Operacionais: Conceito e Estrutura - Alura](https://www.alura.com.br/artigos/sistemas-operacionais-conceito-estrutura/)
