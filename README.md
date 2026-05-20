# O meu percurso em Cibersegurança

## Introdução

A conclusão da formação Jovem + Digital em Cibersegurança, de nível 5 e com a duração de 300 horas, constituiu o ponto de partida para a construção deste portefólio. A sua criação surge da necessidade de organizar, sistematizar e documentar o conhecimento adquirido ao longo da formação, bem como de reunir evidências práticas que permitam demonstrar a evolução do meu percurso na área da cibersegurança.

A escolha desta formação resultou do meu interesse pela área tecnológica e da vontade de compreender, de forma mais aprofundada, o funcionamento dos sistemas informáticos, das redes de comunicação, das vulnerabilidades que lhes podem estar associadas e dos mecanismos utilizados para proteger a informação. Ao longo do percurso formativo, tive contacto com diferentes domínios da cibersegurança, desde os fundamentos de redes e sistemas, legislação, segurança e privacidade, até à análise de vulnerabilidades, programação aplicada à cibersegurança, evidências digitais, monitorização, deteção de intrusões e resposta a incidentes.

Este portefólio pretende, assim, assumir-se como um instrumento de organização, reflexão e consolidação do conhecimento. Não se limita à apresentação dos conteúdos abordados durante a formação, procurando também funcionar como uma base de estudo contínuo, onde possa rever conceitos, consultar procedimentos, reorganizar apontamentos, aprofundar matérias e consolidar competências sempre que necessário.

Neste sentido, o repositório será desenvolvido de forma progressiva, acompanhando não apenas os conteúdos trabalhados na formação Jovem + Digital em Cibersegurança, mas também aprendizagens futuras resultantes de outras formações, estudo autónomo, exercícios práticos e projetos que venha a desenvolver. A sua finalidade é, por isso, dupla: por um lado, demonstrar as competências adquiridas e desenvolvidas; por outro, constituir uma base de consulta pessoal e técnica para apoio ao meu crescimento contínuo na área.

A estrutura deste portefólio será construída de forma gradual, procurando documentar cada etapa com rigor, clareza e sentido crítico. Serão incluídos apontamentos, exercícios, comandos utilizados, análises, relatórios, evidências práticas e reflexões sobre os temas abordados, de modo a representar não apenas o resultado final da aprendizagem, mas também o processo através do qual esse conhecimento foi adquirido, revisto e consolidado.

Quero ainda expressar o meu agradecimento aos formadores e à coordenadora da formação, pelo acompanhamento, disponibilidade e partilha de conhecimento ao longo deste percurso. O contributo prestado foi fundamental para a compreensão dos conteúdos, para a sua aplicação prática e para o desenvolvimento de uma visão mais estruturada sobre a cibersegurança enquanto área técnica, ética e em constante evolução.

---

# Fundamentos de Cibersegurança

## O que é a Cibersegurança

A cibersegurança pode ser entendida como o conjunto de práticas, medidas, procedimentos e tecnologias utilizados para proteger sistemas informáticos, redes, dispositivos, aplicações e dados contra ameaças existentes no meio digital.

O termo resulta da associação entre duas ideias. Por um lado, **“ciber”**, relacionado com a Internet, as redes de computadores, os sistemas digitais e o espaço onde ocorre a comunicação eletrónica. Por outro, **“segurança”**, associada à proteção, prevenção, controlo e redução de riscos.

De forma simples, a cibersegurança procura impedir que informação, sistemas ou serviços sejam acedidos, alterados, destruídos, roubados ou interrompidos por pessoas ou entidades não autorizadas.

Embora seja frequentemente associada a ferramentas técnicas, como antivírus, firewalls ou sistemas de deteção de intrusões, a cibersegurança não se resume à instalação de programas de proteção. Envolve também comportamentos seguros, gestão de acessos, atualização de sistemas, cópias de segurança, proteção física dos equipamentos, monitorização e capacidade de resposta perante incidentes.

Trata-se, por isso, de uma área técnica, organizacional e humana. Muitos incidentes não resultam apenas de falhas tecnológicas, mas também de erros de configuração, falta de atualização, utilização de palavras-passe fracas, abertura de ficheiros maliciosos ou exposição indevida de serviços à Internet.

