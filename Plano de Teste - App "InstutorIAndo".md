# Plano de Teste para Autenticação de Usuário no Aplicativo "InstutorIAndo"

![image](https://github.com/yasmindematos/QA/assets/98225965/e580ecd4-35f4-4320-ac04-5e306f805982)


https://www.figma.com/proto/cG635oMzNURlWSWNERTAa3/InstrutorIAndo---Yasmin-de-Matos?type=design&node-id=502-76&t=gbHLMFjEyjGmfTQO-1&scaling=scale-down&page-id=8%3A77&starting-point-node-id=502%3A76&show-proto-sidebar=1&mode=design

## Objetivo 

Garantir que o processo de autenticação da pessoa usuária seja eficiente e seguro, abrangendo login, registro e manutenção de sessões ativas.

## Preparação do Ambiente de Teste

- Ambiente de teste configurado com a versão mais recente do aplicativo MentorIA.

## Casos de Teste

### Tela de Login

#### **CT-01: Login com sucesso**
<br>

⮕ Objetivo: 
<br>

Verificar se pessoa usuária pode fazer login com credenciais válidas.
<br>

⮕ Passos:
<br>

- Inserir um e-mail e senha válidos nos campos correspondentes.
- Clicar no botão "Entrar".

⮕ **Resultado Esperado**: 
<br>

Redirecionamento para a tela principal com a sessão de usuário/usuária ativa.
<br>

#### **CT-02: Login com credenciais inválidas**

⮕ Objetivo: 
<br>

Confirmar que login com credenciais inválidas é negado.
<br>

⮕ Passos:
<br>

- Inserir e-mail e senha inválidos.
- Clicar no botão "Entrar".

⮕ **Resultado Esperado**: 
<br>

Mensagem de erro e permanência na tela de login.
<br>

### Tela de Registro de Conta Nova
<br>

#### **CT-03: Registro de Conta Nova com Sucesso**
<br>

⮕ Objetivo: 
<br>

Assegurar que pessoa usuária pode registrar uma nova conta
<br>

⮕ Passos:
<br>

- Preencher todos os campos com informações válidas.
- Clicar no botão "Criar conta nova".

⮕ **Resultado Esperado**: 
<br>

Exibição da mensagem "Conta criada com sucesso!" e opção para acessar a página inicial.
<br>

#### **CT-04: Registro com Senha Fraca**
<br>

⮕ Objetivo: 
<br>

Verificar a validação da força da senha durante o registro.
<br>

⮕ Passos:
<br>

- Preencher todos os campos, mas inserir uma senha que não atende aos requisitos de segurança.
- Clicar no botão "Criar conta nova".
<br>

⮕ **Resultado Esperado**: 
<br>

Mensagem de erro indicando a necessidade de uma senha mais forte.
<br>

### Tela de Inatividade
<br>

#### **CT-05: Sessão Expirada por Inatividade**
<br>

⮕ Objetivo:
<br>

Verificar o comportamento do aplicativo após inatividade prolongada.

⮕ Passos:
<br>
- Logar no aplicativo e não realizar nenhuma ação durante o tempo estipulado para expiração da sessão.
<br>

⮕ **Resultado Esperado**: 
<br>

Exibição da tela "Tente novamente!" com a opção de continuar o cadastro.
<br>

## Procedimentos de Execução

- Executar os casos de teste em diferentes dispositivos e sistemas operacionais.
- Utilizar dados de teste variados para cobrir o máximo de cenários possíveis.
- Registrar os resultados de cada caso de teste, incluindo capturas de tela, se aplicável.


## Pós-Teste

- Avaliar resultados obtidos e documentar quaisquer defeitos ou problemas encontrados.
- Priorizar os defeitos com base em sua gravidade e impacto na experiência das pessoas usuárias.
- Comunicar a equipe de desenvolvimento para correções e acompanhamento dos itens reportados.


