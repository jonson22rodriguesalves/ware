# Santander Boot Camp 2025 Ciber Security
* 🦠 Simulação de Malwares - Estudo de Técnicas Ofensivas e Defensivas
  
* 📋 Resumo Executivo
 
* Este projeto documenta a implementação e análise de malwares simulados em ambiente controlado, com foco em ransomware 
* e keylogger. O objetivo é compreender técnicas ofensivas para desenvolver melhores estratégias defensivas em 
* cybersecurity.
   
* 🔬 Metodologia
  
* 🖥️ Ambiente de Teste
* Sistema Operacional: Linux Ubuntu 22.04 / Windows 10
* Linguagem: Python 3.8+
* Bibliotecas: cryptography, pynput, smtplib, socket
* Ambiente: Máquina virtual isolada
* Ferramentas: Wireshark, ClamAV, Windows Defender
   
* 🎯 Escopo dos Testes
* Desenvolvimento de ransomware simulado com criptografia AES
* Implementação de keylogger com captura e exfiltração de dados
* Análise de técnicas de evasão e persistência
* Documentação de medidas defensivas
 
* ⚙️ Implementação Técnica
 
* 🔐 Ransomware Simulado
* Estrutura de Criptografia:
 
* ⌨️ Keylogger Simulado  
* Captura de Teclas:
 
* 📊 Resultados dos Testes
* 🚨 Vulnerabilidades Demonstradas
 
 
* Técnica	Eficácia	Impacto Potencial	Detecção
* Criptografia de Arquivos	Alta	Crítico	Baixa (com evasão)
* Captura de Keylogger	Alta	Médio-Alto	Média
* Exfiltração por Email	Média	Médio	Alta
* Persistência no Sistema	Alta	Crítico	Variável
  
  
* 🔓 Acesso e Controle Obtido
* ✅ Criptografia bem-sucedida de arquivos de teste
* ✅ Captura eficiente de entrada de teclado
* ✅ Geração de ransom note persuasivo
* ✅ Operação furtiva em ambiente Windows
* ✅ Simulação de exfiltração de dados
 
* 🛡️ Medidas de Defesa e Prevenção
* 🔐 Fortalecimento de Sistemas
* Proteção Antivírus:
* Configuração de Firewall:
 
* 🏝️ Sandboxing e Isolamento
* Docker para Análise Segura:
 
* Análise Comportamental:
 
* 📚 Conscientização do Usuário
* Treinamento Essencial:
 
* Não abrir anexos de emails desconhecidos
* Verificar extensões de arquivos (.exe, .scr, .js)
* Manter sistemas e antivírus atualizados
* Fazer backup regular dos dados importantes
* Usar autenticação multifator quando possível
* Sinais de Alerta:
* Computador mais lento que o normal
* Arquivos com extensões estranhas
* Mensagens de resgate ou ameaça
* Atividade de rede incomum
 
* 🔍 Técnicas de Detecção Avançada
* 📊 Análise Heurística
 
* 🌐 Monitoramento de Rede
 
* ✅ Conclusão e Aprendizados
 
* 🎯 Principais Conclusões
* Técnicas de ransomware são eficazes contra usuários desprevenidos
* Keyloggers representam risco significativo para dados sensíveis
* A detecção proativa é essencial para mitigação rápida
* Educação do usuário é a primeira linha de defesa
 
* 📈 Recomendações de Segurança
* Backup Regular: Manter cópias offline dos dados importantes
* Atualizações: Manter todos os softwares atualizados
* Monitoramento: Implementar soluções EDR (Endpoint Detection and Response)
* Políticas de Execução: Restringir execução de scripts não autorizados
* Segmentação de Rede: Isolar sistemas críticos
 
* 🔮 Melhorias Futuras
* Implementar técnicas mais avançadas de evasão
* Desenvolver análise de malware em tempo real
* Criar simulador de ataques para treinamento
* Integrar com ferramentas SIEM para correlação.