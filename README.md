
# Bootcamp DIO - Cibersegurança Santander - Phishing para Captura de Senhas do Facebook

**Atenção:** Este projeto é para fins educacionais e de teste em ambientes controlados. O uso de phishing sem permissão é ilegal e antiético.

## Ferramentas Utilizadas

- **Kali Linux**: Distribuição de segurança e testes de penetração.
- **SEToolkit**: Ferramenta de engenharia social para criação de ataques de phishing e outros.

## Configurando o Phishing no Kali Linux

### Passo 1: Acesso como root
Primeiro, abra o terminal no Kali Linux e obtenha acesso root:

```bash
sudo su
```

### Passo 2: Iniciando o SEToolkit
Inicie o **SEToolkit** no Kali Linux:

```bash
setoolkit
```

### Passo 3: Escolhendo o Tipo de Ataque
Dentro do SEToolkit, selecione as opções abaixo:

1. **Tipo de ataque**: Social-Engineering Attacks
2. **Vetor de ataque**: Web Site Attack Vectors
3. **Método de ataque**: Credential Harvester Attack Method
4. **Método de ataque adicional**: Site Cloner

### Passo 4: Obter o Endereço da Máquina
Descubra o endereço IP da sua máquina com o comando:

```bash
ifconfig
```

### Passo 5: URL para o Clone
Forneça a URL que você deseja clonar. Neste caso, usaremos o **Facebook**:

```
http://www.facebook.com
```

![image](https://github.com/user-attachments/assets/b97d39c7-64bc-4da4-a241-77e15035c5a6)


### Passo 6: Resultados
O SEToolkit irá clonar o site do Facebook e você poderá capturar credenciais (como nome de usuário e senha) inseridas pelos usuários no site clonado.

![image](https://github.com/user-attachments/assets/62f634c7-0bfa-465b-9f48-210a51e4eef4)

![image](https://github.com/user-attachments/assets/50ccb71e-0a92-4d68-bea5-ad6cd4f7b752)


---

**Disclaimer**: Use esta ferramenta apenas em ambientes de teste e com permissão explícita. O phishing é ilegal sem o consentimento da vítima e viola as normas de ética cibernética.

## Licença

Este repositório está licenciado sob a [Licença MIT](LICENSE).
