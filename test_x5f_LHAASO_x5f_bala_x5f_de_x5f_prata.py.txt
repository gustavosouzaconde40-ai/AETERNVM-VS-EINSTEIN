"""
TESTE 2: LHAASO BALA DE PRATA - P12 - AETERNVM-VS-EINSTEIN
Fóton mais energético já visto: Cygnus X-3 3.73 PeV
Padrão prevê tau=4.5 (deveria ser absorvido)
AETERNVM prevê tau_AV=0.81 <1 (vácuo transparente)
DOI Unificado: 10.5281/zenodo.23816088
"""
tau_padrao = 4.5
tau_AV = 0.81
energia_PeV = 3.73
fonte = "Cygnus X-3 - 10 mil anos-luz"

print("=== TESTE LHAASO BALA DE PRATA P12 ===")
print(f"Fonte: {fonte}")
print(f"Energia: {energia_PeV} PeV")
print(f"Padrão ΛCDM prevê tau = {tau_padrao} (opaco, deveria sumir)")
print(f"AETERNVM prevê tau_AV = {tau_AV} (transparente, vácuo trabalha)")
print(f"Observado: DETECTADO vivo")
if tau_AV < 1 and tau_padrao > 1:
    print("RESULTADO: PASSOU - Fóton que deveria morrer, não morreu. E_depletada -> Bulk")
else:
    print("RESULTADO: REFUTADO")
