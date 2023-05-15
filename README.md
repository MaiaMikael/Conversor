# Conversor
Conversor de peso/kg/

def converter_quilos_para_toneladas(kilos):
    """Função que converte quilos para toneladas."""
    toneladas = kilos / 1000
    return toneladas

def main():
    try:
        quilos = float(input("Digite o peso em quilos: "))
        toneladas = converter_quilos_para_toneladas(quilos)
        print("O peso em toneladas é:", toneladas)
    except ValueError:
        print("Entrada inválida. Por favor, digite um valor numérico para o peso.")

    print("FIM")


    if __name__ == '__main__':
    main()
