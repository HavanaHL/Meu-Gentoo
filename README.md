# Meu-Gentoo
Uma documentação simples e didática para o uso do sistema operacional Gentoo Linux.
----
<details>
<summary><strong>Índice</strong></summary>

- [Início](#início)
- [Ponto de partida](#ponto-de-partida)
    - [Por onde começar](#por-onde-começar)
- [O Portage](#o-portage)
    - [O comando emerge](#emerge)

</details>

## Início 
* Esta documentação serve de guia tanto para a instalação quanto para o uso diário do Gentoo.
* A [documentação oficial (Wiki)](https://wiki.gentoo.org/wiki/Main_Page) é sempre a sua maior aliada.
* Este guia está em constante evolução e sujeito a alterações.
* Qualquer sugestão é muito bem-vinda.

## Ponto de partida
* **O Gentoo não é difícil, ele é detalhado.** A chave para o sucesso é a paciência e a leitura. Leia sempre atentamente. Se não entender algo, pesquise. O Gentoo segue a filosofia **D**o **I**t **Y**ourself (Faça Você Mesmo). Você está no controle; aprenda a lidar com seus poderes.
* A Wiki pode parecer assustadora à primeira vista: extensa, gigante e técnica. Mas, lendo com calma, você entende que não é sobre dificuldade, é sobre **explicação**. Se você tem tanto poder sobre a distro, precisa aprender como manusear tudo. A Wiki é completa, direta e explicativa. O manual (handbook) é muito [bem estruturado.](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Installation#How_the_installation_is_structured)

### Por onde começar
* [Entendendo a instalação](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Installation#Introduction) - *Conceitos iniciais.*
* [Download da ISO](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Installation#Gentoo_Linux_installation_media) - *Adquirindo a mídia correta.*
* [Instalando o Gentoo](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Installation#Booting) - *O processo de boot e instalação.*
* [Rede e Netifrc](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Networking) ou [Network Manager](https://wiki.gentoo.org/wiki/NetworkManager) - *Configurando a internet.*
* [Sujando as mãos](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Working) - *Começando a usar o Gentoo.*
* [Dominando o Portage](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Portage) - *Entendendo o package manager.*

## O Portage 
* O *Portage* é o gerenciador de pacotes do Gentoo, ou melhor, o seu coração. Ele vai além de ser apenas o equivalente ao *Apt* (Debian), *Pacman* (Arch) ou *Dnf* (Fedora). Ele é a base total do sistema; é correto dizer que *"O Gentoo Linux é uma distro baseada no **Portage.**"* É com ele que você baixa seus pacotes e, principalmente, gerencia seu sistema.
* Tratando-se de Gentoo, prepare-se para aprender uma lógica diferente. Ao contrário dos outros gerenciadores, que apenas entregam pacotes prontos, o Portage permite que você defina **como** quer seus programas.
* Vamos lidar bastante com arquivos de texto. Pense nisso como escrever "leis" ou "contratos" para o sistema: você define as regras, e o Portage as obedece rigorosamente.

### Emerge
* O `emerge` é o comando que usamos para interagir com o Portage. Ele é a interface de linha de comando.
* Pense assim: O **Portage** é o cérebro (o sistema de gerenciamento) e o **emerge** é a mão (a ferramenta que executa a ação).
* O nome não é por acaso: ele "emerge" (traz à tona) o programa a partir do código-fonte, compilando e instalando tudo pronto para o seu uso.

> [!TIP]
> **Um tranquilizante para você:** Compilar no Gentoo é simples, é rotina.
> É muito diferente de compilar manualmente (o clássico `make && make install`).
> Aqui, o Portage cuida de todas as dependências e erros para você. Sente-se e aguarde.