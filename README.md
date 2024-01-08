# 🚀 Open Network Unit (ONU) Repository

Bem-vindo ao repositório dedicado à Open Network Units (ONUs)! Este espaço é seu guia completo para acessar, configurar e explorar diferentes modelos de ONU via Telnet. Aqui, você encontrará informações detalhadas sobre como habilitar o HTTP em portas WAN e garantir uma experiência de usuário sem complicações.

## ℹ️ Sobre ONUs

As Open Network Units (ONUs) desempenham um papel crucial em redes de fibra óptica, proporcionando conectividade de alta velocidade e confiabilidade aos usuários finais. Este repositório oferece insights e instruções para facilitar o acesso e a configuração desses dispositivos.

## 🌐 Modelos de ONU

Explore os modelos de ONU suportados:

1. **Modelo da Think**
    - [Acesso via Telnet](./onu-modelos/xyz-1000/telnet/README.md)
    - [Configurações HTTP](./onu-modelos/xyz-1000/http/README.md)

2. **Modelo Stavix**
    - [Acesso via Telnet](./onu-modelos/abc-2000/telnet/README.md)
    - [Configurações HTTP](./onu-modelos/abc-2000/http/README.md)

## 🔒 Credenciais de Acesso

- **Login:** root
- **Senha:** Root544b ou Pon521

## 🚪 Acesso via Telnet

Siga estes passos para acessar a ONU via Telnet:

1. Abra o seu cliente Telnet no seu computador.
2. Conecte-se à ONU usando o endereço IP correspondente.

```plaintext
telnet <endereço IP da ONU>
```

3. Insira as credenciais de acesso quando solicitado.

## 🌐 Habilitando HTTP na Porta WAN

Para habilitar o HTTP na porta WAN, utilize o seguinte comando:

```plaintext
ip iptables -F
```

Este comando limpará as regras do iptables, permitindo o acesso HTTP através da porta WAN.

## 🛠️ Dicas Adicionais

- **Segurança:** Certifique-se de alterar as senhas padrão por razões de segurança.
- **Documentação:** Consulte o manual do usuário específico do modelo de ONU para informações detalhadas sobre configurações e funcionalidades.

## 🚀 Pronto para Explorar

Agora você está pronto para explorar e configurar suas ONUs! Utilize as informações fornecidas para personalizar suas configurações e otimizar o desempenho da sua rede.

Divirta-se explorando as possibilidades das Open Network Units! 🌐💡