> **Nota:**  
> Um **sistema informático** pode ser um computador, servidor, telemóvel, aplicação ou conjunto de componentes que processa informação.  
> Uma **rede** é um conjunto de equipamentos ligados entre si para permitir comunicação e troca de dados.  
> Um **serviço** é uma funcionalidade disponibilizada por um sistema, como um site, email, partilha de ficheiros ou acesso remoto.

---

## Importância da Cibersegurança

A utilização de tecnologia está presente em praticamente todos os contextos da vida pessoal, profissional e institucional. Contas de email, serviços bancários, redes sociais, plataformas de trabalho, bases de dados, aplicações web e dispositivos móveis dependem de sistemas digitais e de redes de comunicação.

Quando estes sistemas não se encontram devidamente protegidos, podem surgir consequências graves, tais como:

- acesso indevido a contas;
- roubo de informação pessoal ou profissional;
- perda, alteração ou destruição de dados;
- interrupção de serviços;
- fraude;
- roubo de identidade;
- prejuízos financeiros;
- danos na reputação de pessoas ou organizações.

A cibersegurança é importante porque permite reduzir estes riscos. A segurança absoluta não existe, mas é possível diminuir a probabilidade de ocorrência de incidentes e limitar o seu impacto através de medidas adequadas.

A proteção digital deve, por isso, ser vista como um processo contínuo. Não basta configurar uma ferramenta uma única vez. É necessário manter sistemas atualizados, rever práticas, acompanhar novas ameaças e adaptar os mecanismos de proteção sempre que necessário.

> **Nota:**  
> Um **incidente de segurança** é qualquer acontecimento que possa comprometer a informação, os sistemas ou os serviços.  
> Exemplos: uma conta comprometida, um ficheiro apagado sem autorização, malware instalado, acesso indevido ou indisponibilidade de um serviço.

---

## Medidas básicas de Cibersegurança

Antes de avançar para ferramentas mais complexas, é essencial compreender que a segurança começa por medidas básicas, consistentes e aplicadas de forma regular.

Muitos incidentes não têm origem em ataques tecnicamente sofisticados, mas sim em falhas simples, como:

- utilização de palavras-passe fracas;
- reutilização da mesma palavra-passe em vários serviços;
- sistemas desatualizados;
- abertura de anexos suspeitos;
- cliques em links fraudulentos;
- ausência de cópias de segurança;
- utilização insegura de redes Wi-Fi públicas;
- dispositivos deixados desbloqueados.

Estas situações mostram que a cibersegurança começa também nos hábitos do utilizador. Pequenas decisões do dia a dia podem aumentar ou reduzir significativamente o risco.

Entre as principais medidas básicas encontram-se:

- utilizar palavras-passe fortes e diferentes para cada serviço importante;
- ativar autenticação de dois fatores sempre que possível;
- manter sistemas, aplicações e navegadores atualizados;
- utilizar antivírus ou antimalware;
- ter cuidado com emails, links e ficheiros;
- confirmar a segurança dos sites visitados;
- evitar operações sensíveis em redes públicas;
- realizar cópias de segurança regularmente;
- proteger fisicamente os dispositivos;
- manter uma atitude de atenção e aprendizagem contínua.

> **Nota:**  
> Uma **camada de proteção** é uma medida que ajuda a reduzir o risco.  
> Por exemplo, uma palavra-passe forte é uma camada; a autenticação de dois fatores é outra; uma cópia de segurança é outra.

---

## Palavras-passe e contas

As palavras-passe continuam a ser uma das formas mais comuns de proteger o acesso a contas, sistemas e serviços digitais.

Uma palavra-passe segura deve ser longa, única e difícil de adivinhar. Deve evitar elementos previsíveis, como nomes próprios, datas de nascimento, números simples, sequências conhecidas ou palavras demasiado óbvias.

Também é importante não reutilizar a mesma palavra-passe em vários serviços. Quando a mesma palavra-passe é usada em diferentes contas, a exposição de uma delas pode colocar em risco todas as restantes.

As contas mais importantes, como email, banca, redes sociais, serviços profissionais e plataformas de trabalho, devem ter palavras-passe únicas e particularmente robustas.

Uma boa prática é utilizar um gestor de palavras-passe. Este tipo de ferramenta permite guardar credenciais de forma organizada e ajuda a criar palavras-passe fortes, reduzindo a necessidade de memorizar todas manualmente.

