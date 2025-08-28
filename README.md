## 🔹 Requisitos

### Frontend
Criar uma interface simples com um formulário de cadastro de sinistro contendo os seguintes campos:

- **CNPJ** (Campo formatado como o exemplo: `02.229.683/0001-50`)
- **Motivo do sinistro** (campo de texto livre, ex.: *"Roubo de veículo com a carga"*)
- **Valor do prejuízo** (campo monetário, ex.: `R$ 2.000.000,00`)
- **Código do embarque** (campo livre, ex.: `32422`)
- **Consulta ao motorista** (campo de seleção do tipo *radio button* com duas opções):  
  - "Antes da liberação do motorista"  
  - "Depois da liberação do motorista"  

  > Caso seja selecionada a opção **Depois**, o valor do prejuízo deve ser reduzido em **25%** para fins de cálculo da indenização.

- **Valor indenizado** (campo calculado e exibido com base nas regras acima).

---

### Backend
- Criar um endpoint para registrar sinistros (armazenamento pode ser em banco em memória).

---

## 🔹 Extras *(opcional, para destaque do candidato)*

- Página de **listagem de sinistros**, com exibição dos dados cadastrados.  
- **Relatório resumido**, contendo:  
  - Total de sinistros registrados  
  - Valor total indenizado  

- **Autenticação e autorização**:  
  - Usuário comum → pode apenas registrar sinistros  
  - Administrador → pode aprovar ou gerenciar sinistros  

---

## 🚀 O que será avaliado

- Organização e clareza do código  
- Estruturação do frontend e backend  
- Implementação correta da regra de negócio  
- Qualidade na comunicação entre as camadas (API)  
- Uso adequado de boas práticas (ex.: versionamento, documentação, consistência de nomenclatura)  

---

👉 **Sugestão**: entregue junto um `README.md` com instruções de execução do projeto (como rodar frontend e backend).

## Layout
<img width="1440" height="900" alt="Form Sinistro (1)" src="https://github.com/user-attachments/assets/4595e2d8-074a-40c2-827d-3b5fbf9a402f" />


