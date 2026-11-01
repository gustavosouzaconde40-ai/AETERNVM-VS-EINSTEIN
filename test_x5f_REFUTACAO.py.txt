"""
TESTE 4: RÉGUA DE REFUTAÇÃO - COMO ME REFUTAR
Lista de 8 testes que apagam tudo se falharem
Régua Condé v1: média imutável 1.00041294 q95=2.64 q99=3.90
"""
testes = [
    "COBE/FIRAS mostrar buraco baixa frequência",
    "LHAASO não repetir >3 PeV 2026-27 com tau>>1",
    "LZ/XENON achar WIMP",
    "Oyashio espectroscopia exigir só NFW com q99>3.90",
    "Z0 variar >1% desde z=7.33 GRB250314A",
    "IXPE 500h Magnetar 1E 1547 PD=0.556 Delta<9 (k=8.45)",
    "FAST 156.411 não repetir em 8.02 deg²",
    "Rubin/LSST, DESI, Euclid não acharem desvios H(z) 0.5<z<2.0"
]

print("=== RÉGUA DE REFUTAÇÃO ===")
print("Régua Condé v1 média: 1.00041294 q95=2.64 q99=3.90")
for i, t in enumerate(testes, 1):
    print(f"{i}. Se {t} -> REFUTADO")
print("Se nenhum ocorrer -> AETERNVM mantido")