Sempre que possível, deve ser ativada a autenticação de dois fatores. Esta medida acrescenta uma segunda confirmação ao processo de acesso, dificultando a entrada de terceiros mesmo que a palavra-passe seja descoberta.

Também se deve evitar o envio de palavras-passe por email, SMS ou mensagens de chat, sobretudo quando o pedido é inesperado ou não foi devidamente confirmado.

> **Nota:**  
> **Credenciais** são os dados usados para aceder a um sistema, normalmente nome de utilizador e palavra-passe.  
> **2FA** significa autenticação de dois fatores. Além da palavra-passe, é necessário confirmar a identidade através de outro meio, como uma aplicação no telemóvel, um código temporário ou uma chave física.

---

## Atualizações, antivírus e antimalware

Manter os sistemas atualizados é uma das medidas mais importantes para reduzir riscos de segurança.

As atualizações não servem apenas para melhorar o funcionamento dos programas ou acrescentar novas funcionalidades. Muitas vezes corrigem falhas de segurança já conhecidas, que poderiam ser exploradas por atacantes caso o sistema permanecesse desatualizado.

Por esse motivo, sistemas operativos, aplicações, navegadores e dispositivos móveis devem ser mantidos atualizados, preferencialmente com atualizações automáticas ativadas.

A utilização de antivírus ou antimalware também é importante, pois acrescenta uma camada adicional de proteção contra programas maliciosos. Estas ferramentas podem ajudar a detetar, bloquear ou remover ameaças.

No entanto, o antivírus não deve ser entendido como uma solução completa. Mesmo com uma ferramenta de proteção ativa, continua a ser necessário ter cuidado com ficheiros descarregados, links suspeitos, sites desconhecidos e aplicações de origem duvidosa.

> **Nota:**  
> **Malware** é software malicioso, criado para causar danos, roubar informação, espiar atividade ou obter acesso indevido a um sistema.  
> **Antimalware** é uma ferramenta destinada a detetar, bloquear ou remover malware.  
> **Browser** é o navegador usado para aceder à Internet, como Chrome, Firefox, Edge ou Safari.

---

## Emails, links e ficheiros

O email é um dos meios mais utilizados em ataques informáticos, especialmente através de mensagens falsas, links fraudulentos e anexos maliciosos.

Muitos ataques procuram enganar o utilizador em vez de explorar diretamente uma falha técnica. Para isso, recorrem a mensagens que criam urgência, prometem prémios, simulam faturas, imitam empresas conhecidas ou solicitam dados pessoais e credenciais.

Antes de clicar num link, deve verificar-se o endereço real da página. Um link pode parecer legítimo no texto da mensagem, mas encaminhar para outro site. Pequenas alterações no domínio também podem indicar fraude.

Os anexos devem ser tratados com especial cuidado, principalmente quando são inesperados, vêm de remetentes desconhecidos ou apresentam um conteúdo fora do contexto habitual.

Nunca devem ser enviados códigos de autenticação, palavras-passe ou dados sensíveis por email, SMS ou mensagens de chat quando o pedido é inesperado ou não foi confirmado por outro meio.

> **Nota:**  
> **Phishing** é uma técnica de fraude em que o atacante tenta enganar a vítima para obter dados, como palavras-passe, códigos de autenticação ou dados bancários.  
> Um **link** é uma ligação para uma página ou recurso online.  
> Um **anexo malicioso** é um ficheiro enviado com a intenção de instalar malware ou executar uma ação prejudicial.

---

## Redes e navegação segura

A navegação na Internet também exige cuidados de segurança.

Sempre que se acede a sites sensíveis, como banca online, email, serviços profissionais ou plataformas que tratam dados pessoais, deve confirmar-se se o endereço utiliza HTTPS. Normalmente, esta ligação é identificada pelo cadeado apresentado no navegador.

O HTTPS permite que a comunicação entre o utilizador e o site seja protegida através de encriptação. Isto reduz o risco de terceiros conseguirem ler a informação durante a transmissão.

No entanto, o cadeado não significa automaticamente que o site é legítimo. Um site fraudulento também pode utilizar HTTPS. Por isso, além de verificar o cadeado, é necessário confirmar se o endereço do site está correto.

