# Registro de Testes de Software

Os testes funcionais realizados na aplicação web são descritos a seguir.

|Caso de Teste    | CT-01: Verificar o funcionamento dos links da página Home |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Beatriz |

https://user-images.githubusercontent.com/100447878/174854223-c457e6ca-a9ce-48d3-aba9-b9e617132f31.mov

|Caso de Teste    | CT-02: Verificar o funcionamento do filtro de pesquisa. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Beatriz |

Filtro da página Livros:
    
![Captura de Tela 2022-06-21 às 13 50 15](https://user-images.githubusercontent.com/100447878/174855824-6afdd9f8-9d77-4e2d-b20b-bd62977586ea.png)

Filtro da página Tutorias:
    
![Captura de Tela 2022-06-21 às 13 56 27](https://user-images.githubusercontent.com/100447878/174856220-f128f9d7-0e78-46e9-a80c-56545101d0d2.png)

No caso abaixo, o termo digitado não fazia parte das informações cadastradas dos livros. Assim, não houve retorno de livros registrados.
    
![Captura de Tela 2022-06-21 às 13 56 09](https://user-images.githubusercontent.com/100447878/174856402-2a4e38b6-bf79-4ec0-8b3e-26063f99f4e1.png)

|Caso de Teste    | CT-03: Verificar detalhes dos livros. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Silvia |

![Captura de Tela 2022-06-21 às 14 00 59 (2)](https://user-images.githubusercontent.com/100447878/174856950-9d27862f-5d4d-407b-95f3-70e9b152dc49.png)

|Caso de Teste    | CT-04: Verificar o cadastro de usuários. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Pedro |

Usuário preenche os campos "Senha" e "Confirmaçāo de Senha" com valores diferentes.
      
![Screen Shot 2022-06-01 at 15 14 13](https://user-images.githubusercontent.com/81182674/171474105-64632f30-5457-4366-852d-68145a28b2b3.png)
    
Verificar se o usuário foi cadastrado.
    
![Screen Shot 2022-06-01 at 14 57 22](https://user-images.githubusercontent.com/81182674/171472447-009af414-aaa4-45fb-abb8-e76a23430875.png)
    
Informações armazenadas no LocalStorage após usuário se cadastrar.
    
![Screen Shot 2022-06-01 at 15 20 21](https://user-images.githubusercontent.com/81182674/171475137-83469b08-7778-4391-a725-ad4b3b3d2a77.png)

|Caso de Teste    | CT-05: Verificar o login de usuários. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Ana |
  
Usuário preenche os campos "Email" e "Senha" com valores diferentes do usuário já cadastrado.
  
![8d33f1db-e0a7-4e41-b956-fde91ac31c63](https://user-images.githubusercontent.com/98122346/174851091-f201d92d-02f9-45c0-8b00-e66358158d8d.jpg)

Se as informações de usuário forem válidas, o login será bem sucedido.
  
![c555f947-3721-4eee-ad97-5042ce9e6c5e](https://user-images.githubusercontent.com/98122346/174853350-696ef44f-cbc9-4cad-a0e5-7c51d3a67d4b.jpg)

Informações armazenadas no LocalStorage do usuário logado.

![af4b5123-e45f-4356-bd53-11b5c75cb78f](https://user-images.githubusercontent.com/98122346/174853422-4572412d-173c-457b-ade9-7d7fc997445e.jpg)

|Caso de Teste    | CT-06: Verificar o cadastro de livros. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Pedro |

Mensagem de confirmação de cadastro do livro.

![Captura de Tela 2022-06-21 às 14 15 34](https://user-images.githubusercontent.com/100447878/174859699-0de48c01-faa1-4362-ac5c-f5a9a337e3c8.png)

Registro disponível na página Livros após o usuário cadastrar o livro.

![Captura de Tela 2022-06-21 às 15 51 10](https://user-images.githubusercontent.com/100447878/174876692-ebcfba83-0af7-4449-a378-f0e8091227f4.png)  

Informações armazenadas no LocalStorage após o cadastro do livro.
  
![Captura de Tela 2022-06-21 às 15 52 42](https://user-images.githubusercontent.com/100447878/174876742-e0b01a57-7503-4719-8a87-3ea07d68964c.png)

No exemplo abaixo, o usuário tenta fazer o cadastro do livro de maneira incorreta, sem preencher todos os campos, o que não finaliza o cadastro.
  
![Captura de Tela 2022-06-21 às 14 14 40](https://user-images.githubusercontent.com/100447878/174859774-24a2ca76-c97f-4ae9-9741-418d536a0e53.png)

![Captura de Tela 2022-06-21 às 14 14 59](https://user-images.githubusercontent.com/100447878/174859799-2f7805e2-ff98-415a-aff3-4898d27c879a.png)

|Caso de Teste    | CT-07: Verificar o cadastro de tutores. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | João |

Mensagem de confirmação de cadastro do tutor.
  
![image](https://user-images.githubusercontent.com/101907319/174912389-5ad42624-397a-4ac5-b3c9-add2b13880cb.png)

Registro disponível na página Tutorias após o usuário cadastrar o tutor.
  
![image](https://user-images.githubusercontent.com/101907319/174912436-6ecd1e3d-16db-4ed9-b0f7-e4174ce22d2b.png)

Informações armazenadas no LocalStorage após o usuário cadastrar o tutor.
  
![image](https://user-images.githubusercontent.com/101907319/175368958-66502c11-634a-4a4f-bddb-2c29aa80a969.png)
  
No exemplo abaixo, o usuário tenta fazer o cadastro do tutor de maneira incorreta, sem preencher todos os campos, o que não finaliza o cadastro.
  
![image](https://user-images.githubusercontent.com/101907319/175367758-cc3efcaa-42b5-4e2c-b300-39f19bbebb20.png)

![image](https://user-images.githubusercontent.com/101907319/175367829-3ecabdbf-e559-4377-a7fa-5e4a5ef4b36e.png)

Caso de Teste    | CT-08: Verificar a página de Tutores. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Pedro |

![Captura de Tela 2022-06-20 às 18 40 10](https://user-images.githubusercontent.com/100447878/174680988-44d52b0f-3397-4744-86bc-7246bff79957.png)

Caso de Teste    | CT-09: Verificar a página de perfil de usuários cadastrados. |
|:---|:---|
| Resultados obtidos | Teste atendido  |
| Responsável pela execução do caso de Teste | Pedro |
![Captura de Tela 2022-06-20 às 10 50 33](https://user-images.githubusercontent.com/100447878/174616506-d93f95de-3bd7-44f2-9323-d8bf0b3b4b2b.png)

## Avaliação

Os testes de software mostraram que os requisitos priorizados foram atendidos, funcionando como planejado. Para as próximas iterações, serão acrescentadas melhorias no layout e responsividade da aplicação.
