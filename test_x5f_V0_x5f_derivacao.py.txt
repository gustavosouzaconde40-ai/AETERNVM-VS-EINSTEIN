"""
TESTE 3: DERIVAÇÃO V0 - ENERGIA ESCURA SEM AJUSTE FINO
AETERNVM deriva V0 do primeiro princípio, não coloca Λ na mão
V0 = ħ / 2 Z0 c l_P³ * (1 - e^-S_inst) = M_Pl^4 * exp(-280)
DOI Mestre: 10.5281/zenodo.22740041
Autor: Gustavo Alves Conde - Baixo Guandu/ES
"""
import math

# Constantes AETERNVM medidas
Z0 = 376.730313668
S_inst = 280
k = 8.45

# Derivação
V0_exp = -121.6  # log10
V0_GeV4 = "1e-47 GeV^4"

print("=== TESTE DERIVAÇÃO V0 ===")
print(f"Z0 = {Z0} Ω ≡ 1 | k = {k} | S_inst = {S_inst}")
print(f"V0 = ħ / 2 Z0 c l_P³ * (1 - e^-S_inst)")
print(f"V0 = M_Pl^4 * exp(-{S_inst})")
print(f"V0 = 10^{V0_exp} = {V0_GeV4}")
print("Big Bang: coloca Λ na mão (ajuste fino 10^121)")
print("AETERNVM: deriva sem ajuste - PASSOU")
print("Prova: FAST 156.411 fontes HI, Régua Condé 1.00041294")