As redes Wi-Fi públicas, como as de cafés, hotéis, centros comerciais ou transportes, podem apresentar riscos acrescidos. Sempre que possível, deve evitar-se o acesso a serviços sensíveis através destas redes.

Quando for necessário utilizar uma rede pública, a utilização de uma VPN pode acrescentar uma camada de proteção, criando uma ligação mais segura entre o dispositivo e a Internet.

> **Nota:**  
> **HTTPS** é a versão segura do HTTP e permite proteger a comunicação entre o navegador e o site.  
> **Encriptação** é o processo de transformar informação num formato ilegível para quem não tem autorização para a ler.  
> **VPN** significa Rede Privada Virtual. É uma tecnologia que cria uma ligação protegida através de uma rede pública.

---

## SSL, HTTPS e certificados digitais

A proteção da comunicação entre utilizadores e sites é uma parte importante da cibersegurança.

O HTTPS utiliza certificados digitais para estabelecer ligações seguras entre o navegador e o servidor. Estes certificados ajudam a confirmar a identidade do site e permitem proteger a informação transmitida.

Durante muito tempo, o termo SSL foi utilizado para designar este tipo de proteção. Atualmente, a tecnologia mais utilizada é o TLS, embora a expressão SSL continue a ser usada com frequência de forma geral.

A utilização de HTTPS é especialmente importante em páginas onde são introduzidos dados sensíveis, como palavras-passe, dados pessoais, dados bancários ou informações profissionais.

Num ambiente de estudo ou laboratório, ferramentas como XAMPP, Apache e OpenSSL podem ser utilizadas para compreender melhor como funciona a configuração de um servidor web local e de certificados digitais.

> **Nota:**  
> **Certificado digital** é um ficheiro usado para ajudar a comprovar a identidade de um site e permitir comunicação segura.  
> **Autoridade de Certificação**, ou CA, é uma entidade que emite certificados digitais.  
> **XAMPP** é uma ferramenta que permite criar um ambiente local de desenvolvimento web.  
> **Apache** é um servidor web, ou seja, um programa que disponibiliza páginas ou aplicações através da rede.  
> **OpenSSL** é uma ferramenta usada para trabalhar com certificados e mecanismos de encriptação.

---

## Cópias de segurança

As cópias de segurança são essenciais para recuperar informação em caso de falha, eliminação acidental, perda do equipamento, ataque informático ou ransomware.

Um ransomware pode bloquear ou cifrar ficheiros e exigir um pagamento para permitir a sua recuperação. Se existir uma cópia de segurança recente e protegida, o impacto deste tipo de ataque pode ser reduzido.

As cópias de segurança devem ser realizadas regularmente e guardadas em locais seguros. Sempre que possível, deve existir pelo menos uma cópia offline, ou seja, desligada da Internet e separada do sistema principal.

Também é importante testar periodicamente se as cópias de segurança podem ser recuperadas. Um backup que não pode ser restaurado não cumpre a sua função principal.

As cópias de segurança não impedem um ataque, mas podem ser decisivas para recuperar dados e garantir a continuidade do trabalho.

> **Nota:**  
> **Backup** significa cópia de segurança.  
> **Offline** significa desligado da Internet ou não acessível diretamente pela rede.  
> **Ransomware** é um tipo de malware que bloqueia ou cifra ficheiros e exige um pagamento para permitir a sua recuperação.  
> **Cloud** é um serviço online usado para armazenar ou processar dados através da Internet.

---

## Dispositivos físicos

A proteção física dos dispositivos também faz parte da cibersegurança.

Computadores, telemóveis, discos externos e outros equipamentos podem conter informação sensível ou permitir acesso a contas e sistemas. Por esse motivo, devem estar protegidos com bloqueio de ecrã, PIN, palavra-passe ou biometria.

Não se devem deixar dispositivos desbloqueados e sem vigilância em locais públicos ou em ambientes profissionais. O acesso físico a um equipamento pode permitir consultar ficheiros, copiar dados, alterar configurações ou utilizar contas já autenticadas.

Sempre que disponível, deve ser utilizada encriptação do disco. Esta medida ajuda a proteger os dados armazenados caso o equipamento seja perdido ou roubado.

