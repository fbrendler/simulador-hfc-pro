# Simulador PRO HFC/G-PON/XGS-PON

**Versão Prévia 0.33** · by BRENDLER™

Simulador de projetos de rede coaxial (TV e banda larga HFC) e de fibra óptica (GPON / XGS-PON) que roda direto no navegador, no PC, tablet ou celular deitado, inclusive sem internet.

**Usar online:** https://simulador-pro-hfc-gpon-xgspon.pages.dev

## O que ele faz

- Monta a instalação a partir de um **TAP Rede externa** (2, 4 ou 8 vias) ou de um **DG** (4 vias, só RG6 Branco).
- Passivos: divisores 1/2, 1/3, 1/3D, 1/4, 1/8, DCs 6, 9, 12, 16, 20, **CABLE ISOLATOR**, **MINI ISOLATOR** e **TRAVA LOCK** (toda saída de passivo sem cabo precisa de TRAVA LOCK; o simulador alerta).
- Cabos RG6 Branco, RG6 Preto e RG11 (RG11 só no cabo de entrada acima de 80 m).
- Calcula CA, CB, RX e TX em cada EMTA, Decoder e Box TV e compara com o padrão: TX 38 a 51, RX −12 a 12, CA e CB ≥ 0 (dBmV).
- Alerta de TX na origem: TAP 36 a 43, DG 37 a 43.
- Sugestões de correção testadas no projeto (só aparecem as que funcionam).
- Cenários (Cenário+ cria um cenário em branco que salva sozinho), relatório técnico com desenho da topologia, salvar como JSON ou como HTML offline com o projeto dentro.

- **Modo GPON / XGS-PON** (chave no topo): CTO 8/16 portas com potência em dBm, divisor 1:2 (3,5 dB), PTO (1 entrada e 1 saída, vertical), fibras Drop Low Friction, Cabo Micro Low e Fibra Invisível (metros + conectores), cordão óptico (1,0 a 1,6 dB) e ONT/ONU com MÍN e MÁX: RX OK de −8 a −27 dBm (fora disso, vermelho; não há faixa amarela). Potência na NAP/DIO esperada de 0 a −25 dBm (fora disso, alerta na origem).

## Reportar bug ou falar com o autor

- No simulador: botão **?** → **Reportar bug** ou **Contato**.
- Aqui no GitHub: aba **Issues** → **New issue**.
- E-mail: fabiobrendler@outlook.com

## Arquivos

- `index.html`: o simulador completo em um único arquivo (estilos, ícones e fonte embutidos).
