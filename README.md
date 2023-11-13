# Grupo_Unis-mg
Projeto para faculdade de sistema de informaçao grupo Unis-mg
Codigo
"""
Aula de python unis-mg
Prof.Alberane
Aluno.Danilo Venancio Belato
"""
##Calculadora de anos-meses-dias
idade_em_dias = int(input("Digite sua idade em dias: "))

# converter as idades
anos = idade_em_dias // 365
meses = (idade_em_dias % 365) // 30
dias = (idade_em_dias % 365) % 30

print(f"A idade é de {anos} anos, {meses} meses e {dias} dias.")