A segurança física complementa a segurança digital. Mesmo um sistema bem configurado pode ficar vulnerável se o dispositivo estiver acessível e desbloqueado.

> **Nota:**  
> **PIN** é um código numérico usado para desbloquear um dispositivo ou confirmar uma ação.  
> **Biometria** é a utilização de características físicas, como impressão digital ou reconhecimento facial, para autenticação.  
> **Disco rígido** é o componente onde os dados ficam armazenados num computador.

---

## Atenção e formação contínua

A cibersegurança exige atenção permanente, porque as ameaças mudam ao longo do tempo.

Novas formas de fraude digital surgem com frequência. Alguns exemplos incluem phishing, falsos suportes técnicos, burlas bancárias, fraudes associadas a pagamentos digitais, roubo de contas e esquemas relacionados com criptomoedas.

Por isso, a formação contínua é essencial. Quanto maior for a capacidade de reconhecer comportamentos suspeitos, menor será a probabilidade de cair em esquemas fraudulentos ou tomar decisões inseguras.

A partilha de boas práticas também é importante. Familiares, colegas e pessoas com menor literacia digital podem beneficiar de orientações simples, como verificar remetentes, não clicar em links suspeitos, utilizar palavras-passe fortes e ativar autenticação de dois fatores.

A segurança não depende apenas de especialistas. Depende também da forma como cada pessoa utiliza a tecnologia no dia a dia.

> **Nota:**  
> **Literacia digital** é a capacidade de utilizar tecnologias digitais de forma informada, segura e crítica.  
> **Fraude digital** é qualquer esquema realizado através de meios digitais com o objetivo de enganar a vítima e obter dinheiro, dados ou acesso indevido.

---

## Síntese

Os fundamentos de cibersegurança mostram que a proteção digital começa por práticas simples, mas consistentes.

Palavras-passe fortes, autenticação de dois fatores, atualizações regulares, antivírus ativo, cuidado com emails e ficheiros, navegação segura, utilização prudente de redes Wi-Fi públicas, VPN, cópias de segurança, proteção física dos dispositivos e formação contínua constituem uma base essencial.

---

# Conceitos fundamentais de Segurança da Informação

Depois de compreender o conceito geral de cibersegurança, torna-se necessário aprofundar alguns conceitos fundamentais da segurança da informação. Estes conceitos ajudam a analisar melhor os riscos, a compreender a importância da proteção dos dados e a justificar as medidas de segurança aplicadas em sistemas, redes e organizações.

A segurança da informação preocupa-se com a proteção da informação em qualquer formato, seja digital, físico ou verbal. A cibersegurança, por sua vez, centra-se sobretudo na proteção da informação, dos sistemas e das infraestruturas no contexto digital.

Desta forma, a cibersegurança pode ser entendida como uma parte da segurança da informação, orientada para os riscos associados às tecnologias, às redes, às aplicações e aos dispositivos.

Esta distinção é importante porque nem toda a informação sensível existe apenas em computadores. Um documento impresso, uma conversa, uma palavra-passe escrita num papel ou um acesso partilhado indevidamente também podem representar riscos de segurança.

Estas medidas não eliminam todos os riscos, mas reduzem a probabilidade de ocorrência de incidentes e ajudam a limitar o seu impacto.

A partir desta base, torna-se possível avançar para conceitos mais específicos da segurança da informação, como confidencialidade, integridade, disponibilidade, ameaça, vulnerabilidade, risco, superfície de ataque e defesa em profundidade.


> **Nota:**  
> **Segurança da Informação** é a área que procura proteger a informação contra acesso indevido, alteração, perda, destruição ou divulgação não autorizada.  
> **Cibersegurança** é a aplicação desses princípios ao contexto digital, protegendo sistemas, redes, dispositivos, aplicações e dados.

---

## Tríade CIA: Confidencialidade, Integridade e Disponibilidade

A segurança da informação assenta em três princípios fundamentais: **Confidencialidade**, **Integridade** e **Disponibilidade**. Estes três princípios são frequentemente conhecidos como **tríade CIA**, devido aos termos em inglês *Confidentiality*, *Integrity* e *Availability*.

Esta tríade permite compreender os principais objetivos da proteção da informação. Sempre que se analisa um sistema, uma aplicação, uma rede ou um incidente, é possível avaliar de que forma estes três princípios podem ser afetados.

