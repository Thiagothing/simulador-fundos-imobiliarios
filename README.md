Simulador de Fundos Imobiliários

Perguntas que a ferramenta responde
1. **Quanto investir por mês** → R$ 300 (campo “Investimento mensal”).  
2. **Por quantos anos** → 5 anos.  
3. **Qual a taxa de rendimento mensal** → 1,0789% (campo “Taxa de rendimento mensal”).  
4. **Quanto de patrimônio vai acumular** → Calculado com a função VF, considerando aporte de R$ 300, taxa de 1,0789% e prazo de 60 meses.  
5. **Quanto vai receber de dividendos por mês** → Calculado multiplicando o patrimônio acumulado pela taxa mensal.

---

Fórmulas utilizadas
### VF (Valor Futuro)
- **taxa_mensal**: rendimento da carteira (1,0789%).  
- **prazo_em_meses**: anos × 12 (5 anos = 60 meses).  
- **-aporte**: valor investido mensalmente (R$ 300).  
- **0**: valor presente inicial.  

➡ Resultado: patrimônio acumulado ao final do período.

### PROCV (Procura Vertical)
Usado para buscar o percentual de cada tipo de fundo conforme o perfil escolhido.  
A **chave composta** junta “perfil + tipo de fundo”, garantindo que o PROCV encontre o percentual correto.

---

## Intervalos nomeados
- **aporte** → valor do investimento mensal.  
- **taxa_mensal** → rendimento esperado da carteira.  
- **prazo** → número de anos da simulação.  
- **salario** → usado para calcular a sugestão de aporte de 30%.  
- **perfil** → seleção do perfil de investidor.  

---

## 📈 Perfis de investidor
Percentuais definidos na aba de apoio:

- **Conservador**:  
  - Papel: 30%  
  - Tijolo: 50%  
  - Híbrido: 10%  
  - FOFs: 10%  
  - Desenvolvimento: 0%  
  - Hotelarias: 0%  

- **Moderado**:  
  - Papel: 32%  
  - Tijolo: 35%  
  - Híbrido: 8%  
  - FOFs: 5%  
  - Desenvolvimento: 10%  
  - Hotelarias: 10%  

- **Agressivo**:  
  - Papel: 50%  
  - Tijolo: 10%  
  - Híbrido: 5%  
  - FOFs: 5%  
  - Desenvolvimento: 20%  
  - Hotelarias: 10%  

*(Esses percentuais são apenas exemplos, não recomendação de investimento.)*

---

## Diferenças em relação à ferramenta do Expert
- Usei percentuais próprios para cada perfil.  
- Adicionei cenários de 2, 5, 10, 20 e 30 anos.  
- Personalizei a aba de configurações com salário e sugestão de aporte (30%).  
- Estruturei a tabela de apoio com chave composta para facilitar o PROCV.  

---

## Evidências
<img width="523" height="520" alt="image" src="https://github.com/user-attachments/assets/e7ec690a-ec5f-4aa3-b1bd-f8f2af9ea94f" />

<img width="523" height="557" alt="image" src="https://github.com/user-attachments/assets/e1ac8036-dc46-4de6-9325-b7c7d5635ca3" />