---

### Confidencialidade

A confidencialidade procura garantir que a informação apenas é acedida por pessoas, sistemas ou entidades autorizadas.

Este princípio está relacionado com a proteção contra acessos indevidos, exposição de dados, roubo de informação e divulgação não autorizada. Para garantir a confidencialidade, podem ser utilizadas medidas como palavras-passe fortes, autenticação de dois fatores, permissões de acesso, encriptação e políticas de segurança.

Um exemplo simples de quebra de confidencialidade ocorre quando uma pessoa acede a dados pessoais, documentos internos ou credenciais sem ter autorização para isso.

> **Nota:**  
> **Acesso autorizado** significa que uma pessoa ou sistema tem permissão legítima para consultar ou utilizar determinada informação.  
> **Dados sensíveis** são informações que exigem proteção especial, como dados pessoais, dados bancários, credenciais, documentos internos ou informação confidencial de uma organização.

---

### Integridade

A integridade procura garantir que a informação se mantém correta, completa e sem alterações indevidas.

Este princípio é importante porque os dados devem ser fiáveis. Mesmo que a informação esteja disponível e protegida contra acessos indevidos, deixa de ter valor se tiver sido alterada sem autorização, corrompida ou manipulada.

A integridade pode ser protegida através de controlos de acesso, registos de alterações, validação de dados, cópias de segurança, assinaturas digitais e mecanismos que permitam detetar modificações não autorizadas.

Um exemplo de quebra de integridade ocorre quando alguém altera o valor de uma transação, modifica um registo numa base de dados ou altera um ficheiro sem permissão.

> **Nota:**  
> **Corromper dados** significa tornar a informação incorreta, danificada ou inutilizável.  
> **Assinatura digital** é um mecanismo que permite verificar a autenticidade e a integridade de um documento ou mensagem.

---

### Disponibilidade

A disponibilidade procura garantir que sistemas, serviços e informação estão acessíveis quando são necessários.

Este princípio está relacionado com continuidade de serviço, estabilidade, capacidade de resposta e recuperação em caso de falha. Um sistema seguro não deve apenas proteger dados; deve também permitir que utilizadores legítimos consigam aceder aos serviços de que necessitam.

A disponibilidade pode ser afetada por falhas técnicas, avarias, ataques, erros humanos, cortes de energia, problemas de rede ou ausência de manutenção.

Medidas como cópias de segurança, redundância, monitorização, atualizações, planos de recuperação e proteção contra ataques de negação de serviço ajudam a garantir maior disponibilidade.

Um exemplo de quebra de disponibilidade ocorre quando um site, aplicação ou servidor deixa de estar acessível aos utilizadores legítimos.

> **Nota:**  
> **Redundância** significa ter recursos alternativos preparados para substituir outros em caso de falha.  
> **Ataque de negação de serviço**, também conhecido como DoS ou DDoS, procura tornar um serviço indisponível, sobrecarregando-o ou impedindo o seu funcionamento normal.

---

## Relação entre os três princípios

A confidencialidade, a integridade e a disponibilidade estão interligadas. Um incidente de segurança pode afetar apenas um destes princípios, mas também pode comprometer vários ao mesmo tempo.

Por exemplo, um ataque de ransomware pode afetar:

- a **confidencialidade**, se os dados forem roubados;
- a **integridade**, se os ficheiros forem alterados ou cifrados;
- a **disponibilidade**, se os utilizadores deixarem de conseguir aceder aos sistemas.

Da mesma forma, uma má configuração de permissões pode permitir que utilizadores sem autorização consultem, alterem ou apaguem informação. Nesse caso, os três princípios podem ficar em risco.

Compreender esta relação é essencial para analisar incidentes, avaliar riscos e escolher medidas de proteção adequadas.

---

## Ameaça, Vulnerabilidade e Risco

Para compreender a segurança da informação, é também necessário distinguir três conceitos fundamentais: **ameaça**, **vulnerabilidade** e **risco**.

Estes conceitos estão relacionados, mas não significam a mesma coisa. A sua distinção permite analisar melhor os problemas de segurança e perceber por que razão determinada situação pode representar perigo para um sistema ou organização.

---

### Ameaça

Uma ameaça é qualquer evento, ação, pessoa, grupo, falha ou circunstância com potencial para causar dano.

As ameaças podem ser intencionais ou acidentais. Podem surgir de atacantes externos, utilizadores internos, malware, falhas técnicas, erros humanos, fenómenos naturais ou problemas físicos.

Exemplos de ameaças incluem:

- phishing;
- malware;
- ransomware;
- roubo de credenciais;
- ataques de força bruta;
- falhas de energia;
- erro humano;
- roubo ou perda de equipamento;
- acesso indevido por utilizadores internos.

Uma ameaça, por si só, representa uma possibilidade de dano. Para causar impacto, normalmente precisa de explorar uma vulnerabilidade.

> **Nota:**  
> **Atacante** é uma pessoa ou grupo que tenta comprometer um sistema, roubar informação, causar dano ou obter acesso não autorizado.  
> **Erro humano** é uma ação involuntária que pode causar problemas de segurança, como apagar ficheiros, clicar num link fraudulento ou configurar mal um sistema.

---

### Vulnerabilidade

Uma vulnerabilidade é uma fraqueza, falha ou deficiência que pode ser explorada por uma ameaça.

As vulnerabilidades podem existir em software, hardware, redes, configurações, processos ou comportamentos humanos.

Exemplos de vulnerabilidades incluem:

- palavra-passe fraca;
- sistema desatualizado;
- aplicação com falhas de segurança;
- permissões mal configuradas;
- ausência de autenticação de dois fatores;
- falta de cópias de segurança;
- serviços expostos à Internet sem proteção adequada;
- utilizadores sem formação suficiente.

Uma vulnerabilidade não significa necessariamente que já ocorreu um incidente. Significa que existe uma fragilidade que pode ser explorada.

> **Nota:**  
> **Explorar uma vulnerabilidade** significa aproveitar uma falha para obter acesso, causar dano, alterar informação ou comprometer um sistema.  
> **Configuração insegura** ocorre quando um sistema, aplicação ou serviço está definido de forma incorreta ou demasiado permissiva.

---

### Risco

O risco resulta da combinação entre uma ameaça, uma vulnerabilidade e o impacto que poderá ocorrer caso essa vulnerabilidade seja explorada.

De forma simples, o risco representa a possibilidade de algo correr mal e causar consequências negativas.

Por exemplo, se uma aplicação estiver desatualizada e acessível através da Internet, existe o risco de um atacante explorar uma falha conhecida para comprometer o sistema.

O risco pode ser maior ou menor consoante a probabilidade de ocorrência e o impacto esperado. Uma vulnerabilidade num sistema pouco importante pode representar um risco reduzido. Já uma vulnerabilidade num sistema crítico, exposto publicamente e com dados sensíveis, pode representar um risco elevado.

> **Nota:**  
> **Probabilidade** é a possibilidade de um evento acontecer.  
> **Impacto** é a gravidade das consequências caso esse evento aconteça.  
> **Sistema crítico** é um sistema essencial para o funcionamento de uma pessoa, organização ou serviço.

---

## Exemplo prático

Um exemplo simples ajuda a compreender a relação entre estes conceitos:

```text
Situação:
Uma conta de email utiliza uma palavra-passe fraca e não tem autenticação de dois fatores.

Ameaça:
Um atacante tenta adivinhar ou obter a palavra-passe.

Vulnerabilidade:
A palavra-passe é fraca e a conta não tem uma segunda camada de autenticação.

Risco:
A conta pode ser comprometida.

Impacto:
O atacante pode aceder a mensagens, redefinir palavras-passe de outros serviços, roubar informação ou enviar emails fraudulentos em nome da vítima.

---
## Síntese

Os conceitos fundamentais de segurança da informação ajudam a compreender melhor a lógica da proteção digital.
A tríade CIA permite identificar os principais objetivos da segurança: proteger a confidencialidade, preservar a integridade e garantir a disponibilidade da informação e dos sistemas.
Os conceitos de ameaça, vulnerabilidade e risco ajudam a analisar situações de perigo, perceber como podem ocorrer incidentes e justificar a aplicação de medidas de proteção.
Compreender estes conceitos é essencial para avançar para temas mais práticos, como gestão de acessos, segurança de redes, análise de vulnerabilidades, monitorização, resposta a incidentes e investigação digital.
